# 🐧 Linux Projects

A collection of **Linux administration and Shell Scripting projects** created to practice Linux system administration, file permissions, user/group management, environment variables, and system verification.

This repository contains practical Linux exercises designed around common tasks performed by **Linux System Administrators, Cloud Engineers, and DevOps Engineers**.

## 📌 Project Overview

The purpose of this repository is to build hands-on experience with:

- **Linux System Administration**
- **Shell Scripting**
- **User & Group Management**
- **File Permissions**
- **UMASK**
- **Environment Variables**
- **System Information & Verification**
- **Linux Command-Line Operations**

## 🛠️ Technologies & Tools

- **Linux**
- **Bash / Shell Scripting**
- **Linux CLI**
- **File & Directory Management**
- **User & Group Administration**
- **Linux Permissions**

## 📂 Repository Structure

```text
Linux/
│
├── U4Mask.sh.jpg
├── UGID.sh.jpg
├── Var.sh file.jpg
├── verify.sh.jpg
├── 7aad6be1-0bfa-4fc8-891f-11d9e6affb7d.jpg
└── README.md
```

The repository currently contains practical script examples and screenshots demonstrating Linux administration tasks.

## 🔐 Topics Covered

### 1. Linux File Permissions

Understanding and managing:

```text
r → Read
w → Write
x → Execute
```

Common commands:

```bash
ls -l
chmod
chown
chgrp
```

Example:

```bash
chmod 755 script.sh
```

---

### 2. UMASK

The repository includes a practical exercise related to **UMASK**.

UMASK controls the default permissions assigned when new files and directories are created.

Check the current UMASK:

```bash
umask
```

Set a temporary UMASK:

```bash
umask 022
```

---

### 3. User & Group Management

Linux user and group administration is an important part of server management.

Common commands:

```bash
useradd
usermod
userdel
groupadd
groupmod
groupdel
id
```

Check a user's UID and GID:

```bash
id username
```

Check the current user:

```bash
whoami
```

---

### 4. Environment Variables

Environment variables provide configuration information to processes and applications.

View environment variables:

```bash
env
```

Display a specific variable:

```bash
echo $PATH
```

Create a variable:

```bash
VAR="Linux"
```

Export a variable:

```bash
export VAR="Linux"
```

---

### 5. Shell Scripting

Shell scripts are used to automate repetitive Linux administration tasks.

Basic script structure:

```bash
#!/bin/bash

echo "Hello, Linux!"
```

Make a script executable:

```bash
chmod +x script.sh
```

Run the script:

```bash
./script.sh
```

---

## ⚙️ Running the Scripts

Clone the repository:

```bash
git clone https://github.com/Shibisaran/Linux.git
```

Move into the repository:

```bash
cd Linux
```

Give execution permission to a shell script:

```bash
chmod +x script.sh
```

Run it:

```bash
./script.sh
```

> **Note:** Some files in the repository are stored as `.jpg` screenshots of scripts rather than executable `.sh` files.

## 🧪 Practical Linux Skills

This repository demonstrates practical knowledge of:

| Area | Skills |
|---|---|
| **Linux** | Command-line administration |
| **Shell** | Bash scripting |
| **Users** | User creation and management |
| **Groups** | Group administration |
| **Permissions** | chmod, chown, chgrp |
| **Security** | UMASK and access permissions |
| **Variables** | Environment variables |
| **Automation** | Shell scripts |
| **Troubleshooting** | System verification |

## ☁️ Relevance to Cloud & DevOps

Linux is a fundamental technology for cloud and DevOps environments.

The skills practiced in this repository are directly applicable to:

- **Linux cloud servers**
- **Application deployment**
- **Server administration**
- **Bash automation**
- **Security configuration**
- **Troubleshooting**
- **DevOps workflows**

For example, when working with an AWS EC2 Linux instance, administrators commonly use the same Linux concepts to investigate:

```text
Application
     │
     ▼
Linux Server
     │
     ├── Users & Groups
     ├── File Permissions
     ├── Processes
     ├── Environment Variables
     ├── Logs
     └── Shell Scripts
```

## 🎯 Learning Objectives

The project was created to strengthen practical knowledge of:

- Linux command-line operations
- Bash scripting
- User and group administration
- File and directory permissions
- UMASK configuration
- Environment variables
- Linux troubleshooting
- Server administration fundamentals

## 🚀 Future Improvements

Planned improvements could include:

- Add executable `.sh` files instead of only screenshots
- Add automated system-information scripts
- Add process-management scripts
- Add disk and memory monitoring scripts
- Add log-analysis scripts
- Add backup automation
- Add service-monitoring scripts
- Add cron-job automation
- Add Linux security-hardening scripts

## 👨‍💻 Author

**Shibisaran M**

GitHub:  
https://github.com/Shibisaran

Repository:  
https://github.com/Shibisaran/Linux

---

⭐ **If you find this repository useful, feel free to star it!**
