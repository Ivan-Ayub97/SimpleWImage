# SimpleWImage
Developed by Iván Ayub

SimpleWImage is an innovative desktop application tailored for photographers, designers, and multimedia enthusiasts who need a reliable tool to organize and label their image files efficiently. With its powerful features and user-friendly interface, SimpleWImage simplifies the process of managing extensive image libraries.

---

## Download
[Click here to download the EXE application (.zip)](https://drive.google.com/file/d/1u3Y3rU6pkpwbS9q2k5lGKh2Hi6l1v5IQ/view?usp=sharing)

For inquiries or feedback, contact me at: [sellocasadenubes@gmail.com](mailto:sellocasadenubes@gmail.com).

![SimpleWImage Icon](SimpleWImage.png)

---

## Description
SimpleWImage is built in Python and designed with practicality in mind. It provides a robust solution for batch-renaming and organizing image files, ensuring a smooth workflow for professionals and casual users alike.

---

## Features
- **Batch File Selection:** Quickly import multiple image files in formats such as .png, .jpg, .jpeg, .bmp, and .gif.
- **Thumbnail Previews:** Easily identify and confirm selected images with visual previews.
- **Customizable Renaming Options:** Add prefixes and sequential numbering to file names.
- **Flexible Export Options:** Save renamed files to a designated output folder.
- **File Integrity:** Optionally retain the original files for backup or reference.
- **Real-Time Feedback:** Keep track of progress using an integrated progress bar.
- **Error Handling:** Smooth operation through detailed error messages for unsupported formats or file path issues.
- **Multi-Threading Support:** Speeds up the renaming process by utilizing multiple CPU threads for efficiency.

---

## How to Use
1. Launch the application.
2. Drag and drop or manually select image files for renaming.
3. Enter a custom prefix for the new file names.
4. Choose an output folder for renamed files.
5. (Optional) Enable "Keep original files" to preserve existing files.
6. Click "Rename and Export Files" to start the process.
7. View progress in real-time and receive a completion notification.

### Example Scenario
Imagine managing a project folder with hundreds of images from a product photoshoot. SimpleWImage lets you:
- Add a prefix like "Product_2024_" to maintain consistency.
- Sequentially number files (e.g., "Product_2024_001.jpg").
- Export renamed files to a specified directory while keeping originals intact for further edits.

---

## Application Structure
### User Interface (UI)
Developed using PyQt5, the UI provides a streamlined experience with intuitive controls, including:
- File selection panel.
- Preview window.
- Input fields for custom renaming.
- Progress bar for process updates.

### Core Modules
1. **File Handler:** Responsible for image loading, renaming, and exporting.
2. **Preview Manager:** Generates and displays thumbnails of selected files.
3. **Error Handler:** Displays detailed error messages for invalid operations.
4. **Performance Engine:** Optimized for handling large datasets without compromising speed or reliability.
---

## System Requirements
- **Operating System:** Windows 7 or later
- **Dependencies:**
  - Python 3.x
  - PyQt5
  - PIL (Python Imaging Library)

---

## Captures
![Application Screenshot](SS.png)

---

## Development & Contribution
### Credits
This software utilizes the following libraries:
- **PyQt5**: [PyQt5](https://pypi.org/project/PyQt5/) for creating the graphical user interface, providing widgets and layout management.
- **PIL (Python Imaging Library)**: For handling image loading and processing.
- **sys**: Provides access to system-specific parameters and functions.
- **os**: Standard library for interacting with the operating system.
- **base64**: Handles encoding and decoding of data in base64 format.

Special thanks to the developers of these libraries for their contributions to the open-source community.

### Contributions
We welcome contributions! To contribute:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

Enjoy using SimpleWImage! Your feedback is invaluable and helps us improve continuously.
