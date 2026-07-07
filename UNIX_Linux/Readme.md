# UNIX & Linux Fundamentals

## What is an Operating System?

An Operating System (OS) is system software that acts as an interface between users and computer hardware. It manages hardware resources, runs applications, and provides services to users.

### Functions of an Operating System

* Process Management
* Memory Management
* File Management
* Device Management
* Security Management
* User Management

### Examples

* Windows
* Linux
* UNIX
* macOS

---

# What is UNIX?

UNIX is a multiuser, multitasking operating system developed at Bell Labs in the 1970s.

It was designed to be:

* Portable
* Secure
* Stable
* Efficient

UNIX became the foundation for many modern operating systems.

### Popular UNIX Variants

* AIX
* HP-UX
* Solaris

---

# What is Linux?

Linux is an open-source operating system based on UNIX principles.

It was created by Linus Torvalds in 1991.

Unlike UNIX, Linux is:

* Free
* Open Source
* Community Driven
* Highly Customizable

---

# Why Linux is Popular

### Stability

Linux systems can run for months or years without rebooting.

### Security

Linux has strong permission and security mechanisms.

### Performance

Efficient resource utilization.

### Open Source

Source code is publicly available.

### Server Dominance

Most web servers, cloud platforms, and supercomputers run Linux.

---

# Linux Distributions (Distros)

A Linux Distribution is a complete operating system built around the Linux kernel.

### Popular Distributions

#### Ubuntu

* Beginner friendly
* Widely used

#### Red Hat Enterprise Linux (RHEL)

* Enterprise environments
* Common in corporate organizations

#### CentOS

* Community-supported enterprise distribution

#### Debian

* Stable and secure

#### Fedora

* Latest technologies and features

#### Kali Linux

* Security testing and penetration testing

---

# UNIX vs Linux

| Feature           | UNIX               | Linux                   |
| ----------------- | ------------------ | ----------------------- |
| License           | Proprietary        | Open Source             |
| Cost              | Usually Paid       | Mostly Free             |
| Source Code       | Closed             | Open                    |
| Flexibility       | Limited            | Highly Flexible         |
| Community Support | Limited            | Massive Community       |
| Popularity        | Enterprise Systems | Servers, Cloud, Desktop |

---

# Features of Linux

### Multiuser

Multiple users can access the system simultaneously.

---

### Multitasking

Multiple processes can run concurrently.

---

### Portability

Runs on different hardware platforms.

---

### Security

User authentication and file permissions provide protection.

---

### Hierarchical File System

Files are organized in a tree-like structure.

---

# Linux Architecture

Linux consists of the following layers:

```text
User
↓
Applications
↓
Shell
↓
Kernel
↓
Hardware
```

---

## Kernel

The kernel is the core of the operating system.

Responsibilities:

* Process management
* Memory management
* Device management
* File system management

---

## Shell

The shell acts as an interface between the user and the kernel.

It interprets user commands.

Popular shells:

* Bash
* Sh
* Ksh
* Csh
* Zsh

---

# Types of Shells

## Bourne Shell (sh)

One of the earliest UNIX shells.

---

## Bourne Again Shell (bash)

Most commonly used Linux shell.

Features:

* Command history
* Auto-completion
* Scripting support

---

## Korn Shell (ksh)

Popular in enterprise UNIX environments.

---

## C Shell (csh)

Syntax similar to the C programming language.

---

# Linux File System Overview

Everything in Linux is treated as a file.

Examples:

* Documents
* Directories
* Devices
* Processes

Linux follows a hierarchical directory structure beginning from the root directory.

```text
/
├── bin
├── boot
├── dev
├── etc
├── home
├── lib
├── opt
├── root
├── tmp
├── usr
└── var
```

---

# Important Linux Directories

## /

Root directory of the entire file system.

---

## /home

Stores user home directories.

Example:

```text
/home/priyasha
```

---

## /root

Home directory of the root user.

---

## /etc

Stores configuration files.

---

## /bin

Essential user commands.

Examples:

* ls
* cp
* mv
* cat

---

## /tmp

Stores temporary files.

---

## /usr

Contains applications and user utilities.

---

## /var

Stores logs and variable data.

Examples:

* System logs
* Mail files
* Print queues

---

# Basic Linux Terminology

## File

A collection of data stored under a name.

---

## Directory

A container used to organize files.

---

## Path

The location of a file or directory.

Example:

```text
/home/user/document.txt
```

---

## Absolute Path

Starts from root (/).

Example:

```text
/var/log/messages
```

---

## Relative Path

Starts from current directory.

Example:

```text
documents/report.txt
```

---

# Quick Revision

✅ UNIX Basics

✅ Linux Basics

✅ Linux Distributions

✅ UNIX vs Linux

✅ Linux Architecture

✅ Kernel

✅ Shell

✅ Linux File System

✅ Important Directories

✅ Absolute Path

✅ Relative Path

These are foundational concepts that frequently appear in TCS ITIS assessments and interviews.


# Linux Commands and File Operations

## Command Syntax

Most Linux commands follow this format:

```bash
command [options] [arguments]
```

### Example

```bash
ls -l /home
```

* `ls` → command
* `-l` → option
* `/home` → argument

---

# Getting Help in Linux

## man Command

Displays the manual page of a command.

### Syntax

```bash
man command_name
```

### Example

```bash
man ls
```

---

## --help Option

Provides a quick description of a command.

### Example

```bash
ls --help
```

---

# Present Working Directory

## pwd Command

Displays the current working directory.

### Syntax

```bash
pwd
```

### Example Output

```text
/home/priyasha
```

---

# Listing Files and Directories

## ls Command

Lists files and directories.

### Syntax

```bash
ls
```

### Example

```bash
ls
```

Output:

```text
Documents
Downloads
Pictures
```

---

## Common ls Options

### ls -l

Long listing format.

```bash
ls -l
```

Displays:

* Permissions
* Owner
* Size
* Date
* File name

---

### ls -a

Shows hidden files.

```bash
ls -a
```

Hidden files begin with a dot (`.`).

Example:

```text
.bashrc
.profile
```

---

### ls -la

Shows hidden files in long format.

```bash
ls -la
```

---

### ls -R

Displays directories recursively.

```bash
ls -R
```

---

# Changing Directories

## cd Command

Used to move between directories.

### Syntax

```bash
cd directory_name
```

### Example

```bash
cd Documents
```

---

## Move to Home Directory

```bash
cd
```

or

```bash
cd ~
```

---

## Move One Level Up

```bash
cd ..
```

---

## Move to Root Directory

```bash
cd /
```

---

# Creating Directories

## mkdir Command

Creates a new directory.

### Syntax

```bash
mkdir directory_name
```

### Example

```bash
mkdir project
```

---

## Create Multiple Directories

```bash
mkdir dir1 dir2 dir3
```

---

## Create Nested Directories

```bash
mkdir -p project/java/src
```

---

# Removing Directories

## rmdir Command

Removes an empty directory.

### Example

```bash
rmdir project
```

---

## rm -r Command

Removes a directory and its contents.

### Example

```bash
rm -r project
```

---

## rm -rf Command

Forcefully removes files and directories.

```bash
rm -rf project
```

⚠ Use carefully. Recovery is difficult.

---

# Creating Files

## touch Command

Creates an empty file.

### Example

```bash
touch notes.txt
```

---

## Create Multiple Files

```bash
touch file1.txt file2.txt file3.txt
```

---

# Viewing File Contents

## cat Command

Displays file contents.

### Example

```bash
cat notes.txt
```

---

## Create File Using cat

```bash
cat > notes.txt
```

Type content and press:

```text
Ctrl + D
```

to save.

---

## tac Command

Displays content in reverse order.

### Example

```bash
tac notes.txt
```

---

# Copying Files

## cp Command

Copies files or directories.

### Syntax

```bash
cp source destination
```

### Example

```bash
cp notes.txt backup.txt
```

---

## Copy Directory

```bash
cp -r project backup_project
```

---

# Moving and Renaming Files

## mv Command

Used for moving or renaming files.

### Rename Example

```bash
mv notes.txt linux_notes.txt
```

---

### Move Example

```bash
mv notes.txt Documents/
```

---

# Deleting Files

## rm Command

Removes files.

### Example

```bash
rm notes.txt
```

---

## Force Delete

```bash
rm -f notes.txt
```

---

# Displaying File Content Efficiently

## more Command

Displays content page by page.

### Example

```bash
more logfile.txt
```

---

## less Command

Improved version of more.

### Example

```bash
less logfile.txt
```

Advantages:

* Scroll up and down
* Search within files

---

# Display Beginning of File

## head Command

Displays first 10 lines.

### Example

```bash
head logfile.txt
```

---

## Display First 5 Lines

```bash
head -5 logfile.txt
```

---

# Display End of File

## tail Command

Displays last 10 lines.

### Example

```bash
tail logfile.txt
```

---

## Display Last 20 Lines

```bash
tail -20 logfile.txt
```

---

## Real-Time Log Monitoring

```bash
tail -f logfile.txt
```

Frequently used by system administrators.

---

# Counting Information

## wc Command

Word Count command.

### Example

```bash
wc notes.txt
```

Displays:

* Lines
* Words
* Characters

---

## Count Lines

```bash
wc -l notes.txt
```

---

## Count Words

```bash
wc -w notes.txt
```

---

## Count Characters

```bash
wc -c notes.txt
```

---

# Quick Revision

| Command | Purpose                 |
| ------- | ----------------------- |
| pwd     | Show current directory  |
| ls      | List files              |
| cd      | Change directory        |
| mkdir   | Create directory        |
| rmdir   | Remove empty directory  |
| rm      | Delete files            |
| cp      | Copy files              |
| mv      | Move/Rename files       |
| touch   | Create file             |
| cat     | Display file content    |
| head    | First lines of file     |
| tail    | Last lines of file      |
| wc      | Count lines/words/chars |
| more    | View file page by page  |
| less    | Advanced file viewer    |

---

# Most Asked TCS ITIS Questions

### Which command displays the current working directory?

**Answer:** `pwd`

---

### Which command creates an empty file?

**Answer:** `touch`

---

### Which command is used to rename a file?

**Answer:** `mv`

---

### Which command displays hidden files?

**Answer:** `ls -a`

---

### Which command shows the last lines of a file?

**Answer:** `tail`

---

### Which command is used to count lines in a file?

**Answer:** `wc -l`

These commands form the foundation of Linux administration and are frequently tested in TCS ITIS assessments.


# Wildcards, Redirection, Pipes & Filters

## What are Wildcards?

Wildcards are special characters used to match file names and patterns.

They help users perform operations on multiple files without specifying each file individually.

---

# Asterisk (*)

The asterisk (`*`) represents zero or more characters.

### Example

Suppose the directory contains:

```text id="u1a7x9"
file1.txt
file2.txt
notes.txt
report.pdf
```

Command:

```bash id="r5m2k8"
ls *.txt
```

Output:

```text id="v8n3p1"
file1.txt
file2.txt
notes.txt
```

---

### Example

```bash id="q4j8m6"
rm *.tmp
```

Deletes all files ending with `.tmp`.

---

# Question Mark (?)

Represents exactly one character.

### Example

Files:

```text id="m7c2f5"
file1.txt
file2.txt
file10.txt
```

Command:

```bash id="n3d9k1"
ls file?.txt
```

Output:

```text id="b6e4t7"
file1.txt
file2.txt
```

`file10.txt` is not matched because `?` matches only one character.

---

# Square Brackets []

Used to match any one character from a set.

### Example

```bash id="h2y5r8"
ls file[123].txt
```

Matches:

```text id="j9w4u2"
file1.txt
file2.txt
file3.txt
```

---

### Character Ranges

```bash id="k8v3m7"
ls file[a-z].txt
```

Matches files containing any lowercase alphabet.

---

# Input and Output Redirection

Normally:

* Keyboard = Input
* Screen = Output

Redirection allows input/output to be redirected elsewhere.

---

# Output Redirection (>)

Writes output to a file.

### Syntax

```bash id="c4f9b2"
command > filename
```

### Example

```bash id="g7r2x5"
ls > files.txt
```

Stores command output in `files.txt`.

---

### Important

If the file already exists:

```bash id="t5n8q1"
ls > files.txt
```

The old content is overwritten.

---

# Append Output (>>)

Adds output to an existing file.

### Example

```bash id="d3w7e9"
date >> log.txt
```

New content is appended instead of replacing existing data.

---

# Input Redirection (<)

Takes input from a file.

### Example

```bash id="p6k1y4"
sort < names.txt
```

The `sort` command reads data from `names.txt`.

---

# Standard Streams

Linux uses three standard streams:

| Stream | Description     |
| ------ | --------------- |
| stdin  | Standard Input  |
| stdout | Standard Output |
| stderr | Standard Error  |

---

# Error Redirection

## Redirect Errors

```bash id="x1n4z8"
command 2> errors.txt
```

Stores error messages in a file.

---

## Redirect Output and Errors Together

```bash id="a9k6p3"
command > output.txt 2>&1
```

---

# Pipes (|)

A pipe sends the output of one command as input to another command.

### Syntax

```bash id="e8t5u1"
command1 | command2
```

---

### Example

```bash id="s2m7v4"
ls | sort
```

Flow:

```text id="r6y3q9"
ls output
     ↓
sort input
```

---

### Example

```bash id="f5k8j2"
cat names.txt | sort
```

Displays sorted content.

---

# Filters

Filters process input and produce modified output.

Common filters:

* grep
* sort
* uniq
* cut
* tr
* head
* tail
* wc

---

# grep Command

Searches for patterns in files.

### Syntax

```bash id="w4p7n1"
grep pattern filename
```

---

### Example

```bash id="y9m2r5"
grep linux notes.txt
```

Displays lines containing the word "linux".

---

### Ignore Case

```bash id="u3v8k6"
grep -i linux notes.txt
```

Matches:

```text id="z7f1t4"
Linux
LINUX
linux
```

---

### Display Line Numbers

```bash id="q5c9w2"
grep -n linux notes.txt
```

---

# sort Command

Sorts file contents.

### Example

```bash id="b8n4x7"
sort names.txt
```

---

### Reverse Sort

```bash id="m2k5r9"
sort -r names.txt
```

---

# uniq Command

Removes consecutive duplicate lines.

### Example

```bash id="j6t3v8"
uniq names.txt
```

---

### Count Duplicates

```bash id="c9w2p5"
uniq -c names.txt
```

---

# cut Command

Extracts specific columns from data.

### Example

```bash id="g3r8k1"
cut -c 1-5 file.txt
```

Displays characters 1 through 5.

---

### Extract Fields

```bash id="x7n4q2"
cut -d ":" -f 1 /etc/passwd
```

Displays usernames from the passwd file.

---

# tr Command

Translates or replaces characters.

### Convert Lowercase to Uppercase

```bash id="p2v9m6"
cat file.txt | tr a-z A-Z
```

---

### Remove Characters

```bash id="k5r1w8"
cat file.txt | tr -d " "
```

Removes spaces.

---

# Search Commands

Searching files is a common administrator task.

---

# find Command

Searches for files and directories.

### Syntax

```bash id="t8m3q7"
find path options
```

---

### Example

```bash id="f4n6k9"
find /home -name notes.txt
```

Searches for `notes.txt`.

---

### Search All .txt Files

```bash id="u7p2x4"
find /home -name "*.txt"
```

---

### Search Directories Only

```bash id="r9v5k1"
find /home -type d
```

---

### Search Files Only

```bash id="c6t8m3"
find /home -type f
```

---

# which Command

Displays the location of executable commands.

### Example

```bash id="h4y7n2"
which ls
```

Output:

```text id="m1r8q5"
/usr/bin/ls
```

---

# whereis Command

Displays binary, source, and manual page locations.

### Example

```bash id="k2w9p4"
whereis grep
```

---

# locate Command

Searches using a prebuilt database.

### Example

```bash id="d5v1m8"
locate notes.txt
```

Faster than `find` for many searches.

---

# Quick Revision Table

| Symbol / Command | Purpose                   |
| ---------------- | ------------------------- |
| *                | Match multiple characters |
| ?                | Match one character       |
| []               | Match character set       |
| >                | Redirect output           |
| >>               | Append output             |
| <                | Redirect input            |
| |                | Pipe output               |
| grep             | Search patterns           |
| sort             | Sort data                 |
| uniq             | Remove duplicates         |
| cut              | Extract columns           |
| tr               | Translate characters      |
| find             | Search files              |
| which            | Locate executable         |
| whereis          | Find command locations    |
| locate           | Fast file search          |

---

# Frequently Asked TCS ITIS MCQs

### Which wildcard matches any number of characters?

**Answer:** `*`

---

### Which command searches for a pattern inside a file?

**Answer:** `grep`

---

### Which operator appends output to an existing file?

**Answer:** `>>`

---

### Which command locates executable files?

**Answer:** `which`

---

### Which command is generally faster than find because it uses a database?

**Answer:** `locate`

---

### What does a pipe (`|`) do?

**Answer:** Passes the output of one command as input to another command.

# File Permissions, Ownership & Process Management

## Linux Security Model

Linux is a multi-user operating system.

This means multiple users can access the same system simultaneously.

To protect files and resources, Linux uses:

* Users
* Groups
* Permissions
* Ownership

---

# Understanding File Permissions

Run:

```bash
ls -l
```

Example Output:

```text
-rwxr-xr-- 1 user admin 2048 Jul 7 notes.txt
```

Let's break it down:

```text
-rwxr-xr--
```

---

## First Character

Indicates file type.

| Symbol | Meaning          |
| ------ | ---------------- |
| -      | Regular File     |
| d      | Directory        |
| l      | Symbolic Link    |
| c      | Character Device |
| b      | Block Device     |

Example:

```text
drwxr-xr-x
```

means it is a directory.

---

# Permission Categories

Permissions are divided into three groups:

```text
Owner | Group | Others
```

Example:

```text
rwx r-x r--
```

---

## Owner (User)

The creator or owner of the file.

---

## Group

Users belonging to the same group.

---

## Others

All remaining users.

---

# Permission Types

## Read (r)

Value = 4

Allows:

* View file contents
* Read data

Example:

```bash
cat file.txt
```

---

## Write (w)

Value = 2

Allows:

* Modify files
* Delete files (with directory permissions)

---

## Execute (x)

Value = 1

Allows:

* Run scripts
* Execute programs

Example:

```bash
./script.sh
```

---

# Permission Calculation

| Permission | Value |
| ---------- | ----- |
| Read       | 4     |
| Write      | 2     |
| Execute    | 1     |

---

### Example

```text
rwx
```

Calculation:

```text
4 + 2 + 1 = 7
```

---

### Example

```text
rw-
```

Calculation:

```text
4 + 2 = 6
```

---

### Example

```text
r--
```

Calculation:

```text
4
```

---

# Common Permission Values

| Value | Permission |
| ----- | ---------- |
| 777   | rwxrwxrwx  |
| 755   | rwxr-xr-x  |
| 744   | rwxr--r--  |
| 700   | rwx------  |
| 666   | rw-rw-rw-  |
| 644   | rw-r--r--  |

---

# chmod Command

Used to change permissions.

## Syntax

```bash
chmod permissions file
```

---

### Example

```bash
chmod 755 script.sh
```

Result:

```text
rwxr-xr-x
```

---

### Example

```bash
chmod 644 notes.txt
```

Result:

```text
rw-r--r--
```

---

# Symbolic Method

### Add Execute Permission

```bash
chmod +x script.sh
```

---

### Remove Write Permission

```bash
chmod -w file.txt
```

---

### Add Permission for Owner

```bash
chmod u+x script.sh
```

---

### Add Permission for Group

```bash
chmod g+w file.txt
```

---

### Add Permission for Others

```bash
chmod o+r file.txt
```

---

# File Ownership

Every file has:

* Owner
* Group

View ownership:

```bash
ls -l
```

Example:

```text
user admin notes.txt
```

Owner = user

Group = admin

---

# chown Command

Changes file ownership.

## Syntax

```bash
chown owner file
```

---

### Example

```bash
chown john file.txt
```

Owner becomes:

```text
john
```

---

### Change Owner and Group

```bash
chown john:developers file.txt
```

---

# chgrp Command

Changes group ownership.

### Example

```bash
chgrp developers file.txt
```

---

# Special User: Root

Root is the superuser.

Capabilities:

* Access all files
* Modify permissions
* Create users
* Install software

---

## Switch to Root

```bash
su
```

or

```bash
sudo su
```

---

# sudo Command

Allows authorized users to execute commands with administrative privileges.

Example:

```bash
sudo apt update
```

---

# Process Management

## What is a Process?

A process is a program currently being executed.

Examples:

* Browser
* Database Server
* Shell
* Text Editor

---

# View Running Processes

## ps Command

Displays current processes.

### Example

```bash
ps
```

---

## Detailed Information

```bash
ps -ef
```

Commonly used by administrators.

---

# top Command

Displays processes in real time.

### Example

```bash
top
```

Shows:

* CPU usage
* Memory usage
* Running processes

---

# Process States

| State | Meaning  |
| ----- | -------- |
| R     | Running  |
| S     | Sleeping |
| T     | Stopped  |
| Z     | Zombie   |

---

# Process ID (PID)

Every process has a unique identifier.

Example:

```text
PID = 1234
```

---

# Killing Processes

## kill Command

Terminates a process.

### Syntax

```bash
kill PID
```

---

### Example

```bash
kill 1234
```

---

# Force Kill

```bash
kill -9 1234
```

SIGKILL immediately terminates the process.

---

# Kill by Process Name

```bash
pkill firefox
```

---

# User Management

Linux administrators frequently manage users.

---

# Create User

## useradd

```bash
useradd john
```

---

# Set Password

## passwd

```bash
passwd john
```

---

# Delete User

```bash
userdel john
```

---

# View Current User

```bash
whoami
```

---

# Display Logged-In Users

```bash
who
```

---

# User Information

```bash
id
```

Displays:

* User ID (UID)
* Group ID (GID)

---

# Environment Variables

Store system information.

View all variables:

```bash
env
```

---

## Display Current User

```bash
echo $USER
```

---

## Display Home Directory

```bash
echo $HOME
```

---

# Quick Revision Table

| Command | Purpose                     |
| ------- | --------------------------- |
| chmod   | Change permissions          |
| chown   | Change owner                |
| chgrp   | Change group                |
| sudo    | Run administrative commands |
| ps      | View processes              |
| top     | Real-time processes         |
| kill    | Terminate process           |
| pkill   | Kill by name                |
| useradd | Create user                 |
| passwd  | Set password                |
| userdel | Delete user                 |
| whoami  | Current user                |
| who     | Logged-in users             |
| id      | User information            |
| env     | Environment variables       |

---

# Most Asked TCS ITIS Questions

### What does chmod 755 mean?

**Answer:**
Owner = rwx (7)

Group = r-x (5)

Others = r-x (5)

---

### Which command changes file ownership?

**Answer:** `chown`

---

### Which command displays running processes?

**Answer:** `ps`

---

### Which command shows real-time system activity?

**Answer:** `top`

---

### Which command forcefully kills a process?

**Answer:** `kill -9 PID`

---

### Which command displays the current username?

**Answer:** `whoami`

---

### What is the numeric value of Read permission?

**Answer:** `4`

### What is the numeric value of Write permission?

**Answer:** `2`

### What is the numeric value of Execute permission?

**Answer:** `1`

These concepts are heavily tested in Linux administration interviews, support roles, and TCS ITIS assessments.

# Shell Scripting & Networking Commands

## What is Shell Scripting?

A shell script is a text file containing a sequence of Linux commands that are executed automatically.

Instead of typing commands one by one, we can place them in a script and execute them together.

Benefits:

* Automation
* Reduced manual effort
* Consistency
* Faster administration
* Task scheduling

---

# Creating Your First Shell Script

Create a file:

```bash id="s1"
nano hello.sh
```

Add:

```bash id="s2"
#!/bin/bash

echo "Hello World"
```

Save the file.

---

# Make Script Executable

```bash id="s3"
chmod +x hello.sh
```

---

# Run Script

```bash id="s4"
./hello.sh
```

Output:

```text id="s5"
Hello World
```

---

# Shebang (#!)

The first line of a script.

Example:

```bash id="s6"
#!/bin/bash
```

Tells Linux which interpreter should execute the script.

---

# Variables

Variables store data.

### Syntax

```bash id="s7"
name="Priyasha"
```

Access variable:

```bash id="s8"
echo $name
```

Output:

```text id="s9"
Priyasha
```

---

# User Input

Use `read` to accept input.

Example:

```bash id="s10"
echo "Enter your name:"
read name

echo "Welcome $name"
```

---

# Command-Line Arguments

Arguments can be passed while running a script.

Example:

```bash id="s11"
./script.sh Priyasha
```

Script:

```bash id="s12"
echo $1
```

Output:

```text id="s13"
Priyasha
```

---

# Special Variables

| Variable | Meaning             |
| -------- | ------------------- |
| $0       | Script Name         |
| $1       | First Argument      |
| $2       | Second Argument     |
| $#       | Number of Arguments |
| $?       | Exit Status         |
| $$       | Process ID          |

---

# Conditional Statements

## if Statement

Example:

```bash id="s14"
age=20

if [ $age -ge 18 ]
then
    echo "Eligible"
fi
```

Output:

```text id="s15"
Eligible
```

---

# if-else Statement

```bash id="s16"
marks=35

if [ $marks -ge 40 ]
then
    echo "Pass"
else
    echo "Fail"
fi
```

---

# if-elif-else

```bash id="s17"
marks=80

if [ $marks -ge 90 ]
then
    echo "A Grade"

elif [ $marks -ge 75 ]
then
    echo "B Grade"

else
    echo "C Grade"
fi
```

---

# Loops

Loops repeat commands.

---

# for Loop

Example:

```bash id="s18"
for i in 1 2 3 4 5
do
    echo $i
done
```

Output:

```text id="s19"
1
2
3
4
5
```

---

# while Loop

Example:

```bash id="s20"
count=1

while [ $count -le 5 ]
do
    echo $count
    count=$((count+1))
done
```

---

# Case Statement

Alternative to multiple if-else conditions.

```bash id="s21"
read choice

case $choice in

1)
echo "Add"
;;

2)
echo "Delete"
;;

3)
echo "Update"
;;

*)
echo "Invalid Choice"
;;

esac
```

---

# Functions

Functions allow code reuse.

Example:

```bash id="s22"
greet()
{
    echo "Welcome"
}

greet
```

---

# Exit Status

Every command returns a status code.

| Value    | Meaning |
| -------- | ------- |
| 0        | Success |
| Non-Zero | Failure |

Check status:

```bash id="s23"
echo $?
```

---

# Networking Commands

Network troubleshooting is a major responsibility in IT Infrastructure roles.

---

# ping Command

Checks connectivity between systems.

### Example

```bash id="s24"
ping google.com
```

Output shows:

* Reachability
* Packet loss
* Response time

---

# Send Limited Packets

```bash id="s25"
ping -c 4 google.com
```

Sends only 4 packets.

---

# ip Command

Displays network information.

### Show IP Address

```bash id="s26"
ip addr
```

or

```bash id="s27"
ip a
```

---

# ifconfig Command

Legacy command used to display network interfaces.

```bash id="s28"
ifconfig
```

Still commonly seen in older systems.

---

# hostname Command

Displays system hostname.

```bash id="s29"
hostname
```

---

# nslookup Command

Queries DNS information.

### Example

```bash id="s30"
nslookup google.com
```

Used to verify DNS resolution.

---

# traceroute Command

Displays the path packets take to reach a destination.

Example:

```bash id="s31"
traceroute google.com
```

Useful for network troubleshooting.

---

# netstat Command

Displays network statistics and connections.

### Example

```bash id="s32"
netstat -an
```

Shows:

* Open ports
* Active connections
* Listening services

---

# ss Command

Modern replacement for netstat.

```bash id="s33"
ss -tuln
```

Displays:

* TCP ports
* UDP ports
* Listening services

---

# SSH (Secure Shell)

Used for secure remote login.

### Connect to Remote Server

```bash id="s34"
ssh user@server_ip
```

Example:

```bash id="s35"
ssh admin@192.168.1.10
```

---

# SCP (Secure Copy)

Transfers files securely between systems.

### Copy File to Remote Server

```bash id="s36"
scp file.txt user@server:/home/user
```

---

### Copy File from Remote Server

```bash id="s37"
scp user@server:/home/user/file.txt .
```

---

# wget Command

Downloads files from the internet.

Example:

```bash id="s38"
wget https://example.com/file.zip
```

---

# curl Command

Transfers data between systems.

Example:

```bash id="s39"
curl https://example.com
```

Commonly used for APIs.

---

# Network Troubleshooting Workflow

### Step 1

Check connectivity.

```bash id="s40"
ping target
```

---

### Step 2

Verify IP configuration.

```bash id="s41"
ip addr
```

---

### Step 3

Check DNS resolution.

```bash id="s42"
nslookup domain
```

---

### Step 4

Trace network route.

```bash id="s43"
traceroute domain
```

---

### Step 5

Verify open ports.

```bash id="s44"
ss -tuln
```

---

# Quick Revision Table

| Command    | Purpose               |
| ---------- | --------------------- |
| echo       | Display output        |
| read       | Accept input          |
| if         | Conditional execution |
| for        | Loop                  |
| while      | Loop                  |
| case       | Multiple conditions   |
| ping       | Connectivity test     |
| ip addr    | View IP address       |
| ifconfig   | Network interfaces    |
| hostname   | System name           |
| nslookup   | DNS lookup            |
| traceroute | Trace route           |
| netstat    | Network statistics    |
| ss         | Network sockets       |
| ssh        | Remote login          |
| scp        | Secure file transfer  |
| wget       | Download files        |
| curl       | Data transfer         |

---

# Most Asked TCS ITIS Questions

### Which command checks connectivity to another system?

**Answer:** `ping`

---

### Which command is used for secure remote login?

**Answer:** `ssh`

---

### Which command displays IP address information?

**Answer:** `ip addr`

---

### Which command performs DNS lookup?

**Answer:** `nslookup`

---

### Which command securely copies files between systems?

**Answer:** `scp`

---

### What does exit status 0 indicate?

**Answer:** Successful execution.

---

### Which command is considered a modern replacement for netstat?

**Answer:** `ss`

These shell scripting and networking concepts are commonly tested in Linux administration, support engineering, and TCS ITIS assessments.

# Package Management, Disk Management & Job Scheduling

## What is Package Management?

Software in Linux is usually installed, updated, and removed using package managers.

A package manager:

* Installs software
* Updates software
* Removes software
* Resolves dependencies
* Maintains package databases

---

# Package Managers in Linux

| Distribution      | Package Manager |
| ----------------- | --------------- |
| Ubuntu/Debian     | apt             |
| RHEL/CentOS       | yum             |
| RHEL 8+, Fedora   | dnf             |
| Low-Level Package | rpm             |

---

# APT (Advanced Package Tool)

Used in Ubuntu and Debian-based systems.

---

## Update Package Repository

```bash id="p1"
sudo apt update
```

Downloads information about available packages.

---

## Upgrade Installed Packages

```bash id="p2"
sudo apt upgrade
```

Updates installed software to newer versions.

---

## Install Package

```bash id="p3"
sudo apt install nginx
```

Installs Nginx web server.

---

## Remove Package

```bash id="p4"
sudo apt remove nginx
```

Removes software while keeping configuration files.

---

## Remove Package Completely

```bash id="p5"
sudo apt purge nginx
```

Removes package and configuration files.

---

## Search Package

```bash id="p6"
apt search nginx
```

---

# YUM (Yellowdog Updater Modified)

Common in older Red Hat-based systems.

---

## Install Package

```bash id="p7"
sudo yum install httpd
```

---

## Update Package

```bash id="p8"
sudo yum update
```

---

## Remove Package

```bash id="p9"
sudo yum remove httpd
```

---

# DNF

Modern replacement for YUM.

---

## Install Package

```bash id="p10"
sudo dnf install httpd
```

---

## Update Packages

```bash id="p11"
sudo dnf update
```

---

# RPM

Low-level package manager.

RPM = Red Hat Package Manager

---

## Install RPM Package

```bash id="p12"
rpm -ivh package.rpm
```

---

## Remove RPM Package

```bash id="p13"
rpm -e package_name
```

---

## List Installed Packages

```bash id="p14"
rpm -qa
```

---

# Disk Management

Storage monitoring is an important administrator responsibility.

---

# df Command

Displays disk space usage.

### Example

```bash id="p15"
df -h
```

Options:

* h = Human-readable

Output example:

```text id="p16"
Filesystem  Size Used Avail Use%
/dev/sda1   100G 40G 60G 40%
```

---

# du Command

Displays directory space usage.

### Example

```bash id="p17"
du -sh Documents
```

Output:

```text id="p18"
250M Documents
```

---

## Display Subdirectory Sizes

```bash id="p19"
du -h
```

---

# File System Information

## lsblk

Lists storage devices.

```bash id="p20"
lsblk
```

Displays:

* Hard disks
* SSDs
* Partitions

---

# Mount Command

Displays mounted file systems.

```bash id="p21"
mount
```

---

# Check Disk Usage Quickly

```bash id="p22"
df -h
```

One of the most frequently used administrator commands.

---

# Memory Management

Monitoring memory usage helps identify performance issues.

---

# free Command

Displays RAM usage.

### Example

```bash id="p23"
free -h
```

Output:

```text id="p24"
Total
Used
Free
Available
```

---

# vmstat Command

Displays virtual memory statistics.

```bash id="p25"
vmstat
```

Useful for performance troubleshooting.

---

# top Command

Real-time resource monitoring.

```bash id="p26"
top
```

Shows:

* CPU usage
* Memory usage
* Running processes

---

# htop Command

Enhanced version of top.

```bash id="p27"
htop
```

Features:

* Better UI
* Easier navigation
* Process management

---

# System Monitoring

## uptime

Displays system running time.

```bash id="p28"
uptime
```

Example:

```text id="p29"
10 days, 5 hours
```

---

# System Information

## uname

Displays system information.

```bash id="p30"
uname
```

---

## Display Kernel Information

```bash id="p31"
uname -r
```

---

## Display Complete Information

```bash id="p32"
uname -a
```

---

# Job Scheduling

Linux can automatically execute commands at specific times.

This is called Job Scheduling.

---

# Cron

Cron is a Linux scheduler.

The cron daemon continuously runs in the background.

---

# crontab

Stores scheduled jobs.

View current jobs:

```bash id="p33"
crontab -l
```

---

# Edit Cron Jobs

```bash id="p34"
crontab -e
```

---

# Cron Format

```text id="p35"
* * * * * command
│ │ │ │ │
│ │ │ │ └ Day of Week
│ │ │ └ Month
│ │ └ Day of Month
│ └ Hour
└ Minute
```

---

# Examples

## Run Every Minute

```text id="p36"
* * * * * script.sh
```

---

## Run Daily at Midnight

```text id="p37"
0 0 * * * backup.sh
```

---

## Run Every Sunday

```text id="p38"
0 8 * * 0 report.sh
```

Runs at 8:00 AM every Sunday.

---

# at Command

Schedules a task to run once.

Example:

```bash id="p39"
at 10:00 PM
```

Then enter commands to execute.

---

# Quick Revision Table

| Command     | Purpose                          |
| ----------- | -------------------------------- |
| apt update  | Update repositories              |
| apt install | Install package                  |
| apt remove  | Remove package                   |
| yum install | Install package (RHEL)           |
| dnf install | Install package (Fedora/RHEL 8+) |
| rpm -qa     | List installed packages          |
| df -h       | Disk usage                       |
| du -sh      | Directory size                   |
| lsblk       | List storage devices             |
| free -h     | Memory usage                     |
| vmstat      | Virtual memory stats             |
| top         | Process monitoring               |
| htop        | Advanced monitoring              |
| uptime      | System uptime                    |
| uname -a    | System information               |
| crontab -e  | Edit scheduled jobs              |
| crontab -l  | View scheduled jobs              |

---

# Most Asked TCS ITIS Questions

### Which command shows available disk space?

**Answer:** `df -h`

---

### Which command shows directory size?

**Answer:** `du -sh`

---

### Which command displays memory usage?

**Answer:** `free -h`

---

### Which command schedules recurring tasks?

**Answer:** `cron` / `crontab`

---

### Which command schedules a one-time task?

**Answer:** `at`

---

### Which command displays kernel information?

**Answer:** `uname -r`

---

### Which package manager is commonly used in Ubuntu?

**Answer:** `apt`

---

### Which package manager is commonly used in Red Hat Enterprise Linux?

**Answer:** `yum` or `dnf`

These commands are frequently used in system administration, production support, cloud environments, and IT Infrastructure operations.


