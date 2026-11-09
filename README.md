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
| [medium-sort-names](./medium/medium-sort-names/) | Read a list of names and write them sorted alphabetically |
| [medium-deduplicate-lines](./medium/medium-deduplicate-lines/) | Remove duplicate lines while preserving first occurrence order |
| [medium-filter-students](./medium/medium-filter-students/) | Filter students by score threshold into passing and failing files |

## Complex

| Test | Description |
| --- | --- |
| [complex-financial-reconciliation](./complex/complex-financial-reconciliation/) | Join orders, FX rates, and refunds to compute net revenue across customers, months, and currencies |
| [complex-inventory-reorder](./complex/complex-inventory-reorder/) | Compute EOQ and reorder points from inventory and demand statistics |
| [complex-incident-timeline](./complex/complex-incident-timeline/) | Reconstruct incidents from event logs and compute durations, severity, and root causes |
| [complex-feedback-analysis](./complex/complex-feedback-analysis/) | Score text feedback using a lexicon and produce sentiment and term-frequency summaries |
