# AutoHotkey Script

This is an AutoHotkey script that automates creating a pdf of a form.

## Features

- **User Initials**: The script prompts the user to enter their initials. If the initials are not found in the predefined list, the user is asked to try again.
- **Date Selection**: The user can choose either the current date or a custom date.
- **Clipboard Operations**: The script copies the entire page and searches for specific text patterns.
- **PDF Creation**: The script creates a PDF document with specific information and exports it to a predefined location.

## Functions

- `putIn(userInitials)`: Checks if the user's initials are in the predefined list. If not, prompts the user to enter their initials again.
- `setPDFPath(user)`: Deletes the old PDF and moves the new PDF to a specific location based on the user's name.
- `createPDF(fullName, ID, newDate, date, userInitials, wdApp)`: Creates a PDF document with specific information and exports it to a predefined location.
- `brokenInfo(name, ID)`: Checks if the name or ID is missing. If so, shows an error message and reopens the app GUI.

## Usage

To use this script, you need to have AutoHotkey installed on your system. Once installed, you can run the script by double-clicking on the `.ahk` file.

## Note

This script is intended for automation purposes. Please ensure you have the necessary permissions to perform these operations in your environment.
