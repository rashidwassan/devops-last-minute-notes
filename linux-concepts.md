# Linux Concepts and Keywords for DevOps

## General Concepts

 1 `Kernel`: The core part of Linux, responsible for managing the system’s resources and hardware.

 2 `Shell`: A command-line interpreter that allows users to interact with the operating system.

 3 `User Space`: Memory areas where all user mode applications run.

 4 `Filesystem Hierarchy`: The layout of directories and files on a Linux system, structured hierarchically.

 5 `Processes`: Instances of executing programs managed by the Linux kernel.

 6 `Daemons`: Background services that start up during the boot process or after logging into the desktop.

 7 `Package Manager`: Tools that automate the process of installing, upgrading, configuring, and removing software.

 8 `System Calls`: Interfaces that provide services of the kernel to the user applications.

 9 `Virtualization`: The creation of a virtual (rather than actual) version of something, such as an OS, a server, or network resources.

 10 `Containers`: Lightweight, executable software packages that include everything needed to run an application: code, runtime, libraries, and settings.

## Architecture Components

 11 `Bootloader`: Software that manages the boot process of a computer, such as GRUB.

 12 `Init System`: The first process started by the Linux kernel, responsible for controlling system startup and services (e.g., systemd, SysVinit).

 13 `System Libraries`: Code libraries used by the kernel to perform different operations.

 14 `GUI (Graphical User Interface)`: Graphical interfaces like GNOME or KDE that make interaction user-friendly.

 15 `CLI (Command Line Interface)`: Interface for typing commands on a terminal to interact with the system.

 16 `POSIX (Portable Operating System Interface)`: A family of standards specified by the IEEE for maintaining compatibility between operating systems.

 17 `IPC (Inter-Process Communication)`:A mechanism that allows processes to communicate and synchronize their actions.

 18 `Sysfs (Filesystem for Sysfs)`: A virtual filesystem used by Linux that provides a tree of system devices.

 19 `Procfs (Filesystem for Procfs)`: A virtual filesystem that provides detailed information about Linux processes.

 20 `Sockets`: Endpoints for sending and receiving data between processes over a network or within the same system.

## Components

 21 `BASH (Bourne Again SHell)`: A widely used default command shell in Linux.

 22 `Apache`: A popular web server software for Linux.

 23 `Nginx`: High-performance HTTP and reverse proxy server.

 24 `Systemd`: A system and service manager for Linux, providing parallelization capabilities.

 25 `LVM (Logical Volume Manager)`: A device mapper that provides logical volume management for the Linux kernel.

 26 `KVM (Kernel-based Virtual Machine)`: A virtualization module in the Linux kernel that allows the kernel to function as a hypervisor.

 27 `X Window System`: A windowing system for bitmap displays.

 28 `SELinux (Security Enhanced Linux)`: A security architecture integrated into the kernel that supports access control security policies.

 29 `iptables`: A user-space utility program that allows a system administrator to configure the IP packet filter rules of the Linux kernel firewall.

 30 `Cron`: A time-based job scheduler in Unix-like operating systems.

## Network Components

 31 `TCP/IP`: A set of networking protocols that allow communication over interconnected networks.

 32 `DHCP (Dynamic Host Configuration Protocol)`: A network management protocol used to dynamically assign IP addresses to devices on a network.

 33 `DNS (Domain Name System)`: A hierarchical decentralized naming system for computers, services, or other resources connected to the Internet or a private network.

 34 `SSH (Secure Shell)`: A cryptographic network protocol for operating network services securely over an unsecured network.

 35 `FTP (File Transfer Protocol)`: A standard network protocol used for the transfer of computer files between a client and server on a computer network.

 36 `HTTP/HTTPS`: Protocols used for transmitting web pages over the Internet.

 37 `Samba`: A free software re-implementation of the SMB networking protocol, which allows end users to access and use files, printers, and other commonly shared resources.

 38 `NFS (Network File System)`: A distributed file system protocol allowing a user on a client computer to access files over a network similar to how local storage is accessed.

 39 `VLAN (Virtual Local Area Network)`: A network protocol to create multiple distinct broadcast domains, which are mutually isolated.

 40 `SNMP (Simple Network Management Protocol)`: An Internet Standard protocol for collecting and organizing information about managed devices on IP networks.

 41 `IPsec (Internet Protocol Security)`: A protocol suite for securing Internet Protocol (IP) communications by authenticating and encrypting each IP packet of a communication session.

 42 `Firewall`: A network security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules.

 43 `Load Balancer`: A device that acts as a reverse proxy and distributes network or application traffic across a number of servers.

 44 `VPN (Virtual Private Network)`: Extends a private network across a public network, enabling users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network.

## System Administration

 45 `RAID (Redundant Array of Independent Disks)`: A data storage virtualization technology that combines multiple physical disk drive components into one or more logical units.

 46 `Monitoring Tools`: Tools that check the health and status of systems and networks (e.g., Nagios, Zabbix, Prometheus).

 47 `Backup and Recovery`: Strategies and solutions for data protection in case of data loss or system failure.

 48 `Log Management`: Processes and solutions for systematic collection, storage, analysis, and disposal of system logs.

 49 `Job Scheduling`: Use of cron or other tools to schedule scripts or commands to run at specific times.

 50 `User Management`: Handling user accounts including creating, modifying, and granting permissions.

 51 `Disk Management`: Managing disk space usage on systems through tools like `fdisk`, `parted`, and filesystem-specific commands.

 52 `Patch Management`: The process of updating security patches for software applications and technologies.

 53 `Automation Tools`: Tools designed to minimize manual interventions (e.g., Ansible, Puppet, Chef).

 54 `Security Auditing`: Checking system security settings and policies to ensure they meet the required security guidelines.

## Advanced Concepts

 55 `Cgroups (Control Groups)`: A Linux kernel feature to limit, account for, and isolate the resource usage (CPU, memory, disk I/O, etc.) of process groups.

 56 `Containerization`: Isolating applications within separate environments to enhance security and operational efficiency.

 57 `SELinux Contexts`: Security settings that define the permissions processes and files have within a system running Security-Enhanced Linux.

 58 `Inodes`: Data structures on a filesystem that store information about files and directories, except their names.

 59 `Soft and Hard Links`: Soft links (or symbolic links) refer to a symbolic path indicating the abstract location of another file, while hard links are direct references to the content of the files.

 60 `D-Bus`: A message bus system that provides a simple way for inter-process communication and allows multiple programs to interact.

 61 `Swap Space`: A form of virtual memory that a computer can use to support physical memory (RAM) on the system.

 62 `File Permissions`: Settings that control who can read, write, or execute files or directories.

 63 `Access Control Lists (ACLs)`: A more flexible permission mechanism for file systems that allows you to specify detailed user permissions for a file or directory.

 64 `Ext2/Ext3/Ext4`: Filesystems commonly used in Linux, where Ext4 is the most recent evolution providing various improvements over its predecessors.

 65 `XFS`: A high-performance 64-bit journaling file system created by Silicon Graphics, Inc.

 66 `Btrfs`: A modern file system developed to address the expanding scalability and reliability requirements of contemporary operating environments.

 67 `Journalling`: A process that helps protect the integrity of the filesystem by keeping a log of ongoing changes.

 68 `LUKS (Linux Unified Key Setup)`: A specification for disk encryption to secure data on devices using cryptographic techniques.

 69 `Logical Volume Manager (LVM)`: A device mapper framework that provides logical volume management for the Linux kernel.

 70 `RAID (Redundant Array of Independent Disks)`: A data storage virtualization technology that combines multiple physical disk drive components into one or more logical units for redundancy or performance improvement.

 71 `Root Account`: The default superuser account in Linux systems that has access to all commands and files.

 72 `Umask`: A command that determines the default file permission sets for newly created files and directories.

 73 `SSH Keys`: Cryptographic keys used for secure remote login using the SSH protocol.

 74 `TCP Wrappers`: Host-based Networking ACL system, used to filter network access to Internet protocol servers on (Unix-like) operating systems.

 75 `Environment Variables`: Variables that are defined in the shell and are available system-wide to influence the behavior of processes.

 76 `Cron Jobs`: Scheduled commands that use the cron daemon to execute scripts at specified times and intervals.

 77 `Syslog`: A standard for message logging, where messages are stored for dealing with system management and security auditing.

 78 `Network Interfaces`: Components that facilitate the connection between a computer and a network.

 79 `Kernel Modules`: Pieces of code that can be loaded and unloaded into the kernel upon demand, extending the functionality of the core system without rebooting.

 80 `Proc File System (/proc)`: A virtual filesystem in Linux that provides a mechanism for kernel-space to send information to user-space.

 81 `Uptime`: Command to find out how long the system has been running.

 82 `/etc/fstab`: A configuration file that contains information about the various partitions and storage devices in use.

 83 `Systemd Units`: Configuration files for systemd that manage the behavior of services, mount points, and other system components.

 84 `Grub Bootloader`: A program that loads the Linux kernel into the computer's main memory to begin its operations.

 85 `Kernelspace vs Userspace`: Distinct areas where the core system (kernel) and the user applications run, ensuring security and stability.

 86 `iptables/netfilter`: Tools that define rules for packet filtering and NAT to secure networks on Linux systems.

 87 `uname Command`: Command used to print system information including the Linux kernel version and hardware platform.

 88 `Shared Libraries`: Libraries that can be simultaneously used by multiple programs in Linux to save memory and enhance functionality.

 89 `Runlevels`: Predefined modes of operation in Unix-like systems that determine which programs can execute at startup.

 90 `Shell Scripting`: Writing scripts using shell commands to automate tasks.

 91 `GNU Tools`: Collection of tools developed by the GNU project including compilers, editors, and various utilities.

 92 `Namespaces`: Features of the Linux kernel that partition kernel resources such that one set of processes sees one set of resources while another set of processes sees a different set of resources.

