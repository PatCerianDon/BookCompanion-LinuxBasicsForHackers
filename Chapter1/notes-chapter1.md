# Chapter 1 - Getting Started with the Basics
## Introductory Terms and Concepts

- **Binaries** : refers to files that can be executed, similar to executables in Windows. Generally resides in /usr/bin or /usr/sbin directory.  
- **Case sensitivity**: Linux filesystem is case-sensitive. For example *Desktop* is different from *desktop*. If encountering "file or directory not found" error, make sure to check your case.
- **Directory** : Provides a way to organize files, usually in a hierarchical manner. Same as folders in Windows.
- **Home** : Each user has their own /home directory. Files created will save here by default.
- **Kali** : A linux distribution designed for penetration testing. Comes with hundreds of tools pre-installed for use in ethical hacking.
- **root** : The administrator or superuser account for Linux systems. Able to reconfigure system, add users, change passwords, etc. As a hacker or penetration tester, gaining access to the root user is an important goal.
- **Script** : Series of commands run in interpretive environment that converts to source code. Can be run with the bash interpreter or any other scripting language interpreter such as Python, Perl, or Ruby. Python is currently the most popular.
- **Shell** : Environment and interpreter for running commands in Linux. Most widely used shell is BASH, which stands for Bourne-again Shell. Other popular shells include C shell and Z shell. 
- **Terminal** : Another name for Command line interface (CLI).

## The Linux Filesystem

- **/** : The root (/) of the filesystem is at the top of the tree hierarchy. 
- **/root** : Home directory of all-powerful root user.
- **/etc** : Contains the Linux configuration files, files that control when and how programs start up.
- **/home** : The user's home directory. 
- **/mnt** : Where other filesystems are attached or mounted to the filesystem.
- **/media** : Where CDs and USB devices are mounted to filesystem. 
- **/bin** : Where application binaries reside, the equivalent of executables in Microsoft Windows. 
- **/lib** : Where libraries reside, similar to DLLs in Microsoft Windows. 

## Basic Commands in Linux

- pwd : Returns location within the directory structure. 
- whoami : Print the username associated with current effective user ID. 
- cd : Short for *change directory*. Used to change directories from the terminal.
- ls : List the contents of the current directory. 
- help : Provides help information for commands. Nearly every command, application, or utility has a dedicated help file. --help or -h.
- man : Short for manual. Displays the manual or help documentation that includes description and important syntax. 
- locate : Find every occurrence of file by name and prints results.
- whereis : Locate the binary, source, and manual page files for a command.
- which : Locates the pathname of files that can be executed in current environment. 
- find : Searches for files in a directory hierarchy. Able to search from a starting point, specific file type, name, etc.
- ps : Displays a snapshot of current running processes. 
- grep : Filter for specific keywords or patterns.
- cat : Concatenate files and print on the standard output.
- touch : Change details of file, such as timestamps. If file doesn't exist, file will be created by default. 
- mkdir : Create directory.
- cp : Copies files and directories. 
- mv : Move (or rename) files.
- rm : Remove files or directories. 
- rmdir : Remove directory if empty.

## Exercises
1. Use the ls command from the root (/) directory to explore the directory structure of Linux. Move to each of the directories with the cd command and run pwd to verify where you are in the directory structure.
2. Use the whoami command to verify which user you are logged in as.
3. Use the locate command to find wordlists that can be used for password cracking.
4. Use the cat command to create a new file and then append to that file. Keep in mind that > redirects input to a file and >> appends to a file. 
5. Create a new directory called hackerdirectory and create a new file in that directory named hackedfile. Now copy that file to your /root directory and rename it secretfile.
