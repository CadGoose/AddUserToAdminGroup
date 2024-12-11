# AddUserToAdminGroup

A script to add a local user to the administrators group, ensuring it runs with administrator privileges.

## Description

This script is designed to add a specified local user to the administrators group on a Windows machine. It ensures that the script runs with administrator privileges by relaunching itself with predefined credentials if necessary.

## Prerequisites

- Windows operating system
- Administrator credentials

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/AddUserToAdminGroup.git
   cd AddUserToAdminGroup

## Edit the Script
1. Open AddUserToAdminGroup.au3 in a text editor.
2. Replace ENTER ADMIN USERNAME and ENTER ADMIN PASSWORD with the actual administrator username and password.

## Run the Script
Execute the script using an AutoIt interpreter or compile it to an executable.

## Script Details
The script performs the following steps:

1. Check for Administrator Privileges:
If the script is not running as an administrator, it relaunches itself with the provided administrator credentials.

2. Prompt for User Account:
Prompts the user to enter the username of the account to be added to the administrators group.

3. Add User to Administrators Group:
Uses the net localgroup command to add the specified user to the local administrators group.

4. Confirm Success:
Displays a message indicating whether the user was successfully added to the administrators group.

5. Optional Restart:
Prompts the user to restart the computer immediately or later.
