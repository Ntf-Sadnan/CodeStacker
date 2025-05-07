# CodeStacker

Share your full code base with LLMs or for easy analysis. CodeStacker takes a `.zip` archive of your project, extracts and consolidates the content of relevant text files into a single, formatted `.txt` output, processed entirely in your browser.

## Features

*   Processes `.zip` files client-side.
*   Automatically filters out binary/image files, hidden files/folders, and common build/dependency directories.
*   Outputs file paths and content into a single, formatted text file.
*   Offers download and copy-to-clipboard options.

## How to Use
1.  Open `index.html` in your browser. (or just visit https://ntf-sadnan.github.io/CodeStacker)
2.  Upload your project's `.zip` file.
3.  Click "Process & Create Stack".
4.  Use the Download or Copy button for the output.

## What's Included/Ignored

Includes text-based code files. Skips binary files, images, hidden files/folders, and directories like `node_modules`, `.git`, `dist`, etc.

## Running Locally

Open the `index.html` file directly in any modern web browser. No server is required.


