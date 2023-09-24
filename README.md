# user-management-script
Simple script for user management 
## Overview

This User Management Script is a Bash script designed to simplfy user account management on a Linux system. It provides a user-friendly interface for creating and deleting user accounts, allowing system administrators to perform common user management tasks more efficiently. The script also include error hadnling to ensure smooth operation.

## Features

**Create User**: Easily create a new user account. The script checks for existing username to prevent duplicates.
**Change Password**: Quickly change a user's password, ensuring account security.
**Add Supplementary Group**: Choose to add a supplementary group to a user during account creation.
**Delete User**: Safely delete user accounts, including their home directories, while verifying the existence of the user.
**List User Accounts**: Display a list of all user accounts on the system.
**User-Friendly Menu**: A clear and interactive menu guides you through user management options.

## Prerequisites

- A Linux system (tested on RHEL 9).
- Administrative privileges (for user management commands like 'useradd', 'userdel', 'passwd', 'usermod', and 'getent').

## Usage
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/abadibusraa/user-management-script.git
