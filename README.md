# Google-Drive-Permission-Manager

Description:
This Python script helps manage Google Drive permissions efficiently by automating the process of identifying and removing non-company email addresses from a specified folder and its subfolders. Built using the Google Drive API, it recursively scans folders, lists non-company email addresses with permissions, and removes unwanted permissions while allowing exempted emails to remain.

The script is designed to be flexible and secure, making it an excellent tool for maintaining data access hygiene in shared Google Drive environments.

Features:
Authenticates with Google Drive using OAuth 2.0.
Recursively lists all files and folders within a target directory.
Identifies and lists non-company email addresses with access.
Removes unwanted permissions in bulk while allowing exemptions.
Batch processing for improved efficiency.
Includes delays to prevent Google Drive API rate-limiting.

Usage:
Clone the repository.
Set up your Google Drive API credentials (client_secret.json is required but should not be uploaded).
Run the script and provide the folder ID when prompted.
Manage permissions by specifying exempt email addresses or removing all non-company emails.

Requirements:
Python 3.x
Google Drive API enabled for your Google account.

Dependencies: Install them via pip install google-auth google-auth-oauthlib google-api-python-client.

Notes:
Be sure to exclude client_secret.json and token.pickle when uploading or sharing this script.
Replace @companydomain.com with your organization's email domain in the script before running.
