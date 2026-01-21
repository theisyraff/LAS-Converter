# LAS-Converter
A simple CLI code to extract Log ASCII Standard (.las) file into a readable Comma Separated Values (.csv) and Microsoft Excel (.xlsx) file.

Implementation Plan - LAS Converter CLI

The goal is to create a robust, user-friendly Command Line Interface (CLI) for converting LAS files to CSV and XLSX. We will provide executable wrapper scripts for both Windows (.bat) and macOS (.command) to make it easy to run.

las_converter.py: The main Python script.
requirements.txt: Dependencies list.
run_converter.bat: Windows launcher.
run_converter.command: macOS launcher.

Progress Verbosing: Implement a text-based progress indicator (e.g., "Step 1/3: Reading LAS file...").
Error Handling: Add try-except blocks with clear error messages and a input("Press Enter to exit...") at the end so the window doesn't close immediately on error.

Windows Batch File (run_converter.bat)
- Check if python is installed.
- Install requirements automatically (or check).
- Run the script.
- Pause at the end.

macOS Command File (run_converter.command)
- Set execute permissions (automatically via script if possible, usage instructions otherwise).
- cd to script directory.
- Check python3.
- Install requirements.
- Run the script.

Manual Verification
- Run las_converter.py with arguments.
- Run las_converter.py without arguments (interactive mode).
- Verify run_converter.bat logic (by inspection, as we are on Mac).
- Verify run_converter.command by running it.

Open for public usage, but please do not claim all the credits T_T
