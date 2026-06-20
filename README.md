# linux-basics


1. What is Linux?

Linux is an open-source operating system that allows users to manage hardware and software resources efficiently.

2. What is a Kernel?

The kernel is the core component of an operating system that acts as a bridge between hardware and software.

3. Difference Between Linux and Windows

Linux is open-source and free to use, whereas Windows is a proprietary, paid, and closed-source operating system.

4. What is a Linux Distribution (Distro)?

A Linux distribution is a packaged version of Linux that includes the kernel, system utilities, and software applications. Examples include Ubuntu, CentOS, and Fedora.

5. What is a Shell?

A shell is a command-line interface that enables communication between the user and the operating system.

6. What is CLI?

CLI (Command Line Interface) is a text-based interface used to interact with the operating system through commands.

7. pwd Command
Definition

Displays the absolute path of the current working directory.

pwd
8. ls Command
Definition

Lists files and directories present in the current location.

ls
9. cd Command
Definition

Changes the current working directory.

cd directory_name
10. mkdir Command
Definition

Creates a new directory.

mkdir new_folder
11. rmdir Command
Definition

Removes an empty directory.

rmdir folder_name
12. touch Command
Definition

Creates a new empty file or updates the timestamp of an existing file.

touch file.txt
13. clear Command
Definition

Clears the terminal screen for a cleaner workspace.

clear
14. whoami Command
Definition

Displays the username of the currently logged-in user.

whoami
15. date Command
Definition

Shows the current system date and time.

date
File & Directory Commands (16–30)
16. cp Command
Definition

Copies files or directories from one location to another.

cp source destination
17. mv Command
Definition

Moves or renames files and directories.

mv old_name new_name
18. rm Command
Definition

Deletes files from the system.

rm file.txt
19. rm -rf Command
Definition

Forcefully removes files and directories recursively without confirmation.

rm -rf folder_name
20. cat Command
Definition

Displays the contents of a file.




File & Directory Commands (21–30)
21. less and more Commands
Definition

These commands allow users to view file contents page by page, making it easier to read large files.

less file.txt
more file.txt
22. head Command
Definition

Displays the first few lines of a file. By default, it shows the first 10 lines.

head file.txt
23. tail Command
Definition

Displays the last few lines of a file. By default, it shows the last 10 lines.

tail file.txt
24. wc Command
Definition

Counts the number of lines, words, and characters in a file.

wc file.txt
25. find Command
Definition

Searches for files and directories within a specified location based on different criteria.

find /home -name file.txt
26. locate Command
Definition

Quickly searches for files using a pre-built database, making it faster than the find command.

locate file.txt
27. grep Command
Definition

Searches for specific text patterns within files and displays matching results.

grep "hello" file.txt
28. diff Command
Definition

Compares two files line by line and highlights the differences between them.

diff file1.txt file2.txt
29. file Command
Definition

Identifies and displays the type of a file.

file document.pdf
30. stat Command
Definition

Displays detailed information about a file, including size, permissions, ownership, and timestamps.

stat file.txt
Permissions & Ownership (31–40)
31. What Are File Permissions?
Definition

File permissions determine who can read, write, or execute a file or directory.

32. ls -l Command
Definition

Displays detailed file information, including permissions, ownership, size, and modification date.

ls -l
33. chmod Command
Definition

Changes the permissions of a file or directory.

chmod 755 file.sh
34. chown Command
Definition

Changes the ownership of a file or directory.

chown user file.txt
35. chgrp Command
Definition

Changes the group ownership of a file or directory.

chgrp developers file.txt
36. What Does Permission 777 Mean?
Definition

Permission 777 grants read, write, and execute access to all users (owner, group, and others).

chmod 777 file.txt
37. What is umask?
Definition

umask defines the default permissions assigned to newly created files and directories.

umask
38. Who is the Root User?
Definition

The root user is the superuser account with unrestricted access to all system resources and administrative functions.

39. sudo Command
Definition

Allows authorized users to execute commands with elevated administrative privileges.

sudo apt update
40. What is the Sticky Bit?
Definition

The Sticky Bit is a special permission that restricts file deletion within a shared directory to the file owner, directory owner, or root user.

chmod +t /shared_folder
Process & System Commands (41–50)
41. What is a Process?
Definition

A process is an instance of a program that is currently running in the system.

42. ps Command
Definition

Displays information about currently running processes.

ps
43. top Command
Definition

Provides real-time monitoring of system processes, CPU usage, memory usage, and other system statistics.

top
44. kill Command
Definition

Terminates a running process using its Process ID (PID).

kill 1234
45. df Command
Definition

Displays disk space usage and available storage on mounted file systems.

df -h
46. du Command
Definition

Shows the size of files and directories within a specified location.

du -sh folder_name
47. free Command
Definition

Displays information about system memory (RAM) usage and availability.

free -h
48. ifconfig / ip a Command
Definition

Displays network interface configuration and IP address information.

ifconfig

or

ip a
49. ping Command
Definition

Tests network connectivity between the local system and a remote host.

ping google.com
50. shutdown Command
Definition

Safely shuts down or powers off the system.


Additional Linux Commands (Bonus)
51. history Command
Definition

Displays a list of previously executed commands in the terminal.

history
52. man Command
Definition

Displays the manual page and detailed documentation of a command.

man ls
53. echo Command
Definition

Prints text or variable values to the terminal.

echo "Hello World"
54. uname Command
Definition

Displays system and kernel information.

uname -a
55. hostname Command
Definition

Displays or sets the system hostname.

hostname
56. which Command
Definition

Shows the location of an executable command.

which python
57. zip and unzip Commands
Definition

Compresses and extracts ZIP archives.

zip files.zip file.txt
unzip files.zip
58. tar Command
Definition

Creates and extracts archive files.

tar -cvf backup.tar folder/
tar -xvf backup.tar
59. wget Command
Definition

Downloads files directly from the internet using a URL.

wget https://example.com/file.zip
60. curl Command
Definition

Transfers data between a client and a server, commonly used for APIs.

curl https://example.com
