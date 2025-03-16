# Desktop Cleaner Script

## Overview
This Python script organizes files in a specified folder by moving them into subfolders based on their file extensions. It helps keep your desktop or downloads folder tidy by categorizing files into relevant directories.

## Features
- Automatically detects file extensions and creates subfolders accordingly.
- Moves files into their respective subfolders based on their extensions.
- Ensures subfolders are created only if necessary.
- Provides console output for tracking moved files.

## Prerequisites
- Python 3.x installed on your system.
- The `os` and `shutil` Python modules (which are included in the standard library).

## Installation
1. Clone this repository or copy the script file to your local machine.
2. Ensure Python is installed by running:
   ```sh
   python --version
   ```

## Usage
1. Open the script file and modify the `folder_path` variable to the directory you want to clean (e.g., `C:/Users/USER/Downloads`).
2. Run the script:
   ```sh
   python script.py
   ```

## Instructions
1. Download or copy the script to your local system.
2. Open the script in a text editor (e.g., Notepad++, VS Code, or PyCharm).
3. Modify the `folder_path` variable to point to the directory you want to clean.
4. Save the script.
5. Open a command prompt or terminal.
6. Navigate to the folder where the script is located using:
   ```sh
   cd path/to/your/script
   ```
7. Run the script using:
   ```sh
   python script.py
   ```
8. Observe the output as files are moved into categorized subfolders.

## Script Explanation
- **`create_subfolder_if_needed(folder_path, subfolder_name)`**: Checks if a subfolder exists and creates one if needed.
- **`move_file_to_subfolder(file_path, subfolder_path)`**: Moves a file to its designated subfolder.
- **`clean_folder(folder_path)`**: Iterates through files in the specified folder, determines their extensions, and moves them accordingly.
- The script is executed when run directly using `if __name__ == "__main__":`.

## Example Output
```
Desktop Cleaner Script
Moved: document.pdf -> PDF Files/
Moved: image.png -> PNG Files/
Cleaning complete.
```

## Notes
- Ensure you have the necessary permissions to modify files in the specified folder.
- This script only moves files and does not delete anything.
- Works best for commonly used folders like `Downloads`, `Desktop`, etc.

## License
This project is licensed under the MIT License.

