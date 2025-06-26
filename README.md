 Task 1: Understanding Linux- Write a short paragraph on what Linux is.- Mention at least 3 Linux distributions and their use cases

 ans:
 Linux is an open-source operating system based on the Unix architecture. It manages hardware resources and provides a platform for running software applications. Because it is open-source, anyone can view, modify, and distribute its source code. Linux is widely used in servers, desktops, mobile devices, and embedded systems due to its stability, security, and flexibility.

 Ubuntu: A user-friendly Linux distribution popular for desktops and servers. It’s ideal for beginners and widely used for web servers and cloud computing.

CentOS / Rocky Linux: These are enterprise-grade distributions often used for servers, especially in business environments, known for long-term support and stability.

Raspberry Pi OS: A lightweight distribution designed specifically for Raspberry Pi devices, used mainly in education, DIY projects, and embedded systems.

 Task 2: System Navigation Basics- Commands: pwd, ls, cd, clear, echo, whoam

 ans:pwd
Purpose: Print Working Directory – shows the full path of your current directory.
ls
Purpose: List files and directories in the current directory.

cd
Purpose: Change directory.

clear
Purpose: Clear the terminal screen.
 echo
Purpose: Display a line of text or a variable’s value.
 Exercise:
 1. Navigate to the home directory.
 2. List all hidden files.
 3. Create a file called intro.txt and write a line into it

 4. ans:
 5. ![Image](https://github.com/user-attachments/assets/e0cb543c-f3f8-4e0c-bd63-7a700ea8dc72)

 6.  Page 2: File and Directory Operations
 Task 1: File Management- Commands: touch, mkdir, rm, rmdir, mv, cp, cat, nano, less

ans:
touch
Create an empty file or update timestamp.
mkdir
Create a directory.
 rm
Remove a file
rmdir
Remove an empty directory.
mv
Move or rename files/directories.
cp
Copy files or directories.
cat
Display contents of a file.
nano
Open a simple text editor in the terminal.
less
View long files page-by-page
Task 2: Exercises- Create a directory linux_practice.- Inside it, create a file info.md, add some content, and then copy it as info_backup.md.- Move the info.md to a folder achives
ans:
![Image](https://github.com/user-attachments/assets/ebe52352-d752-4f62-a7a4-21a6fe4333f9)

 Page 3: File Permissions
 Task 1: Understanding File Permissions- Explain file permission notations (e.g., -rwxr-xr--).- Commands: chmod, chown,
 ans:
  Page 3: File Permissions
 Task 1: Understanding File Permissions- Explain file permission notations (e.g., -rwxr-xr--).- Commands: chmod, chown,
 chmod – Change file permissions
 chown – Change file owner

 Task 2: Exercises- Create a script file test.sh and give it execute permission.- Change the ownership of a file to a different user (use sudo if needed).
ans:








 Page 4: Users and Groups
 Task 1: Users and Group Management- Commands: adduser, usermod, passwd, groups, id, su, sud

ans:adduser
Purpose: Add a new user (and create their home directory).
usermod
Purpose: Modify a user’s account (e.g., add to a group).
passwd
Purpose: Change a user’s password.
groups
Purpose: Show groups a user belongs to
id
Purpose: Show user ID (UID), group ID (GID), and groups
sudo
Purpose: Run a command with root (admin) privileges
 Task 2: Exercises- Create a user called intern1 and a group called interns.- Add intern1 to interns group.- Set a password for the 

 ans:![Image](https://github.com/user-attachments/assets/5f688d4b-8c25-4c4d-96d2-f7353e3cb190)
 Page 5: Package Management
 Task 1: Package Installations- Difference between apt, yum, and dnf.- Commands: sudo apt update && sudo apt upgrade, sudo apt install <package
 ans:Linux distributions use different package managers to install, update, and manage software packages. The three commonly used package managers are apt, yum, and dnf.

apt (Advanced Package Tool) is used in Debian-based systems such as Ubuntu and Linux Mint. It allows users to install, update, and remove software packages with .deb extensions. It is user-friendly and widely supported.

yum (Yellowdog Updater Modified) is used in older Red Hat-based systems like CentOS 7 and RHEL 7. It manages .rpm packages and resolves software dependencies during installations.

dnf (Dandified YUM) is the modern replacement for yum, introduced in Fedora and newer versions of CentOS and RHEL (8 and above). It is more efficient and faster, with better dependency management and performance.
sudo: Runs the command as a superuser (admin).

apt: The package manager.

update: Updates the package list.
sudo apt install <package-name>
What it does:
Installs a specific software package.

 Task 2: Exercises- Install curl, git, and tree on your system.- Remove tree afterward using a package manager
 ans:
![Image](https://github.com/user-attachments/assets/a914005a-0b6b-43c9-881c-cb80bd508b76)
![Image](https://github.com/user-attachments/assets/eac682ff-fd8f-43e6-a536-c0fba79130df)
 Page 6: File Searching and Redirection
 Task 1: Search and Filters- Commands: find, grep, locate, head, tail, sort, w
 ans:find
Purpose: Search for files and directories in a directory hierarchy.
grep
Purpose: Search for specific patterns or text inside files.
locate
Purpose: Quickly find file locations (uses a prebuilt index).
head
Purpose: Display the first few lines of a file (default is 10).
tail
Purpose: Display the last few lines of a file (default is 10).
sort
Purpose: Sort lines of a file or input.

Task 2: Redirection- Usage of >, >>, <, 
ans:> (Output Redirection)
Purpose: Redirects standard output to a file, overwriting the file if it exists.
>> (Append Output Redirection)
Purpose: Redirects output to a file, appending to the end of the file (does not overwrite).
< (Input Redirection)
Purpose: Takes input from a file instead of the keyboard.

 Exercise:- Create a file with multiple lines.- Use grep to find a keyword.- Pipe output of ls -l into grep and filter .sh files
 ans:













