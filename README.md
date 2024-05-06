# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

## Developed by: MOHAMED AAKIF ASRAR S
## Register number: 212223240088
 
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

![WhatsApp Image 2024-05-06 at 19 26 38_b24962a4](https://github.com/MOHAMEDAAKIFASRAR/Windows-basic-commands-batchscript/assets/148514683/9099d2a2-6793-4932-9ea0-439038b3cf85)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.cd %userprofile%\Desktop\MyLab

![WhatsApp Image 2024-05-06 at 19 27 08_e2b6fa5f](https://github.com/MOHAMEDAAKIFASRAR/Windows-basic-commands-batchscript/assets/148514683/cfdf682a-f752-4197-b9f5-b76e70608c81)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.dir %userprofile%
 \Desktop\MyLab
![WhatsApp Image 2024-05-06 at 19 27 29_8272ae6e](https://github.com/MOHAMEDAAKIFASRAR/Windows-basic-commands-batchscript/assets/148514683/5c953a3d-bd8d-41cd-8003-1c96937c1ecf)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%
 \Desktop\Backup mkdir %userprofile%\Desktop\Backup

![WhatsApp Image 2024-05-06 at 19 27 48_28ad6754](https://github.com/MOHAMEDAAKIFASRAR/Windows-basic-commands-batchscript/assets/148514683/2f37def6-c6c2-43f2-a513-c1773b3a801d)

## COMMAND AND OUTPUT
 mv Myfile.txt %userprofile%\Documents
 
![WhatsApp Image 2024-05-06 at 19 28 05_e53f4025](https://github.com/MOHAMEDAAKIFASRAR/Windows-basic-commands-batchscript/assets/148514683/824199bd-0fa2-4db9-b2b4-78d2d9dd7f69)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%
 \Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed
 successfully!





## OUTPUT


![WhatsApp Image 2024-05-06 at 19 28 22_051f0046](https://github.com/MOHAMEDAAKIFASRAR/Windows-basic-commands-batchscript/assets/148514683/811d3f82-49dd-4e22-a738-88483f038f9e)



# RESULT:
The commands/batch files are executed successfully.

