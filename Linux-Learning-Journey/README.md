# 🐧 Linux Learning Journey

<p align="center">
  <img src="https://img.shields.io/badge/OS-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Distribution-Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Learning%20In%20Progress-blue?style=for-the-badge" />
</p>

## 📌 About This Repository

Welcome to my **Linux Learning Journey!**

This repository is a collection of my notes, commands, practical implementations, terminal experiments, and concepts that I am learning while exploring Linux.

The goal is to develop a strong understanding of Linux fundamentals, become comfortable with command-line operations, and gradually explore system administration, server management, and DevOps concepts.

Rather than simply memorizing commands, I aim to understand **what each command does, how it works, and where it is useful in real-world environments.**

This repository will be continuously updated as I learn and practise new concepts.

---

## 🎯 Learning Objectives

- Understand Linux fundamentals and its filesystem structure.
- Become comfortable working with the Linux terminal.
- Learn file and directory management.
- Understand users, groups, permissions, and ownership.
- Explore package management and system monitoring.
- Work with environment variables and shell configuration.
- Learn archiving and compression techniques.
- Automate tasks using Cron Jobs.
- Understand basic web server concepts using NGINX.
- Explore secure remote access and file transfers using SSH and SFTP.
- Build a foundation for Linux administration and DevOps.

---

## 📚 Topics Covered

### 1. Linux Fundamentals & Basic Commands

- Introduction to Linux and Ubuntu.
- Understanding the Linux terminal.
- Navigating the filesystem.
- Absolute and relative paths.
- Creating and managing files and directories.
- Reading and editing files.
- Searching for files and directories.
- Understanding root and normal user access.

**Commands explored:**
`pwd`, `ls`, `cd`, `mkdir`, `touch`, `cat`, `cp`, `mv`, `rm`, `find`, `head`, `tail`, `less`, `history`, `clear`.

### 2. Users, Groups & Permissions

- Understanding Linux users and groups.
- Creating and managing users.
- Understanding root privileges.
- Using `sudo`.
- Understanding read, write, and execute permissions.
- Symbolic and numeric permission methods.
- Changing file ownership and group ownership.
- Managing group memberships.

**Commands explored:**
`whoami`, `id`, `groups`, `adduser`, `passwd`, `usermod`, `groupadd`, `groupdel`, `chmod`, `chown`, `chgrp`, `sudo`.

### 3. Package Management – APT

- Introduction to package management.
- Updating package information.
- Installing software packages.
- Upgrading installed packages.
- Removing and purging packages.
- Listing installed packages.

**Commands explored:**
`apt update`, `apt upgrade`, `apt install`, `apt remove`, `apt purge`, `apt autoremove`.

### 4. Process & System Monitoring

- Understanding running processes.
- Monitoring system resource usage.
- Checking memory and disk space.
- Understanding process information.

**Commands explored:**
`ps`, `ps aux`, `top`, `htop`, `free -h`, `df -h`.

### 5. Environment Variables, PATH & Bash Configuration

- Understanding shell and environment variables.
- Exploring commonly used environment variables.
- Understanding the PATH variable.
- Adding directories to PATH.
- Understanding the `.bashrc` configuration file.
- Creating custom environment variables.
- Reloading shell configurations.

**Commands explored:**
`env`, `printenv`, `echo`, `export`, `unset`, `which`, `type`, `source`, `nano ~/.bashrc`.

### 6. Linux Filesystem Hierarchy

- Understanding the Linux filesystem.
- Exploring the root directory `/`.
- Understanding important Linux directories.
- Understanding mount points.
- Introduction to filesystem types.
- Understanding how Linux represents files and devices.
- Checking disk usage and mounted filesystems.

**Directories explored:**
`/`, `/home`, `/root`, `/etc`, `/bin`, `/sbin`, `/boot`, `/dev`, `/tmp`, `/var`, `/usr`, `/mnt`, `/media`, `/opt`.

**Commands explored:**
`pwd`, `ls /`, `df -h`, `du -sh`, `mount`, `findmnt`, `lsblk`, `file`.

### 7. Archives & Compression

- Understanding archiving versus compression.
- Creating and extracting TAR archives.
- Working with TAR.GZ files.
- GZIP compression and decompression.
- ZIP and UNZIP operations.
- Introduction to BZIP2 and XZ.
- Viewing archive contents.

**Commands explored:**
`tar`, `gzip`, `gunzip`, `zip`, `unzip`, `bzip2`, `bunzip2`, `xz`, `unxz`.

### 8. Cron Jobs & Task Scheduling

- Understanding task scheduling in Linux.
- Introduction to Cron and Crontab.
- Understanding the five fields of Cron syntax.
- Working with special scheduling symbols.
- Creating and managing scheduled tasks.
- Checking Cron service status.
- Viewing Cron logs.
- Understanding recurring tasks and automation.

**Commands explored:**
`crontab -l`, `crontab -e`, `crontab -r`, `systemctl status cron`, `journalctl -u cron`.

### 9. NGINX – Web Server Fundamentals

- Introduction to web servers.
- Understanding the role of NGINX.
- Introduction to master and worker processes.
- Understanding basic NGINX configuration.
- Starting, stopping, and restarting NGINX.
- Checking service status.
- Testing NGINX configuration.
- Exploring access and error logs.

**Commands explored:**
`nginx -v`, `systemctl status nginx`, `systemctl start nginx`, `systemctl stop nginx`, `systemctl restart nginx`, `nginx -t`, `curl`.

### 10. SSH, SFTP & FileZilla

- Understanding Secure Shell (SSH).
- Connecting to remote Linux systems.
- Understanding SSH authentication.
- Introduction to SSH keys.
- Understanding SFTP.
- Secure file transfers.
- Exploring FileZilla for file transfer operations.

**Commands explored:**
`ssh`, `ssh-keygen`, `ssh-copy-id`, `sftp`, `scp`.

---

## 💻 Learning Environment

| Component | Details |
|---|---|
| Operating System | Windows 11 |
| Linux Distribution | Ubuntu |
| Environment | Windows Subsystem for Linux (WSL) |
| Shell | Bash |
| Terminal | Windows Terminal |
| Editor | Nano / Vim |
| Web Server | NGINX |
| File Transfer Client | FileZilla |

---


## 🛠️ How I Practise

1. Learn a new Linux concept.
2. Understand the commands and their purpose.
3. Execute commands in my Ubuntu terminal.
4. Observe the output and experiment with different examples.
5. Document important concepts and practical observations.
6. Revise and practise regularly.

---

## 🚀 Future Learning Goals

Some topics I plan to explore next:

- [ ] Advanced Bash Scripting
- [ ] Linux Networking Commands
- [ ] Process Management in Depth
- [ ] System Administration
- [ ] SSH Configuration and Troubleshooting
- [ ] Docker Fundamentals
- [ ] CI/CD Fundamentals
- [ ] DevOps Tools and Workflows
- [ ] Cloud and Linux Server Management

---

## 🌱 My Learning Philosophy

Learning Linux is not just about remembering commands. It is about understanding how an operating system works, how files and processes are managed, how users interact with a system, and how servers operate.

This repository represents my learning process — including experiments, mistakes, troubleshooting, notes, and improvements.

I believe in learning consistently, practising what I learn, and building strong technical foundations step by step.

**One command at a time. One concept at a time. One step closer to becoming better.**

---

<p align="center">
  <b>🐧 Learn • Practise • Experiment • Improve 🚀</b>
  <br/>
  <i>This repository is a continuous work in progress.</i>
</p>
