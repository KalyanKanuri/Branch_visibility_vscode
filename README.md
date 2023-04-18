# PowerShell Profile with Git Status
This is a PowerShell profile that displays the current directory and Git branch in green, and shows any Git changes in yellow with symbols for each type of change.

## Installation
To use this profile, follow these steps:

> Open PowerShell as an administrator.
> Type notepad $profile and press Enter. This will create a new profile file or open the existing one in Notepad.
> Copy the code from the PowerShell profile file in this repository and paste it into your profile file.
> Save and close the profile file.
> Reload your profile by typing . $profile in the PowerShell console.

## Usage
After installing the profile, the PowerShell prompt will display the current directory and Git branch in green. If there are any Git changes, they will be displayed in yellow with symbols for each type of change. The available symbols are:

> 'M' for modified files
> 'A' for added files
> 'D' for deleted files
> 'R' for renamed files
> '?' for untracked files

You can also use the gs alias to run the Get-GitStatus function manually and display the Git status.

## License
This code is licensed under the Mozilla Public License 2.0. Feel free to use, modify, and distribute it as you like.