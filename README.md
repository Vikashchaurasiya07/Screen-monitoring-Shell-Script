System Monitoring Script

Description

This script monitors system resources (CPU, memory, disk usage) and network connectivity, sending alerts when thresholds are exceeded.

Usage

1. Save this script to a file (e.g., system_monitor.sh)
2. Make the script executable with chmod +x system_monitor.sh
3. Run the script manually or schedule it with cron to run at regular intervals

Configuration

- Adjust the thresholds in the script to suit your needs:
    - CPU_THRESHOLD
    - MEM_THRESHOLD
    - DISK_THRESHOLD
- Add more checks or customize the script as needed

Requirements

- Bash shell (version 4 or higher)
- top, free, df, ping commands installed


Author

vikash chaurasiya
Version

1.0

Changelog

- Initial release
