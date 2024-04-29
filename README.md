# Ex08-Windows-basic-commands-batchscript
### Tarunika.D (212223040227)
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
```
NAME:Tarunika.D
REG.NO:212223040227
```
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/tarunikadamodaran/Windows-basic-commands-batchscript/assets/145633268/e688f447-0ab1-4592-a4bf-e6f44f6c9b60)




## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/tarunikadamodaran/Windows-basic-commands-batchscript/assets/145633268/b342cb16-a332-49cd-a37d-7fb1610c57b2)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab

![image](https://github.com/tarunikadamodaran/Windows-basic-commands-batchscript/assets/145633268/34196785-ac98-4f58-87fa-3c4a297ff30d)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup

![image](https://github.com/tarunikadamodaran/Windows-basic-commands-batchscript/assets/145633268/305bcb77-9a6d-4d6b-a751-7b7f32a8ad68)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![image](https://github.com/tarunikadamodaran/Windows-basic-commands-batchscript/assets/145633268/c84b8df2-c895-4563-8b60-6ed3ee1c9dd8)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT
![image](https://github.com/tarunikadamodaran/Windows-basic-commands-batchscript/assets/145633268/072ab415-edaf-4de0-ae7b-3b1155d48d2e)






# RESULT:
The commands/batch files are executed successfully.

