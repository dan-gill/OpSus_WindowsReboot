# OpSus_WindowsReboot

Takes a CSV file as input. Use a hypervisor to connect to Windows machines. Store Windows services details, issue
power-off command, wait until all systems are powered off, start systems based on priority from CSV, and ensure
services are back to their original state before moving to the next system.
