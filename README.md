# pasco-results
This repository contains the generated abstractions produced by the tool PASCo. The folders are structured based on the parameters used during the generation process.

## Folder Structure

- **k_n**: Indicates the `k_bound` parameter used to set up PASCo.
- **t_600**: Indicates the timeout used in seconds.

## File Types

Each generated abstraction contains the following files:
- `.epa` or `.states`: The abstraction in EPA mode or states (for enum).
- `.csv`: The query times for that abstraction.
- `.txt`: Extra information.