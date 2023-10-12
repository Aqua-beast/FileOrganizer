# File Organizer

A simple Node.js script to organize files in a directory based on their types.

## Usage

1. Make sure you have Node.js installed on your system.

2. Clone or download this repository.

3. Open a terminal and navigate to the project directory.

4. Run the script using the following format:

```bash
node index.js <command> [directoryPath]
```
Replace <command> with one of the available commands and [directoryPath] with the path to the directory you want to organize.

## Available Commands

### 1. tree
Use this command to display the directory structure of a specified directory.
```bash
node index.js tree [directoryPath]
```
If no directory path is provided, it will default to the current working directory.

### 2. organize
Use this command to organize files in a specified directory into categories based on their file extensions.
```bash
node index.js organize [directoryPath]
```
If no directory path is provided, it will default to the current working directory.

### 3. help 
Use this command to display a list of available commands and their descriptions.
```bash
node index.js help
```

## File Categories

The script organizes files into the following categories based on their extensions:

- **Media**: mp4, mkv
- **Archives**: zip, 7z, rar, tar, gz, ar, iso, xz
- **Documents**: docx, doc, pdf, xlsx, xls, odt, ods, odp, odg, odf, txt, ps, tex
- **Applications**: exe, dmg, pkg, deb

Files with extensions not listed in the above categories will be placed in an "others" folder.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

This project is a simple file organization script created with Node.js.

