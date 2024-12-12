# Password Strength Checker - PowerShell Script  

This repository contains a PowerShell script that evaluates the strength of a password based on specific security criteria. The script provides feedback and suggestions to help users create stronger and more secure passwords.  

## Features  
- Checks password strength based on the following criteria:  
  - Minimum length (at least 8 characters).  
  - Presence of uppercase letters (A-Z).  
  - Presence of lowercase letters (a-z).  
  - Presence of digits (0-9).  
  - Presence of special characters (!@#$%^&*, etc.).  
- Outputs results for each criterion, highlighting strengths and weaknesses.  
- Provides suggestions for improving the password if weaknesses are detected.  

## Getting Started  

### Prerequisites  
- PowerShell (version 5.1 or later is recommended).  

### Installation  
1. Clone or download this repository to your local machine.  
2. Save the script file (`Check-PasswordStrength.ps1`) to a directory of your choice.  

### Usage  
1. Open PowerShell.  
2. Navigate to the directory where the script is saved using the `cd` command:  
   ```powershell
   cd path\to\your\script
