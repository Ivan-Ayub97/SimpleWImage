# SimpleWImage
This program is particularly useful for photographers, designers, and anyone who needs to keep their image files organized and well-labeled.

# SimpleWImage

## Description
SimpleWImage is a desktop application developed in Python, designed to efficiently rename and organize image files with a functional interface. It’s perfect for managing large image libraries or multimedia projects.

## Features
- **File Selection:** Select multiple image files (e.g., .png, .jpg, .jpeg, .bmp, .gif).
- **Preview:** View a preview of selected images to easily identify them.
- **Custom Renaming:** Add a prefix and a sequential number to file names.
- **Flexible Export:** Save renamed files to a user-selected folder.
- **Original File Preservation:** Option to keep the original files intact.
- **Progress Bar:** Display the progress of renaming and exporting processes.

## Application Structure
The program is composed of several key components:

1. **Main Interface (UI):** Built with PyQt5, this component handles user interactions, file selection, and process initiation. It includes buttons, input fields, and a preview area for selected images.

2. **File Handler:** This module manages file operations such as loading images, renaming them according to the user’s preferences, and exporting them to the designated folder.

3. **Image Previewer:** Uses PyQt5 widgets to display thumbnails of selected images, allowing users to confirm their selections visually.

4. **Progress Tracker:** Implements a progress bar to provide feedback on the renaming and exporting process, enhancing user experience.

5. **Error Handling:** Ensures smooth operation by catching and displaying errors, such as unsupported file formats or invalid file paths.

## How to Use
1. Run the application.
2. Select the image files you want to rename.
3. Enter a prefix for the new file names.
4. Choose the folder where the renamed files will be saved.
5. (Optional) Check the "Keep original files" option to preserve the original files.
6. Click on "Rename and Export Files" to start the process.
7. Monitor the progress and receive a notification upon completion.

### Example Use Case
Imagine you are a photographer with a folder of 500 images from a recent shoot. Using SimpleWImage, you can:
- Add a descriptive prefix such as "Wedding_2024_".
- Automatically number the files sequentially.
- Export the renamed files to a project-specific folder while keeping the originals intact.

## System Requirements
- Operating System: Windows
- Dependencies: Python 3.x, PyQt5

