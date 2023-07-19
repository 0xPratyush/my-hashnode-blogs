---
title: "🐧🎬 Mastering Linux Basics: Essential Commands for Productive DevOps 🚀💻"
datePublished: Wed Jul 19 2023 20:33:09 GMT+0000 (Coordinated Universal Time)
cuid: clka6kivk000209md93z84ftl
slug: mastering-linux-basics-essential-commands-for-productive-devops
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1689797540059/aeea2318-f935-4358-97c8-d65d9668ca11.png
tags: linux, devops, linux-for-beginners, 90daysofdevops, trainwithshubham

---

# Introduction :

In this blog, we'll unravel the power of basic Linux commands that serve as the building blocks of seamless and automated operations. 🧱💡 From exploring the content of files to manipulating directories, we'll equip you with the essential tools to navigate the Linux terminal with confidence and finesse. 📜🔧

# **Mostly Used Commands in DevOps**:

Here are some of the most commonly used basic Linux commands in the world of DevOps:

1. `ls`: Lists files and directories in the current directory.
    
2. `pwd`: Prints the present working directory.
    
3. `cd`: Changes the current directory.
    
4. `mkdir`: Creates a new directory.
    
5. `rm`: Removes files or directories.
    
6. `cp`: Copies files or directories.
    
7. `mv`: Moves or renames files or directories.
    
8. `touch`: Creates an empty file or updates the timestamp of an existing file.
    
9. `cat`: Concatenates and displays the content of a file.
    
10. `grep`: Searches for a pattern in a file or input stream.
    
11. `find`: Searches for files and directories in a directory hierarchy.
    
12. `chmod`: Changes file permissions.
    
13. `chown`: Changes file ownership.
    
14. `wget`: Downloads files from the internet.
    
15. `curl`: Transfers data to or from a server using various protocols.
    
16. `ssh`: Securely connects to a remote server.
    
17. `top`: Monitors system processes and resource usage.
    
18. `ps`: Displays information about running processes.
    
19. `netstat`: Displays network statistics and connections.
    
20. `ifconfig` or `ip`: Configures and displays network interfaces.
    
21. `ping`: Tests network connectivity to a host.
    
22. `traceroute`: Traces the route packets take to reach a host.
    
23. `systemctl`: Controls system services in systemd-based Linux distributions.
    

No DevOps journey is complete without version control. Git, the industry-standard version control system, enables seamless collaboration and code management. Learn how to clone repositories, create branches, commit changes, and work with remote repositories using `git` commands.

# Some use cases of the commands:

1. **To view what's written in a file:**
    
    Command: `cat filename`
    
    Description: `cat` command is used to display the content of a file on the terminal.
    
2. **To change the access permissions of files:**
    
    Command: `chmod permissions filename`
    
    Description: `chmod` command is used to change the file permissions. "permissions" can be represented in numeric (e.g., 755) or symbolic (e.g., u+rwx) form.
    
3. **To check which commands you have run till now:**
    
    Command: `history`
    
    Description: `history` command displays a list of previously executed commands in the terminal.
    
4. **To remove a directory/Folder:**
    
    Command: `rm -r directory_name`
    
    Description: `rm` command is used to remove files or directories. The `-r` option is used to remove directories recursively.
    
5. **To create a fruits.txt file and to view the content:**
    
    Commands:
    
    ```bash
    echo "Apple
    Mango
    Banana
    Cherry
    Kiwi
    Orange
    Guava" > fruits.txt
    cat fruits.txt
    ```
    
    Description: The first command creates a file named fruits.txt and adds the listed fruits to it. The second command displays the content of the file on the terminal.
    
6. **To add content in devops.txt (One in each line):**
    
    Command: `echo -e "Apple\nMango\nBanana\nCherry\nKiwi\nOrange\nGuava" > devops.txt` Description: The `echo` command with the `-e` option is used to enable interpretation of backslash escapes. It adds the fruits one in each line to the devops.txt file.
    
7. **To show only the top three fruits from the file:**
    
    Command: `head -n 3 devops.txt`
    
    Description: `head` command is used to display the beginning lines of a file. The `-n 3` option shows only the first three lines.
    
8. **To show only the bottom three fruits from the file:**
    
    Command: `tail -n 3 devops.txt`
    
    Description: `tail` command is used to display the ending lines of a file. The `-n 3` option shows only the last three lines.
    
9. **To create another file Colors.txt and to view the content:**
    
    Commands:
    
    ```bash
    echo "Red
    Pink
    White
    Black
    Blue
    Orange
    Purple
    Grey" > Colors.txt
    cat Colors.txt
    ```
    
    Description: The first command creates a file named Colors.txt and adds the listed colours to it. The second command displays the content of the file on the terminal.
    
10. **To find the difference between fruits.txt and Colors.txt file:**
    
    Command: `diff fruits.txt Colors.txt` Description: `diff` command is used to compare files line by line and display the differences, if any, between them. If there is no output, it means the files are identical.
    

Please note that some commands may require appropriate permissions to be executed successfully, especially when dealing with file removal or modification operations.

# Conclusion: 🎉🎉

These are just a few of the many commands you'll encounter in the DevOps world. Mastering these commands will empower you to navigate your way through various DevOps tasks with ease and efficiency. Happy scripting and automating! 🚀💻