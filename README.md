# exereverse

`exereverse` is a Python package designed to extract files from `.exe` files created by PyInstaller. It simplifies the process of handling these `.exe` files by automating the extraction process and managing the necessary tools for you.

## Benefits

- **Automated Extraction**: Extracts files from `.exe` files created by PyInstaller with minimal user intervention.
- **Easy Installation**: Installs all required dependencies automatically.
- **User-Friendly**: Provides a straightforward command-line interface for ease of use.
- **Cross-Platform**: Works on Windows, macOS, and Linux.

## Installation

You can install `exereverse` directly from PyPI using pip:

```bash
pip install exereverse
```

## Usage

Once installed, you can use `exereverse` from the command line. Here are some common commands:

- **Extract an executable:**

```bash
exereverse --file path_to_exe_file.exe
```

This will extract the contents of the specified `.exe` file into a default directory named `extracted_files`.

- **Get help and see available commands:**

```bash
exereverse --help
```

This will display the help information and usage instructions.

## Benefits

- **Efficient Extraction**: Quickly extract files without needing to manually handle different tools.
- **Simple Interface**: User-friendly command-line interface that is easy to use and understand.
- **Automatic Setup**: Handles the downloading of necessary tools, so you don’t have to worry about missing files.

## Thanks

We'd like to express our gratitude to the developers of PyInstaller and `pyinstxtractor.py` for their valuable contributions to the community. Your hard work has made the extraction process much easier for everyone.

---

Thank you for using `exereverse`!
