File Organizer
A simple Node.js script to organize files in a directory based on their types.

Usage
Make sure you have Node.js installed on your system.

Clone or download this repository.

Open a terminal and navigate to the project directory.

Run the script using the following format:

bash
Copy code
node main.js <command> [directoryPath]
Replace <command> with one of the available commands and [directoryPath] with the path to the directory you want to organize.

Available Commands
1. tree
Use this command to display the directory structure of a specified directory.

bash
Copy code
node main.js tree [directoryPath]
If no directory path is provided, it will default to the current working directory.

2. organize
Use this command to organize files in a specified directory into categories based on their file extensions.

bash
Copy code
node main.js organize [directoryPath]
If no directory path is provided, it will default to the current working directory.

3. help
Use this command to display a list of available commands and their descriptions.

bash
Copy code
node main.js help
File Categories
The script organizes files into the following categories based on their extensions:

Media: mp4, mkv
Archives: zip, 7z, rar, tar, gz, ar, iso, xz
Documents: docx, doc, pdf, xlsx, xls, odt, ods, odp, odg, odf, txt, ps, tex
Applications: exe, dmg, pkg, deb
Files with extensions not listed in the above categories will be placed in an "others" folder.

Example
Here's an example of how to use the script to organize files:

bash
Copy code
node main.js organize /path/to/directory
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
This project is a simple file organization script created with Node.js.