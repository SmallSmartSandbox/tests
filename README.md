# tests

Standardized evaluation tests for the SSSB sandbox.

Tests are grouped by **level** in subfolders (e.g. `simple/`). Each test case contains:
- `task.json` — task definition, limits, expected files, allowed tools
- `workspace/` — files the agent operates on

## Simple

| Test | Description |
| --- | --- |
| [simple-read-file](./simple/simple-read-file/) | Read a file and print its contents |
| [simple-edit-file](./simple/simple-edit-file/) | Append text to a file |
| [simple-fetch-tool-call](./simple/simple-fetch-tool-call/) | Fetch a URL and write a summary |
| [simple-write-file](./simple/simple-write-file/) | Create a new file using write mode |
| [simple-combine-files](./simple/simple-combine-files/) | Read multiple files and combine their contents |
| [simple-copy-file](./simple/simple-copy-file/) | Read a file and reproduce its contents in a new file |
| [simple-tool-denial](./simple/simple-tool-denial/) | Respect tool allowlists and refuse denied actions |

## Medium

| Test | Description |
| --- | --- |
| _none yet_ | |

## Complex

| Test | Description |
| --- | --- |
| _none yet_ | |
