DataSavingApp
Overview

DataSavingApp is an Android application designed to help users efficiently store and manage their data usage information in Google Sheets. This app is ideal for users who want to keep track of their mobile data consumption and save the information directly to Google Sheets for easy access and analysis.
Features

    Automatic Data Logging: Automatically log your daily, weekly, and monthly data usage and save it to a Google Sheet.
    Custom Data Entry: Manually enter data usage details for specific apps or time periods.
    Data Visualization: View your data usage trends with charts directly in Google Sheets.
    Google Sheets Integration: Seamless integration with Google Sheets to store and organize your data.
    Notifications: Receive notifications when new data entries are added or when you reach certain data usage thresholds.
    Data Backup: Automatically back up your data to Google Sheets, ensuring it is safe and accessible from any device.
    Export Options: Export your data to other formats (e.g., CSV) directly from Google Sheets for further analysis.

Installation

Prerequisites

    Android Studio: Version 4.0 or higher
    Google Account: Required for Google Sheets API access
    Google Sheets API: Enable Google Sheets API in your Google Cloud Console
    Steps

    Clone the Repository:


    git clone https://github.com/yourusername/datasavingapp.git

    Open in Android Studio:
        Launch Android Studio and select Open an existing project.
        Navigate to the cloned repository folder and select it.

    Configure Google Sheets API:
        Follow the Google Sheets API Quickstart Guide to enable the API and obtain your credentials.
        Place the credentials.json file in the app/src/main/res/raw/ directory.

    Sync Project with Gradle:
        Click Sync Now in Android Studio to ensure all dependencies are correctly installed.

    Build and Run:
        Connect your Android device or use an emulator.
        Click Run to build and install the app on your device.

Usage

    Sign in with Google:
        Open the app and sign in with your Google account to link it to Google Sheets.

    Track Data Usage:
        The app will automatically log your data usage and save it to the connected Google Sheet.

    View Data in Google Sheets:
        Open Google Sheets to view, analyze, and manage your data.

Contributing

Contributions are welcome! Please follow these steps:

    Fork the repository.
    Create a new branch (git checkout -b feature/YourFeature).
    Make your changes.
    Commit your changes (git commit -m 'Add Some Feature').
    Push to the branch (git push origin feature/YourFeature).
    Open a Pull Request.
