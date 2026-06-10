# *mpm Tools* system guide

## Project overview

The **mpm Tools** is a **VS Code** extension that makes it easy to work with **mpm** and its file **mpm.json**.


## Tech stack

- **Programming languages**:
  **JavaScript** and **MicroPython 1.28+**.


## Project structure

The codebase is organized as follows:

```
/
├── mpm-tools/  # extension code
├── scripts/    # scripts used during the development
└── files.txt   # list of files to download and install
```


## Development Workflow & Commands

- **File sync**:
  Synchronize the file **files.txt** used by **`mpm vscode`** for installing the extension:

  ```bash
  scripts/sync
  ```
