# 🐧 Linux Runbook

<img align="center" alt="Coding" width="1200" src="https://media.giphy.com/media/LrXAkOxhUT1S0/giphy.gif">

## Linux Basics:

> What is Linux? Linux is an open-source operating system known for its flexibility and robustness. It is widely used in server environments, embedded systems, and as an alternative to proprietary operating systems like Windows and macOS. Here are some fundamental concepts and commands in Linux:

### File System Navigation

> Linux uses a hierarchical file system. You navigate through directories using commands like cd (change directory), ls (list files), and pwd (print working directory).

- Example:

```
bash
Copy code
cd /home/user/documents     # Change directory
ls                          # List files and directories
pwd                         # Print working directory
```

- Use Case: Navigating the file system to access and organize files.

### File Operations

- You can create, copy, move, and delete files using commands like touch, cp, mv, and rm.

- Example:

```
bash
Copy code
touch file.txt               # Create an empty file
cp file.txt newfile.txt      # Copy a file
mv file.txt ~/documents/     # Move a file
rm file.txt                  # Remove a file
```

- Use Case: Managing files and their content.

### Directory Operations

- You can create, remove, and manipulate directories using commands like mkdir, rmdir, and chmod.

Example:

```
bash
Copy code
mkdir myfolder               # Create a new directory
rmdir myfolder               # Remove an empty directory
chmod 755 myfolder           # Change directory permissions
```

- Use Case: Organizing and securing your file system.

### Text Processing

- Linux provides powerful text processing tools like cat, grep, sed, and awk for working with text files.

- Example:

```
bash
Copy code
cat file.txt                 # Display file content
grep "pattern" file.txt      # Search for a pattern in a file
sed 's/old/new/g' file.txt   # Replace text in a file
awk '{print $2}' file.txt    # Extract data from a file
```

- Use Case: Searching, analyzing, and transforming text data.

### Package Management

> Linux distributions have package managers like apt, yum, and dnf to install, update, and remove software packages.

- Example (using apt on Debian/Ubuntu):

```
bash
Copy code
sudo apt update              # Update package lists
sudo apt install package    # Install a package
sudo apt remove package     # Remove a package
```

- Use Case: Managing software installations and updates.

### Process Management

> You can view and control running processes using commands like ps, kill, and top.

- Example:

```
bash
Copy code
ps -ef                       # List all running processes
kill PID                     # Terminate a process by ID
top                          # Monitor system processes
```

- Use Case: Monitoring and managing system resources.

### User Management

> Linux allows you to create, modify, and delete user accounts using commands like useradd, passwd, and userdel.

- Example:

```
bash
Copy code
sudo useradd newuser         # Create a new user
sudo passwd newuser          # Set a password for the user
sudo userdel olduser         # Delete a user
```

- Use Case: Managing user access to the system.

## Resources: 

[Introduction to Linux](https://www.freecodecamp.org/news/introduction-to-linux/)
