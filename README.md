
# Cloud Security Lab 1: Linux Commands Study

## Introduction to Linux

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
![image](https://github.com/user-attachments/assets/27893e2e-01ee-4adf-b375-50dc06510df2)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
![image](https://github.com/user-attachments/assets/f7f0b250-c93c-4035-97e3-09734724db5e)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/7a58ddb9-fb44-4cf0-a06a-5fe470a0eabb)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/12c46f5e-97f8-4c67-9178-319b72e5b323)

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/a4507643-8edb-4ac5-a922-b090fd27a04e)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
![image](https://github.com/user-attachments/assets/dccfd0c9-10b0-470f-8086-34cfcd9536b6)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
![image](https://github.com/user-attachments/assets/1fc2405f-5a24-4341-88ab-b69ca08864e4)


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/c29e5a59-d865-4c5a-aaac-b064a608db2a)

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
![image](https://github.com/user-attachments/assets/bc2c39a6-ab17-45ec-85fc-aca23f246e72)

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
![image](https://github.com/user-attachments/assets/ea469750-58bd-416d-94bf-49d75c5961d2)

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
![image](https://github.com/user-attachments/assets/5a7af388-032a-47ff-b7d0-0d75517e1c03)


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/6c047c08-db1c-413e-8e30-d3535767e949)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/01c5b96d-3321-438a-9257-c6a2ebace192)

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
![image](https://github.com/user-attachments/assets/bb953f13-a28a-4414-b498-174d2fbb28e9)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
![image](https://github.com/user-attachments/assets/846e67d7-b801-49a3-92f3-c04d3c4ecdf2)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
![image](https://github.com/user-attachments/assets/ac6b9244-b67c-4e16-b6d6-2e944fea093a)

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/44653859-a2b9-4006-857e-9e9287a4593a)

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
![image](https://github.com/user-attachments/assets/505a22ed-e405-4f8a-8cce-2a14fb09906b)

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/7c6d6e46-69c8-4db7-9b25-ad88b984bc79)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
![image](https://github.com/user-attachments/assets/8dd4d011-002b-4c28-a1fd-96d2de949152)

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
![image](https://github.com/user-attachments/assets/e8145990-c2c8-4537-b15c-8763af6e84f2)

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
![image](https://github.com/user-attachments/assets/ea4dfe32-a824-4b9e-ade1-683b8d6fef3d)


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
![image](https://github.com/user-attachments/assets/94fbc154-b987-417e-9e03-1375601e7445)


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
![image](https://github.com/user-attachments/assets/c9e7df3d-2f2e-4835-a7ba-ef003e4531b0)


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/c82c29cf-793f-4bbb-ac8a-7417bd31280f)

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
![image](https://github.com/user-attachments/assets/280a7b9d-2f88-4585-b5b0-cc7080e2a8e1)

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
![image](https://github.com/user-attachments/assets/2fd83b15-93f5-47c5-a414-b6ff395cd2a3)


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
![image](https://github.com/user-attachments/assets/19d4e8e1-b5fa-4384-86ae-444988b27d05)


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

## Result
