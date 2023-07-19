---
title: "Mastering Shell Scripting for DevOps: Automate, Streamline, Excel!"
datePublished: Wed Jul 19 2023 21:31:56 GMT+0000 (Coordinated Universal Time)
cuid: clka8o458000209mnfi1sdtxy
slug: mastering-shell-scripting-for-devops-automate-streamline-excel
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1689800862687/78cbb3fd-94bc-49c0-9f4a-9a9e7c93c113.webp
tags: linux, devops, shell, 90daysofdevops, trainwithshubham

---

# Introduction :

Welcome to our comprehensive guide on the art of shell scripting in the realm of DevOps! In this blog, we will embark on an exciting journey to explore the power and versatility of shell scripting, a fundamental skill that every DevOps engineer should possess.

### What is Kernel?

The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.

### What is Shell?

A shell is a special user program that provides an interface to the user to use operating system services. Shell accepts human-readable commands from users and converts them into something which the kernel can understand. It is a command language interpreter that executes commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or start the terminal.

### What is Linux Shell Scripting?

Shell scripting is the art of writing scripts using a command-line shell (like Bash) to automate tasks and streamline workflows in the DevOps domain. It allows DevOps engineers to create powerful, reusable scripts that execute a series of commands, perform system operations, manage deployments, and more. Shell scripts act as a bridge between human-readable commands and machine-executable instructions, making complex tasks easily reproducible and automated.

Example: Let's say you have a deployment process that involves pulling code from a Git repository, building the application, and deploying it to a production server. Instead of manually executing each step, a shell script can automate this process, ensuring consistency and efficiency in deployments.

### What is `#!/bin/bash?` can we write `#!/bin/sh` as well?

`#!/bin/bash`:

The line `#!/bin/bash` is called a "shebang" or "hashbang." It indicates the path to the shell that should be used to interpret the script. In this case, `#!/bin/bash` specifies that the script should be interpreted by the Bash shell. It is the most common shebang used for shell scripts on Linux systems.

Yes, you can write `#!/bin/sh` as well. This shebang specifies that the script should be interpreted by the system's default shell, which may be Bash or another shell compatible with the Bourne shell standard, such as Dash.

### Write a Shell Script that prints `I will complete #90DaysOofDevOps challenge`

```bash
#!/bin/bash

echo "I will complete #90DaysOfDevOps challenge"
```

### Write a Shell Script to take user input, input from arguments and print the variables.

Shell Script to take user input and print the variables:

```bash
#!/bin/bash

# Taking input from the user
read -p "Enter your name: " name
read -p "Enter your age: " age

# Printing the variables
echo "Hello, $name! You are $age years old."
```

Shell Script to take input from arguments and print the variables:

```bash
#!/bin/bash

# Accessing arguments provided when running the script
name=$1
age=$2

# Printing the variables
echo "Hello, $name! You are $age years old."
```

### Write an Example of If else in Shell Scripting by comparing 2 numbers

```bash
#!/bin/bash

num1=10
num2=20

if [ $num1 -gt $num2 ]; then
  echo "$num1 is greater than $num2"
elif [ $num1 -lt $num2 ]; then
  echo "$num1 is less than $num2"
else
  echo "Both numbers are equal"
fi
```

# Conclusion:

Throughout this blog, we explored the art of crafting powerful scripts that automate tasks, streamline workflows, and optimize system management. From user interactions to command-line arguments, you've learned how to create dynamic and interactive scripts, tailored to your unique needs.