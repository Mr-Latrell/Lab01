# Lab01
First Lab Assignment

## Lab 01

- Name: Keonje Paige
- Email: paige.34@wright.edu

## Part 1 - GitHub Profile
[Mr-Latrell Profile](https://github.com/Mr-Latrell)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |help - This command displays the many available commands or detailed help information on a specified command.               |
| Get-Location| pwd    |Get-Location - This command is what helps show the location of you current path.|
| Get-ChildItem | ls    |Get-ChildItem - This command keeps track on all the items the device will have a certain location.
|mkdir   | mkdir       |mkdir - This command is what helps make folders and files|
| Set-Location | cd     |Set-Location - This commands functions like that of the cd(change directory) command, changing the location of terminal,folder, and file.        |
| New-Item | touch      |New-Item - This command is the Windows PowerShell equivalence of the touch command, meaning it creates files. |
| Move-Item | mv        |Move-Item - This is the command that helps relocate a file, folder, or registry key from one location to another.|
| Copy-Item | cp        |Copy-Item - This is the Windows Prompt used to copy file,folders,etc. to another location.|
| Remove-Item | rm      |Remove-Item - This the Windows Prompt PowerShell equivalence of the rm command, where it removes any previous files, folders, etc.        |
| notepad.exe | vim     |notepad.exe - This is the command to use to open a notepad file.
        |

Windows
All of the functions, scripts, and modules that reside in the system will shown.


## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

MY OS IS WINDOWS

My Command Line Shell is: 

MY COMMAND LINE SHELL IS WINDOWS POWERSHELL


### Navigating My OS on the Command Line

1. Create a directory named `DirA`:
mkdir DirA
2. Create a directory named `Dir B`:
mkdir "Dir B"
3. Go into `DirA`:
Set-Location DirA
4. Go into `Dir B` from `DirA`:
Set-Location "C:\Users\Je\Dir B"
5. Return to your user's home directory:
Set-Location "C:\Users\Je"
6. Create a file named `test.txt`:
 New-Item -Path "C:\Users\Je\test.txt" -ItemType File
7. Move the file named `test.txt` into `DirA`:
Move-Item -Path "C:\Users\Je\test.txt" -Destination "C:\Users\Je\DirA"
8. Contents of `test.txt`:
Get-Content "C:\Users\Je\DirA\test.txt"
```
Testing, Testing, One Two, One Two.
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`:
Copy-Item -Path "C:\Users\Je\DirA\test.txt" -Destination "C:\Users\Je\DirA\copy.txt"
10. View the contents of `DirA`: 
Get-ChildItem
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`:
Copy-Item -Path "C:\Users\Je\DirA\test.txt" -Destination "C:\Users\Je\Dir B\fodder.txt"
12. Delete / remove both `fodder.txt` AND `Dir B`:
Remove-Item -Path "C:\Users\Je\Dir B\fodder.txt"

## Citations

To add citations, provide the cite and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.



