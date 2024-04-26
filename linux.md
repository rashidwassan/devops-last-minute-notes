# 100 Linux Commands

## Basic Commands
1. `ls`: List files and directories.
2. `cd`: Change directory.
3. `pwd`: Print working directory.
4. `mkdir`: Make directory.
5. `touch`: Create an empty file.
6. `cp`: Copy files or directories.
7. `mv`: Move or rename files or directories.
8. `rm`: Remove files or directories.
9. `cat`: Concatenate and display file content.
10. `less`: Display file content one screen at a time.
11. `head`: Display the first part of a file.
12. `tail`: Display the last part of a file.
13. `grep`: Search for patterns in files.
14. `wc`: Count lines, words, and characters in a file.
15. `chmod`: Change file permissions.
16. `chown`: Change file owner and group.
17. `chgrp`: Change group ownership of a file.
18. `ln`: Create hard or symbolic links.
19. `find`: Search for files and directories.
20. `locate`: Find files by name.
21. `file`: Determine file type.
22. `du`: Display disk usage of files and directories.
23. `df`: Display disk space usage.
24. `mkdir -p`: Create parent directories if they do not exist.
25. `rmdir`: Remove empty directories.
26. `tar`: Archive files.
27. `gzip`: Compress files.
28. `gunzip`: Decompress files.

## File System Commands
29. `mount`: Mount a filesystem.
30. `umount`: Unmount a filesystem.
31. `blkid`: Print block device attributes.
32. `fsck`: Check and repair filesystems.
33. `mkfs`: Create a filesystem.
34. `fdisk`: Manipulate disk partition table.
35. `parted`: Create and manipulate disk partitions.
36. `lsblk`: List block devices.
37. `df -h`: Display disk space usage in human-readable format.
38. `du -h`: Display disk usage in human-readable format.

## Process Management Commands
39. `ps`: Display running processes.
40. `top`: Display dynamic real-time view of running processes.
41. `kill`: Terminate a process.
42. `killall`: Terminate processes by name.
43. `pkill`: Signal processes based on name and other attributes.
44. `pgrep`: List processes based on name and other attributes.
45. `nice`: Run a command with modified scheduling priority.
46. `renice`: Change priority of running processes.
47. `htop`: Interactive process viewer.

## User Management Commands
48. `useradd`: Add a user.
49. `userdel`: Delete a user.
50. `passwd`: Change user password.
51. `su`: Switch user.
52. `sudo`: Execute command as another user (typically root).
53. `chsh`: Change login shell.

## Network Commands
54. `ifconfig`: Display network interface configuration (deprecated, use 'ip' command).
55. `ip`: Show/manipulate routing, devices, policy routing, and tunnels.
56. `ping`: Send ICMP echo requests to network hosts.
57. `traceroute`: Print the route packets trace to network host.
58. `netstat`: Display network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.
59. `nslookup`: Query Internet name servers interactively.
60. `dig`: DNS lookup utility.
61. `host`: DNS lookup utility.
62. `hostname`: Print or set system hostname.
63. `ss`: Utility to investigate sockets.

## System Information Commands
64. `uname`: Display system information.
65. `lsb_release`: Display Linux Standard Base information.
66. `uptime`: Display system uptime.
67. `who`: Display users who are currently logged in.
68. `w`: Display who is logged in and what they are doing.
69. `last`: Display listing of last logged in users.
70. `ps aux`: Display all processes.
71. `free`: Display amount of free and used memory in the system.
72. `df -h`: Display disk space usage in human-readable format.
73. `du -h`: Display disk usage in human-readable format.
74. `lscpu`: Display CPU information.
75. `lsusb`: Display USB devices information.
76. `lsblk`: List block devices.

## System Control Commands
77. `shutdown`: Shutdown or restart the system.
78. `reboot`: Reboot the system.
79. `poweroff`: Power off the system.
80. `halt`: Halt the system.
81. `init`: System and service manager (deprecated in favor of systemd).
82. `systemctl`: Control the systemd system and service manager.
83. `service`: Run a System V init script.
84. `chkconfig`: Update and query runlevel information for system services.
85. `journalctl`: Query the systemd journal.

## Text Processing Commands
86. `sed`: Stream editor for filtering and transforming text.
87. `awk`: Pattern scanning and text processing language.
88. `cut`: Remove sections from each line of files.
89. `sort`: Sort lines of text files.
90. `uniq`: Report or omit repeated lines.
91. `wc`: Print newline, word, and byte counts for each file.
92. `tr`: Translate or delete characters.
93. `tee`: Read from standard input and write to standard output and files.
94. `paste`: Merge lines of files.
95. `grep`: Search for patterns in files.

## Archive and Compression Commands
96. `tar`: Archive files.
97. `gzip`: Compress files.
98. `gunzip`: Decompress files.
99. `zip`: Package and compress files.
100. `unzip`: Extract files from a zip archive.

