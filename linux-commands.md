# Linux Command Reference

This document provides a reference to 100 commonly used Linux commands, ranging from basic to advanced. Each command is accompanied by a brief description and an example of its usage.

## ls
**Description:** List directory contents.


```bash
ls -l
```

## cd
**Description:** Change the current directory.


```bash
cd /home
```

## pwd
**Description:** Print working directory.


```bash
pwd
```

## mkdir
**Description:** Create a new directory.


```bash
mkdir new_directory
```

## rmdir
**Description:** Remove an empty directory.


```bash
rmdir empty_directory
```

## rm
**Description:** Remove files or directories.


```bash
rm file.txt
```

## cp
**Description:** Copy files or directories.


```bash
cp file.txt /backup
```

## mv
**Description:** Move or rename files or directories.


```bash
mv file.txt /new_location
```

## touch
**Description:** Change file timestamps. If the file does not exist, it is created empty.


```bash
touch new_file.txt
```

## chmod
**Description:** Change the permissions of files or directories.


```bash
chmod 755 script.sh
```

## chown
**Description:** Change the owner and group of files.


```bash
chown user:group file.txt
```

## find
**Description:** Search for files in a directory hierarchy.


```bash
find . -type f -name "*.txt"
```

## grep
**Description:** Print lines matching a pattern.


```bash
grep "search_string" file.txt
```

## sed
**Description:** Stream editor for filtering and transforming text.


```bash
sed -i 's/old/new/g' file.txt
```

## awk
**Description:** Pattern scanning and processing language.


```bash
awk '{print $1}' file.txt
```

## cat
**Description:** Concatenate and display files.


```bash
cat file.txt
```

## echo
**Description:** Display message on screen.


```bash
echo "Hello World"
```

## printf
**Description:** Format and print data.


```bash
printf "Hello %s\n" "World"
```

## head
**Description:** Output the first part of files.


```bash
head -n 5 file.txt
```

## tail
**Description:** Output the last part of files.


```bash
tail -n 5 file.txt
```

## less
**Description:** View and paginate file contents.


```bash
less file.txt
```

## more
**Description:** View file contents interactively.


```bash
more file.txt
```

## du
**Description:** Estimate file space usage.


```bash
du -sh /home/user
```

## df
**Description:** Report file system disk space usage.


```bash
df -h
```

## top
**Description:** Display Linux processes.


```bash
top
```

## ps
**Description:** Report a snapshot of the current processes.


```bash
ps aux
```

## kill
**Description:** Send a signal to a process.


```bash
kill -9 1234
```

## killall
**Description:** Kill processes by name.


```bash
killall process_name
```

## man
**Description:** Format and display the on-line manual pages.


```bash
man ls
```

## sudo
**Description:** Execute a command as another user.


```bash
sudo apt update
```

## apt-get
**Description:** APT package handling utility (Debian-based).


```bash
sudo apt-get install nginx
```

## yum
**Description:** Package manager for RPM-based distributions.


```bash
sudo yum install nginx
```

## dnf
**Description:** Federated package manager for RPM-based distributions.


```bash
sudo dnf install nginx
```

## tar
**Description:** Archive files.


```bash
tar -czvf archive.tar.gz /folder
```

## gzip
**Description:** Compress or expand files.


```bash
gzip file.txt
```

## bzip2
**Description:** A block-sorting file compressor.


```bash
bzip2 file.txt
```

## zip
**Description:** Package and compress (archive) files.


```bash
zip archive.zip file.txt
```

## unzip
**Description:** List, test, and extract compressed files in a ZIP archive.


```bash
unzip archive.zip
```

## ssh
**Description:** OpenSSH SSH client (remote login program).


```bash
ssh user@host
```

## scp
**Description:** Secure copy (remote file copy program).


```bash
scp file.txt user@host:/path
```

## wget
**Description:** Retrieve files from the web.


```bash
wget http://example.com/file
```

## curl
**Description:** Transfer data from or to a server.


```bash
curl -O http://example.com/file
```

## iptables
**Description:** Administration tool for IPv4/IPv6 packet filtering and NAT.


```bash
sudo iptables -L
```

## crontab
**Description:** Schedule periodic background work.


```bash
crontab -e
```

## systemctl
**Description:** Control the systemd system and service manager.


```bash
systemctl status nginx
```

## journalctl
**Description:** Query and display messages from the journal.


```bash
journalctl -u nginx
```

## vmstat
**Description:** Report virtual memory statistics.


```bash
vmstat 1 5
```

## iostat
**Description:** Report CPU statistics and I/O statistics for devices and partitions.


```bash
iostat
```

## netstat
**Description:** Networking statistics.


```bash
netstat -tuln
```

## ss
**Description:** Utility to investigate sockets.


```bash
ss -tuln
```

## ping
**Description:** Send ICMP ECHO_REQUEST to network hosts.


```bash
ping example.com
```

## traceroute
**Description:** Print the route packets trace to network host.


```bash
traceroute example.com
```

## nslookup
**Description:** Query Internet name servers interactively.


```bash
nslookup example.com
```

## dig
**Description:** DNS lookup.


```bash
dig example.com
```

## mount
**Description:** Mount a filesystem.


```bash
sudo mount /dev/sda1 /mnt
```

## umount
**Description:** Unmount file systems.


```bash
sudo umount /mnt
```

## fsck
**Description:** Check and repair a Linux filesystem.


```bash
sudo fsck /dev/sda1
```

## dd
**Description:** Convert and copy a file.


```bash
dd if=/dev/zero of=/dev/sda1
```

## alias
**Description:** Define or display aliases.


```bash
alias ll='ls -l'
```

## unalias
**Description:** Remove alias definitions.


```bash
unalias ll
```

## history
**Description:** Display or manipulate the history list.


```bash
history
```

## env
**Description:** Display, set, or remove environment variables.


```bash
env
```

## export
**Description:** Set export attribute for shell variables.


```bash
export PATH="/usr/local/bin:$PATH"
```

## unset
**Description:** Remove variable or function names.


```bash
unset TEMP
```

## which
**Description:** Locate a command.


```bash
which ls
```

## whereis
**Description:** Locate the binary, source, and manual page files for a command.


```bash
whereis ls
```

## who
**Description:** Show who is logged on.


```bash
who
```

## whoami
**Description:** Print the user name associated with the current effective user ID.


```bash
whoami
```

## uptime
**Description:** Tell how long the system has been running.


```bash
uptime
```

## hostname
**Description:** Show or set the system's host name.


```bash
hostname
```

## uname
**Description:** Print system information.


```bash
uname -a
```

## lsof
**Description:** List open files.


```bash
lsof -i
```

## nohup
**Description:** Run a command immune to hangups.


```bash
nohup ./script.sh &
```

## watch
**Description:** Execute a program periodically, showing output fullscreen.


```bash
watch -n 1 date
```

## strace
**Description:** Trace system calls and signals.


```bash
strace -c ls
```

## free
**Description:** Display memory usage.


```bash
free -h
```

