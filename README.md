# linux-basics


## 1. What is Linux?
- Linux is an open-source operating system that allows users to manage hardware and software resources efficiently.

## 2. What is a Kernel?
- The kernel is the core component of an operating system that acts as a bridge between hardware and software.

## 3. Difference Between Linux and Windows
- Linux is open-source and free to use, whereas Windows is a proprietary, paid, and closed-source operating system.

## 4. What is a Linux Distribution (Distro)?
- A Linux distribution is a packaged version of Linux that includes the kernel, system utilities, and software applications. Examples include Ubuntu, CentOS, and Fedora.

## 5. What is a Shell?
- A shell is a command-line interface that enables communication between the user and the operating system.

## 6. What is CLI?
- CLI (Command Line Interface) is a text-based interface used to interact with the operating system through commands.

## 7. pwd Command
- Displays the absolute path of the current working directory.
pwd

## 8. ls Command
- Lists files and directories present in the current location.

## 9. cd Command
- Changes the current working directory.
cd directory_name

## 11. mkdir Command
- Creates a new directory.
mkdir new_folder

## 11. rmdir Command
- Removes an empty directory.
rmdir folder_name

## 12. touch Command
- Creates a new empty file or updates the timestamp of an existing file.
touch file.txt

## 13. clear Command
- Clears the terminal screen for a cleaner workspace.
clear

## 14. whoami Command
- Displays the username of the currently logged-in user.
whoami

## 15. date Command
- Shows the current system date and time.
date

# File & Directory Commands (16–30)

## 16. cp Command
- Copies files or directories from one location to another.
cp source destination

## 17. mv Command
- Moves or renames files and directories.
mv old_name new_name

## 18. rm Command
- Deletes files from the system.
rm file.txt

## 19. rm -rf Command
- Forcefully removes files and directories recursively without confirmation.
rm -rf folder_name

## 20. cat Command
- Displays the contents of a file.


# File & Directory Commands (21–30)

## 21. less and more Commands
- These commands allow users to view file contents page by page, making it easier to read large files.
less file.txt
more file.txt

## 22. head Command
- Displays the first few lines of a file. By default, it shows the first 10 lines.
head file.txt

## 23. tail Command
- Displays the last few lines of a file. By default, it shows the last 10 lines.
tail file.txt

## 24. wc Command
- Counts the number of lines, words, and characters in a file.
wc file.txt

## 25. find Command
- Searches for files and directories within a specified location based on different criteria.
find /home -name file.txt

## 26. locate Command
- Quickly searches for files using a pre-built database, making it faster than the find command.
locate file.txt

## 27. grep Command
- Searches for specific text patterns within files and displays matching results.
grep "hello" file.txt

## 28. diff Command
- Compares two files line by line and highlights the differences between them.
diff file1.txt file2.txt

## 29. file Command
- Identifies and displays the type of a file.
file document.pdf

## 30. stat Command
- Displays detailed information about a file, including size, permissions, ownership, and timestamps.
stat file.txt

# Permissions & Ownership (31–40)

## 31. What Are File Permissions?
- File permissions determine who can read, write, or execute a file or directory.

## 32. ls -l Command
- Displays detailed file information, including permissions, ownership, size, and modification date.
ls -l

## 33. chmod Command
- Changes the permissions of a file or directory.
chmod 755 file.sh

## 34. chown Command
- Changes the ownership of a file or directory.
chown user file.txt

## 5. chgrp Command
- Changes the group ownership of a file or directory.
chgrp developers file.txt

## 36. What Does Permission 777 Mean?
- Permission 777 grants read, write, and execute access to all users (owner, group, and others).
chmod 777 file.txt

## 37. What is umask?
- umask defines the default permissions assigned to newly created files and directories.
umask

## 38. Who is the Root User?
- The root user is the superuser account with unrestricted access to all system resources and administrative functions.

## 39. sudo Command
- Allows authorized users to execute commands with elevated administrative privileges.
sudo apt update

## 40. What is the Sticky Bit?
- The Sticky Bit is a special permission that restricts file deletion within a shared directory to the file owner, directory owner, or root user.
chmod +t /shared_folder

# Process & System Commands (41–50)

## 41. What is a Process?
- A process is an instance of a program that is currently running in the system.

## 42. ps Command
- Displays information about currently running processes.
ps

## 43. top Command
- Provides real-time monitoring of system processes, CPU usage, memory usage, and other system statistics.
top

## 44. kill Command
- Terminates a running process using its Process ID (PID).
kill 1234

## 45. df Command
- Displays disk space usage and available storage on mounted file systems.
df -h

## 46. du Command
- Shows the size of files and directories within a specified location.
du -sh folder_name

## 47. free Command
- Displays information about system memory (RAM) usage and availability.
free -h

## 48. ifconfig / ip a Command
- Displays network interface configuration and IP address information.
ifconfig
or
ip a

## 49. ping Command
- Tests network connectivity between the local system and a remote host.
ping google.com

## 50. shutdown Command
- Safely shuts down or powers off the system.

# Additional Linux Commands (Bonus)

## 51. history Command
- Displays a list of previously executed commands in the terminal.
history

## 52. man Command
- Displays the manual page and detailed documentation of a command.
man ls

## 53. echo Command
- Prints text or variable values to the terminal.
echo "Hello World"

## 54. uname Command
- Displays system and kernel information.
uname -a

## 55. hostname Command
- Displays or sets the system hostname.
hostname

## 56. which Command
- Shows the location of an executable command.
which python

## 57. zip and unzip Commands
- Compresses and extracts ZIP archives.
zip files.zip file.txt
unzip files.zip

## 58. tar Command
- Creates and extracts archive files.
tar -cvf backup.tar folder/
tar -xvf backup.tar

## 59. wget Command
- Downloads files directly from the internet using a URL.
wget https://example.com/file.zip

### 60. curl Command
- Transfers data between a client and a server, commonly used for APIs.
curl https://example.com
