Project Structure:
.
├── maintenance.sh        # Main interactive menu
├── backup.sh             # Creates compressed backups of important files
├── update_cleanup.sh     # Updates and cleans the system
├── log_monitor.sh        # Scans system logs for errors
└── alerts.log            # Stores detected error logs

Features :
Backup Automation:
Compresses and saves files from a source directory into timestamped archives.
System Update & Cleanup:
Automatically updates system packages and removes unnecessary dependencies.
Log Monitoring:
Scans /var/log/syslog for errors, warnings, or critical issues, and logs them to alerts.log.
Interactive Menu:
A user-friendly CLI interface to access all maintenance tools in one place.

Project Description:
The System Maintenance Suite is a Bash-based automation tool designed to simplify routine system administration tasks on Linux.
It provides an interactive command-line interface that allows users to perform backups, update and clean the system, and monitor logs
for errors efficiently.
The suite includes modular scripts — backup.sh, update_cleanup.sh, and log_monitor.sh — which can also run independently.
It automates essential maintenance operations, saves time, and helps ensure system stability through regular updates and error detection.
