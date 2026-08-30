# LINUX-FUNDAMENTALS

LINUX FUNDAMENTALS (WEEK 1 FINAL ASSESSMENT)

# Task 1 Verify Current User
Commands :
whoami
id
groups
"Display the current user, User ID details, and group memberships."

# Task 2 Create Linux Lab Structure
Commands :
mkdir Linux-Lab
cd Linux-Lab
mkdir Files Scripts Logs Configs
ls
"Create and verify the Linux lab directory structure."

# Task 3 File Operations
Commands :
touch Files/linux.txt
touch Files/devops.txt
touch Scripts/deploy.sh
ls Files
ls Scripts
"Create and display the required files."

# Task 4 Copy and Rename Files
Commands :
cp Files/linux.txt Files/linux-backup.txt
mv Files/devops.txt Files/devops-notes.txt
ls Files
"Copy and rename files and verify the changes."

# Task 5 File Content Verification
Commands :
nano Files/linux.txt
nano Files/devops-notes.txt
cat Files/linux.txt
cat Files/devops-notes.txt
"Add text to files using Nano and verify the contents using cat."

# Task 6 Permissions Management
Commands :
chmod +x Scripts/deploy.sh
ls -l Scripts/deploy.sh

touch Configs/app.env
chmod 600 Configs/app.env
ls -l Configs/app.env
"Make the script executable and apply secure permissions to the configuration file."

# Task 7 Ownership Verification
Commands :
ls -l Scripts/deploy.sh
ls -l Configs/app.env
"Verify the owner and group ownership of the files."

# Task 8 Process Monitoring
Commands :
ps
top
"Display and monitor running processes."

# Task 9 Process Management
Commands :
sleep 300
ps aux | grep sleep
kill PID
ps aux | grep sleep
"Create a process, find its PID, terminate it, and verify that it is no longer running."

# Task 10 Service Management
Commands :
systemctl status ssh
systemctl status cron
"Check the status of SSH and Cron services."

# Task 11 Log Investigation
Commands :
journalctl -n 20
journalctl -u ssh
"View the latest system logs and SSH service logs."
