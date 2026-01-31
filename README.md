Below is your **complete content converted into a clean, well-structured Markdown (`.md`) format**, ready to save directly as:

```
mastering-linux-commands.md
```

You can copy everything below into a file with that name.

---

````md
# Mastering Linux Commands: A Comprehensive Guide

---

## Chapter 1: Navigating the Filesystem

### 1. Print Working Directory (`pwd`)

Shows the full path of the current directory.

```bash
pwd
````

---

### 2. Change Directory (`cd`)

```bash
cd /home/user/Documents
cd ..
```

---

### 3. List Directory Contents (`ls`)

```bash
ls
ls -la
```

---

## Chapter 2: Getting Help

### 4. Manual Pages

```bash
man ls
```

### 5. Locate Command Path

```bash
which python
```

---

## Chapter 3: Managing Files and Directories

### 6. Create Directory

```bash
mkdir new_folder
```

### 7. Remove Empty Directory

```bash
rmdir old_folder
```

### 8. Remove File

```bash
rm file.txt
rm -i file.txt
```

### 9. Copy Files

```bash
cp file.txt /home/user/backup/
cp -r folder1 folder2
```

### 10. Move / Rename

```bash
mv file.txt Documents/
mv old.txt new.txt
```

### 11. Create File

```bash
touch newfile.txt
```

---

## Chapter 4: Viewing Files

### 12. Display File

```bash
cat file.txt
```

### 13. Print Text

```bash
echo "Hello World"
```

### 14. Identify File Type

```bash
file image.png
```

### 15. Redirect Output

```bash
cat file.txt > output.txt
```

### 16. Pipes

```bash
ls | grep txt
```

---

## Chapter 5: Searching

### 17. Locate

```bash
locate filename.txt
```

### 18. Find

```bash
find /home/user -name filename.txt
```

### 19. Grep

```bash
grep "word" file.txt
grep -r "word" /home
```

### 20. Update Locate Database

```bash
sudo updatedb
```

---

## Chapter 6: File Viewing Tools

### Head

```bash
head file.txt
head -n 20 file.txt
```

### Tail

```bash
tail file.txt
tail -f file.txt
```

### Line Count

```bash
wc -l file.txt
```

### More / Less

```bash
more file.txt
less file.txt
```

---

## Chapter 7: Text Editors

### Nano

```bash
nano file.txt
```

Shortcuts:

* Ctrl+O → Save
* Ctrl+X → Exit

### Vim

```bash
vim file.txt
```

Commands:

* i → Insert
* :wq → Save & Exit
* :q! → Exit without save

---

## Chapter 8: Archiving

### Tar

```bash
tar -cvf archive.tar files/
tar -xvf archive.tar
tar -czvf archive.tar.gz files/
```

### Gzip

```bash
gzip file.txt
gunzip file.txt.gz
```

### Bzip2

```bash
bzip2 file.txt
bunzip2 file.txt.bz2
```

---

## Chapter 9: System Information

### Disk

```bash
df -h
```

### Memory

```bash
free -h
```

### Kernel Info

```bash
uname -a
```

### Processes

```bash
top
htop
```

### Kill Process

```bash
kill PID
kill -9 PID
```

---

## Chapter 10: Permissions

### Chmod

```bash
chmod 755 script.sh
```

### Chown

```bash
chown user file.txt
chown user:group file.txt
```

### Chgrp

```bash
chgrp group file.txt
```

---

## Chapter 11: Networking

### IP Address

```bash
ip a
```

### Ping

```bash
ping google.com
```

### Download

```bash
wget https://example.com/file.zip
```

### SSH

```bash
ssh user@host
```

### SCP

```bash
scp file.txt user@host:/path/
```

### Netstat

```bash
netstat -tuln
```

---

## Chapter 12: Package Management

### Update

```bash
sudo apt update
```

### Upgrade

```bash
sudo apt upgrade
```

### Install

```bash
sudo apt install vim
```

### Remove

```bash
sudo apt remove vim
sudo apt purge vim
```

---

## Chapter 13: Shell Scripting

### Hello Script

```bash
#!/bin/bash
echo "Hello World"
```

Run:

```bash
chmod +x script.sh
./script.sh
```

### Variables

```bash
NAME="World"
echo "Hello $NAME"
```

### If Statement

```bash
if [ -f file.txt ]; then
 echo "Exists"
else
 echo "Missing"
fi
```

---

## Chapter 14: Cron Jobs

```bash
crontab -e
```

Run every day at 5AM:

```bash
0 5 * * * /path/script.sh
```

---

## Chapter 15: Aliases

```bash
alias ll='ls -lh'
unalias ll
```

Persistent:

```bash
echo "alias ll='ls -lh'" >> ~/.bashrc
source ~/.bashrc
```

---

## Chapter 16: Users

```bash
sudo adduser newuser
sudo deluser olduser
su - username
passwd username
```

---

## Chapter 17: Zip

```bash
zip files.zip file1 file2
unzip files.zip
```

---

## Chapter 18: Text Processing

### Awk

```bash
awk '{print $1}' file.txt
```

### Sed

```bash
sed 's/old/new/g' file.txt
```

### Tr

```bash
echo hello | tr a-z A-Z
```

### Sort

```bash
sort file.txt
```

### Cut

```bash
cut -d':' -f1 /etc/passwd
```

---

## Chapter 19: Loops

### For

```bash
for i in {1..10}; do echo $i; done
```

### While

```bash
x=1
while [ $x -le 5 ]; do
 echo $x
 x=$((x+1))
done
```

---

## SSH Service

```bash
sudo service ssh start
ssh kali@192.168.56.101
```

---

End of File

```


