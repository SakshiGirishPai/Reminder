# Reminder 
## Notification App
A simple Python script that utilizes the `plyer` library to display recurring desktop notifications. This script serves as a reminder to drink water at regular intervals.

## Features:
- Displays desktop notifications with the title "Reminder" and the message "Drink water."
- Uses the `plyer` library for cross-platform notification support.
- The script runs in an infinite loop, sending reminders at fixed intervals.
- The notification includes a custom app icon for visual identification.

## Dependencies:
- `time`: Standard Python library for handling time-related functions.
- `plyer`: Cross-platform library for accessing features commonly found on various operating systems.

## Usage:
1. Install the required libraries: `pip install plyer`.
2. Adjust the file path in the `app_icon` parameter to point to your custom icon (replace ".vscode\python.py\project1\project_reminder\icon.ico" with the actual path).
3. Run the script, and it will display recurring reminders to drink water at 10-second intervals (adjustable by changing the `timeout` parameter).

Feel free to customize the script for different reminder messages, time intervals, or additional features!
