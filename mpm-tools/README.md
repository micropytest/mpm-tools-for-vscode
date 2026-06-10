# mpm Tools for VS Code


The **mpm Tools extension** makes it easy to work with the **mpm.json** file.

> **Important**.
> Make sure you have the latest version of the extension for working with the latest validation and snippets.

## Install

You can install/update the **VS Code** extension with the following procedure:

01. Go to [https://github.com/micropytest/mpm-tools-for-vscode](https://github.com/micropytest/mpm-tools-for-vscode).

02. Copy the directory **mpm-tools** into **~/.vscode/extensions/mpm-tools**.
    This should look as follows:

    ```
    ~/.vscode/extensions/mpm-tools/
    ├── schemas/...
    ├── snippets/...
    ├── package.json
    └── README.md
    ```

03. Reboot **VS Code** if started.

Alternatively, you can install/update the extension via **mpm**:

```bash
micropython -m mpm vscode
```


## Features

- **JSON validation**:
  
  - The **mpm\*.json** files are validated with the **mpm JSON Schema**.
  
  - The **package.json** file is validated with the **package.json Schema** from **MicroPython**.

- **Snippets**:
  These use the prefix **mpm-** such as, for example, **mpm-init** for generating the initial content for a **mpm.json** file.
