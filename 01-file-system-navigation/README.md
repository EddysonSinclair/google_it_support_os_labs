#PROJECT TITLE 

## LINUX FILE SYSTEM NAVIGATION and MANAGEMENT


# PROJECT OVERVIEW

This project aims at focusing and understanding the linux file system, using command line tools I was able to simulate what happens and is done usually by IT SUPPORT, System Admins. and System Admins.; This projects includes creating directories, organizing them, moving/renaming, copying and safely managing log files.
The goal of this lab is to gain more confidence and conversance working in the linux command line and also how files and directories are structred and managed in Linux

## LAB ENVIRONMENT

- Operating System: Ubuntu Linux (LTS)
- Virtualization Tool: VirtualBox
- Shell: Bash


## Tasks Performed

- Created a structured workspace to simulate a real system environment
- Navigated directories using Linux terminal commands
- Created and organized directories and files
- Simulated system log creation and backup
- Practiced copying, moving, renaming, and deleting files safely
- Inspected file permissions

## Commands & Explanations

# Creating directoties and files 
mkdir logs backups scripts users - mkdir is the command used to create directories and organize them
touch logs/system.log - touch command is used to create new files
 
# Viewing File Contents
cat logs/system.log - cat displays the content in a file one the screen, Administrators frequently use this command to inspect log files during
troubleshooting.

# Simulating Log Updates
echo "System started successfully" >> logs/system.log - echo outputs a text
echo "User login detected" >> logs/system.log - " >> " appends text to a file without overwriting existing content.
This simulates how services continuously write information to log files.

#Copying and Renaming Files
cp logs/system.log backups/ - "cp" copies files from one location to another.
mv backups/system.log backups/system_backup.log - "mv" moves or renames files.

#Deleting Files Safely
rm users/user_list.txt - "rm" removes files and directories

#Inspecting File Permissions
ls -l logs/system.log - "ls" is used to list contents in a file, including file ownerships and permissions
Understanding file permissions is essential for system security and access control.

