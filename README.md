# Get-PID-Script

The script checks if the PID in interest is running.
how it works:
- The user is prompted to insert the PID.
- The script is automatically added to the crontab and will run every minute.
- in case the PID fails, a text file is generated at the home directory with the PID as its name.
