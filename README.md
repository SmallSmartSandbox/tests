# tests

Standardized evaluation tests for the SSSB sandbox.

Each subdirectory is a test case containing:
- `task.json` — task definition, limits, expected files, allowed tools
- `workspace/` — files the agent operates on; need to be cloned into the actual SSSB-workspace

## Tests

| Test | Description |
| --- | --- |
| [basic-read-file](./basic-read-file/) | Read a file and print its contents |
| [basic-edit-file](./basic-edit-file/) | Append text to a file |
| [basic-fetch-tool-call](./basic-fetch-tool-call/) | Fetch a URL and write a summary |
| [basic-write-file](./basic-write-file/) | Create a new file using write mode |
| [basic-combine-files](./basic-combine-files/) | Read multiple files and combine their contents |