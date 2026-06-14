# Linux Task 01: Linux Environment Setup & Essential Commands

**Name:** Supriya  
**OS Used:** Kali Linux (on VirtualBox)  
**Date:** June 12, 2026

---

## Objective

To become familiar with the Linux operating system, terminal usage, navigation, and basic file management commands.

---

## Part A: Linux Installation & Verification

- **Distribution Used:** Kali Linux
- **Kernel Version:** Linux kali 6.18.12+kali-amd64
- **Username:** supriya
- **Hostname:** kali

> Screenshots: Desktop environment, terminal window, and system info captured.

---

## Part B: Basic Navigation Commands

| Command | Purpose |
|---------|---------|
| `pwd` | Prints the current working directory path |
| `ls` | Lists files and folders in the current directory |
| `ls -la` | Lists all files (including hidden) with detailed info like permissions, size, date |
| `cd` | Changes the current directory (cd alone goes to home) |
| `clear` | Clears the terminal screen |
| `history` | Shows list of previously executed commands |
| `whoami` | Displays the currently logged-in username |
| `hostname` | Shows the name of the machine/computer |

**Outputs from my system:**
- `whoami` → `supriya`
- `hostname` → `kali`
- `pwd` → `/home/supriya`

---

## Part C: Directory Management

Created the following folder structure inside `~/CyberSecurity_Lab`:

```
CyberSecurity_Lab/
├── CyberSecurity/
├── EthicalHacking/
├── Linux/
├── Networking/
└── Reports/
```

**Commands used:**
```bash
mkdir -p CyberSecurity_Lab/{Networking,Linux,CyberSecurity,EthicalHacking,Reports}
cd CyberSecurity_Lab
tree
```

---

## Part D: File Management

All commands run from inside `~/CyberSecurity_Lab`

```bash
# Create files
touch Linux/notes.txt Linux/commands.txt Linux/report.txt

# Copy a file
cp Linux/notes.txt Reports/notes_backup.txt

# Move a file
mv Linux/report.txt CyberSecurity/report.txt

# Rename a file
mv Linux/commands.txt Linux/linux_commands.txt

# Delete a file
rm Reports/notes_backup.txt
```

| Command | Purpose |
|---------|---------|
| `touch` | Creates a new empty file |
| `cp` | Copies a file from one location to another |
| `mv` | Moves or renames a file |
| `rm` | Deletes/removes a file |

---

## Part E: System Information Collection

| Info | Value |
|------|-------|
| Kernel Version | `Linux kali 6.18.12+kali-amd64 #1 SMP PREEMPT_DYNAMIC Kali 6.18.12-1kali1 (2026-02-25) x86_64 GNU/Linux` |
| Username | `supriya` |
| Hostname | `kali` |
| Current Directory | `/home/supriya/CyberSecurity_Lab` |
| Date & Time | `Friday 12 June 2026 10:35:44 PM IST` |
| System Uptime | `22:35:49 up 44 min, 1 user, load average: 0.13, 0.10, 0.11` |

**Commands used:**
```bash
uname -a
hostname
whoami
date
uptime
pwd
```

---

## Part F: Linux Research Activity

### 1. What is Linux?
Linux is a free and open-source operating system kernel created by Linus Torvalds in 1991. It is the foundation of many operating systems called "distributions" (like Ubuntu, Kali, Debian). Unlike Windows or macOS, Linux is community-driven and its source code is publicly available for anyone to view, modify, and distribute.

### 2. Why is Linux important in Cyber Security?
Linux is essential in cybersecurity because most security tools like Metasploit, Nmap, Wireshark, and Burp Suite are built for Linux. It gives users deep control over the system, supports scripting and automation, and is used on the majority of servers and cloud infrastructure that security professionals need to protect or test.

### 3. Difference between Linux and Windows

| Feature | Linux | Windows |
|---------|-------|---------|
| Cost | Free and open-source | Paid / licensed |
| Customization | Highly customizable | Limited |
| Security | More secure, less targeted by malware | More vulnerable |
| Command Line | Powerful terminal (bash/zsh) | Command Prompt / PowerShell |
| Used in | Servers, hacking, development | Desktop, gaming, office |

### 4. What is a Linux Distribution?
A Linux distribution (or "distro") is a complete operating system built on top of the Linux kernel, bundled with software, a package manager, and a desktop environment. Examples include Kali Linux (for hacking), Ubuntu (for general use), Debian, Fedora, and Parrot OS. Each distro is designed for a different purpose or audience.

### 5. Why do Ethical Hackers prefer Linux-based operating systems?
Ethical hackers prefer Linux because:
- It comes pre-installed with hundreds of hacking and security tools (especially Kali Linux)
- It offers full control over the system with root access
- It is lightweight and can run on older hardware or as a VM
- Most targets (web servers, IoT devices) run Linux, so it helps in understanding the environment
- It supports powerful scripting with bash/python for automation
- It is free, making it accessible for everyone learning cybersecurity

---

## Repository Structure

```
Linux_Task_01_Supriya/
├── README.md
├── screenshots/
│   ├── part_a_desktop.png
│   ├── part_b_commands.png
│   ├── part_c_tree.png
│   ├── part_d_files.png
│   └── part_e_sysinfo.png
└── notes.md
```

---

*Task completed as part of Cybersecurity Internship — Week 1*
