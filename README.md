# CodeStacker

Share your full code base with LLMs or for easy analysis. CodeStacker takes a `.zip` archive of your project, extracts and consolidates the content of relevant text files into a single, formatted `.txt` output, processed entirely in your browser.

## Features

*   **Input:** Upload a project as a `.zip` file.
*   **Client-Side Processing:** Your code is processed locally in your browser for privacy and speed.
*   **Intelligent Filtering:** Automatically skips common ignored directories (`node_modules`, `.git`, build folders) and binary/image files.
*   **Formatted Output:** Combines included file paths and their content into a single, readable text file.
*   **Download & Copy:** Get the output as a `.txt` file or copy the content directly to your clipboard.

## How to Use

1.  Download or open the `index.html` file in your web browser.
2.  Click the file upload area (or drag and drop) to select your project's `.zip` archive.
3.  Click "Process & Create Stack".
4.  Once complete, use the "Download" or "Copy" buttons to get your bundled code.

## What Gets Included / Ignored?

CodeStacker aims to include only relevant text-based code files. It skips:

*   Directories themselves (only files within are processed).
*   Common binary files (like `.exe`, `.dll`, `.pdf`).
*   Image files (like `.jpg`, `.png`, `.svg`).
*   Hidden files and directories (starting with `.`, e.g., `.git`, `.vscode`, `.env`).
*   Common dependency/build folders (`node_modules`, `vendor`, `dist`, `build`, `__pycache__`, etc.).
*   Files that appear to be binary based on a simple content check.

The output format is typically the file path followed by the file content, enclosed in code block-like delimiters.

## Running Locally

This project is a single HTML file. Simply download the `index.html` file and open it directly with any modern web browser. No installation or server is required.

## Credits

Created by [Ntf Sadnan](https://github.com/ntf-sadnan).

## License

This project is licensed under the MIT License.
