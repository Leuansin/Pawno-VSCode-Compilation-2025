# PAWN Compile Task for VS Code

This repository provides a ready-to-use `tasks.json` configuration to compile **PAWN scripts** (`.pwn`) for **SA-MP (San Andreas Multiplayer)** directly from **Visual Studio Code**. It resolves common issues with spaces in file paths and custom compilation flags.

---

## Features

- Compiles PAWN scripts (`.pwn`) with a single key combination.
- Handles file paths with spaces.
- Supports custom compiler flags (`-Dgamemodes`, debugging options, etc.).
- Integrated with VS Code’s tasks system for a seamless workflow.

---

## Usage

1. Open VS Code
2. Press **(CTRL + K + O)**
3. Choose the whole folder where the server is
4. Go to: Terminal/Configure Tasks/Create tasks.json/msBuild
5. Go to the .vscode folder that VS Code just created
6. Copy n Paste all the content from the tasks.json in this repository to the tasks.json newly created in the .vscode folder
7. Make sure you are viewing and have opened the .pwn file you are modifying
8. Press **Ctrl+Shift+B** (or **Cmd+Shift+B** on macOS) to run the default build task.
9. The output will appear in the terminal panel. If compilation succeeds, your `.amx` file is generated in the same directory as your `.pwn`.

---

## Notes

- Make sure all paths use **forward slashes** (`/`) or are properly quoted to avoid errors with spaces.
- Adjust the compiler flags in the `args` section according to your needs.
- This setup was tested on **Windows 10/11** with VS Code.

---

## License

This repository is open-source and free to use. You can modify it to suit your own SA-MP development workflow.
