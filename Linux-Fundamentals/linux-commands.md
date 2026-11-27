🐧 Linux Fundamentals

1. Introduction

Linux is an open-source operating system widely used in servers, cloud computing, networking, and cybersecurity.

Linux provides a command-line interface (CLI) that allows users to manage files, directories, users, permissions, and processes.

2. Basic Linux Commands

Command| Description
pwd| Displays the current directory
ls| Lists files and directories
cd| Changes the current directory
mkdir| Creates a new directory
touch| Creates an empty file
cat| Displays file contents
cp| Copies files
mv| Moves or renames files
rm| Removes files
clear| Clears the terminal

3. File and Directory Management

Create a directory

mkdir cybersecurity

Enter the directory

cd cybersecurity

Create a file

touch notes.txt

Display files

ls -l

Display current location

pwd

4. Linux File Permissions

Linux permissions control who can read, write, or execute files.

Three permission types:

- Read (r) = 4
- Write (w) = 2
- Execute (x) = 1

Three user categories:

- Owner
- Group
- Others

Example:

chmod 755 notes.txt

This gives the owner read, write, and execute permissions, while group and others receive read and execute permissions.

5. Users and Groups

Linux supports multiple users and groups to manage access to system resources.

Useful commands:

whoami

Displays the current username.

id

Displays user and group identification information.

groups

Displays the groups associated with the current user.

6. Process Management

A process is a running instance of a program.

Useful commands:

ps

Displays processes associated with the current terminal.

top

Displays running processes and system resource usage.

ps aux

Displays detailed process information.

7. Linux Security Basics

- Use strong passwords.
- Apply minimum required permissions.
- Keep software updated.
- Avoid unnecessary administrator privileges.
- Review running processes.
- Use trusted software sources.
- Protect confidential files.

8. Practical Exercise

The following commands can be used to practice basic Linux file management:

mkdir lab
cd lab
touch report.txt
ls -l
pwd

Expected learning outcome:

- Created a directory.
- Entered the directory.
- Created a file.
- Listed directory contents.
- Identified the current working directory.

9. Conclusion

Linux fundamentals are essential for cybersecurity professionals. Understanding commands, file permissions, users, groups, and processes provides a foundation for system administration and security analysis.

Author: Ajay M.
Project: Linux Security & Reconnaissance Lab
