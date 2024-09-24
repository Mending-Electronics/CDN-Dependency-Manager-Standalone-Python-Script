# CDN Dependency Checker

## Overview
CDN Dependency Checker is a standalone Python script designed to scan your project directory for *.html, *.js, *.php, and *.py files, listing all CDN dependencies used. It generates a `packages.json` file similar to a Node.js project and queries common CDN APIs to fetch the latest versions of these packages. Users can easily update the CDN versions in their project files by clicking the patch button.

## Features
- Scans *.html, *.js, *.php, and *.py files for CDN dependencies.
- Generates a `packages.json` file with the listed dependencies.
- Fetches the latest versions of CDN packages from common APIs.
- Allows users to patch CDN versions with a simple click.

## Installation
1. Install Python 3.xx if you haven't already.
2. Download the script and place it in the root directory of your project.

## Usage
1. Run the script:
    ```bash
    python cdn_checker.py
    ```
2. (Hide process) Check each files in your project directory to list used CDN dependencies in each file. Requests the CDN APIs to get the latest versions of the packages, comparing them to the used CDN package versions. Generates a `packages.json`.
3. Review the listed CDN dependencies and their versions in a table.
4. Click the patch button to update the CDN versions in your project files.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or suggestions, please open an issue.
