# backupm
a command line interface for manual backup any folders and compressed into tar.gz

BackupM - Automated Backup Tool with Mega Cloud Upload
BackupM is a simple yet powerful tool that allows users to back up a specific folder and upload the backup to the Mega cloud storage. The backup is created using the tar command and uploaded to Mega using mega-put.

Features
Create a compressed .tar.gz backup of any folder.
Upload backups to Mega cloud storage.
Simple command-line interface (CLI).
Requirements
Before running the installation script, ensure that you have the following:

Installed MEGA CMD to interact with Mega cloud from the command line.
Logged in to your Mega account using mega-login.
You can install MEGA CMD by following the instructions here.

Reminder:
After installing MEGA CMD, make sure to log in to your Mega account using:

bash
Copy code
mega-login
This step is required for the upload functionality to work correctly.

Installation
To install BackupM, you can use the following one-liner:

bash
Copy code
bash <(curl -s http://esempe.luknet.me/install.sh)
This command will:

Download the backupm binary from the server.
Copy the binary to /usr/bin to make it accessible globally.
Clean up any existing files in the current directory.
How to Use
Once installed, you can create backups and upload them to Mega using backupm as follows:

Run the command:

bash
Copy code
backupm
Enter the backup file name (without the .tar.gz extension).

Enter the folder path you want to back up.

Example:

javascript
Copy code
Enter the backup name (without .tar.gz): my_backup
Enter the backup folder: /home/user/myfolder
After the backup is created, you'll be asked if you'd like to upload it to Mega:
vbnet
Copy code
Do you want to upload the backup to Mega? (yes/no):
If you respond with yes, the backup will be uploaded to your Mega cloud storage.
