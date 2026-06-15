# Day 08 - Bash Basics 🚀

## Overview

Today I started learning Bash Scripting and understood how scripts can automate repetitive Linux tasks. I practiced creating scripts, printing output, using variables, taking user input, and writing simple automation scripts.

---

# 🐧 What is Bash?

Bash (Bourne Again Shell) is a command-line interpreter used to execute Linux commands and automate tasks using shell scripts.

---

# Shell Script Basics

## Creating a Script

Create a script file:

```bash
touch first_script.sh
```

Edit the script:

```bash
nano first_script.sh
```

---

## First Bash Script

```bash
#!/bin/bash

echo "Hello DevOps"
```

Run the script:

```bash
bash first_script.sh
```

Or:

```bash
chmod +x first_script.sh
./first_script.sh
```

Output:

```text
Hello DevOps
```

---

# Understanding Shebang

```bash
#!/bin/bash
```

The shebang tells Linux to execute the script using the Bash shell.

---

# Echo Command

Print text on the screen:

```bash
echo "Learning Bash Scripting"
```

Output:

```text
Learning Bash Scripting
```

---

# Variables

Store data inside variables:

```bash
name="Mayank"

echo $name
```

Output:

```text
Mayank
```

---

# User Input Using read

Take input from users:

```bash
echo "Enter your name:"
read name

echo "Welcome $name"
```

Example Output:

```text
Enter your name:
Mayank

Welcome Mayank
```

---

# Multiple Inputs

```bash
#!/bin/bash

echo "Enter your name:"
read name

echo "Enter your tool:"
read tool

echo "Welcome $name"
echo "$tool is a DevOps tool"
```

Output:

```text
Welcome Mayank
AWS is a DevOps tool
```

---

# Simple Information Script

```bash
#!/bin/bash

echo "Current User"
whoami

echo "Current Directory"
pwd

echo "Today's Date"
date
```

This script displays:

* Current user
* Current directory
* Current date and time

---

# Commands Practiced

```bash
touch
nano
chmod
bash
echo
read
whoami
pwd
date
```

---

# Key Learning

✅ What Bash is

✅ How Shell Scripts Work

✅ Creating .sh Files

✅ Shebang (#!/bin/bash)

✅ Echo Command

✅ Variables

✅ User Input (read)

✅ Running Scripts

✅ Simple Automation Scripts

---

# Learning Summary

Today I learned the fundamentals of Bash Scripting. I created my first shell script, used variables, accepted user input, and built simple scripts to automate common Linux tasks. This is the foundation for future DevOps automation and scripting.

---

# DevOps Roadmap Progress

```text
✅ Linux Commands
✅ File System
✅ Permissions
✅ Ownership
✅ Package Management
✅ Users & Groups
✅ Processes
✅ Services
✅ SSH
✅ Bash Basics

✅ Python Variables
✅ Data Types
✅ Input
✅ if/else
✅ For Loop
✅ While Loop
✅ Functions

🔜 Bash Conditions (if)
🔜 Bash Loops
🔜 Python Lists
🔜 Networking
🔜 Git
🔜 AWS
🔜 Docker
```

Day 08 Complete 🚀
