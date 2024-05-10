# Windows-basic-commands-batchscript
# Ex08-Windows-basic-commands-batchscript

## Developed by : NANDHIKA P
## Register no : 212223040125

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

%userprofile%\Desktop\MyLab

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/2cd8eac5-ea01-436a-9a7b-8f6a73934af6)

## COMMAND AND OUTPUT
List the contents of the "MyLab" directory.

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/95aa5c63-ee88-4ba0-af19-70821f29ed69)

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/41805cfa-8819-4404-87f0-2a4aca85aa51)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/cef36ed7-1cf4-4071-9ced-86e2e61c847a)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

copy MyFile.txt %userprofile%\Desktop\Backup

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/cb14981c-124d-44ce-bdcf-ed92a24e7e86)

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/7a6a417d-0080-4441-abef-562ad4f5b988)

## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/9dc4b123-ce3d-4230-b6ce-53781ffe46ec)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the 
"Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```
## OUTPUT

![image](https://github.com/Nandhika05/Windows-basic-commands-batchscript/assets/154419402/d5ffe1dd-7e31-4e42-aae2-b660ee98f08d)


# RESULT:
The commands/batch files are executed successfully.

