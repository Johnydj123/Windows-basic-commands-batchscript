# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.mkdir %userprofile%\Desktop\MyLab



![WhatsApp Image 2024-05-05 at 21 27 17_8aea56f8](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/d6fb107f-4dd7-4997-80e5-bcf69e0a8432)

## COMMAND AND OUTPUT:

List the contents of the "MyLab" directory.cd %userprofile%\Desktop\MyLab

![WhatsApp Image 2024-05-05 at 21 37 01_3235c7ad](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/8ce53bb3-8b41-43eb-9f28-00f77fe12df2)

![WhatsApp Image 2024-05-05 at 21 37 02_be89a00d](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/155427d0-a303-4299-9efb-3eb182320d2e)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.dir %userprofile%\Desktop\MyLab

![WhatsApp Image 2024-05-05 at 21 39 09_c0927837](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/02be4fa2-fc35-451c-90b2-6b8f73af2dbd)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![WhatsApp Image 2024-05-05 at 21 41 13_eec2cecc](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/6b89e45d-1cbc-4d1e-a427-c922de315285)

![WhatsApp Image 2024-05-05 at 21 41 14_274ce04f](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/72aac777-8dc5-4a78-9a35-34d996264586)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![WhatsApp Image 2024-05-05 at 21 44 19_25eb0b93](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/07347f71-4933-4bad-9666-b20e01f97523)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


```
@echo off mkdir
%userprofile%\Desktop\DocBackup copy 
%userprofile%\Documents*.docx
%userprofile%\Desktop\DocBackup echo
Backup completed successfully!`
```



## OUTPUT


![WhatsApp Image 2024-05-05 at 21 44 20_9ea5b511](https://github.com/Johnydj123/Windows-basic-commands-batchscript/assets/145953459/cecc2996-2aeb-426c-9725-82bfb3f2ee6e)



# RESULT:
The commands/batch files are executed successfully.

