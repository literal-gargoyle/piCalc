# 1 Million Digits of Pi Calculator

![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)

This project calculates Pi to 1 million decimal places using Python's `mpmath` library and saves the result in a Microsoft Word document. It is designed to be user-friendly, automatically installs dependencies, and provides a progress bar for better user experience.

## This Project was made for my book
The book is releasing on amazon soon!

---

## Features
- **High-Precision Calculation**: Computes Pi to 1 million digits using the `mpmath` library.
- **Automatic Dependency Management**: Automatically installs required Python packages (`mpmath`, `python-docx`, and `tqdm`) if they are not already installed.
- **Cross-Platform Console Clearing**: Clears the console for a clean output, compatible with Windows, Linux, and macOS.
- **Progress Bar**: Displays a progress bar using the `tqdm` library to simulate the calculation process.
- **Output File**: Saves the calculated digits of Pi in a `.docx` file named `Pi_to_1_Million_Digits.docx` in the folder where the script is executed.

---

## Requirements
- Python 3.x
- Internet connection (for installing dependencies)

---

## Installation
1. Clone this repository or download the script.
2. Ensure you have Python 3.x installed on your system.
3. Run the script directly; it will handle dependency installation automatically.

---

## Usage
1. Run the script:
   ```bash
   python piCalc.py
