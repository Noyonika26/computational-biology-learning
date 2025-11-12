# Linux Fundamentals Notes
These notes summarize key concepts and commands I’ve learned from **LinkedIn Learning – Learning Linux Command Line**.  
I’m documenting them here as part of my computational biology learning journey.

---

## 1. Kernels
- The **kernel** is the core of the operating system, managing communication between hardware and software.
- Users don’t interact directly with the kernel; instead, they use a **shell** or graphical interface.
- The kernel source code can be modified and recompiled to change system behavior.

---

## 2. Terminals and Desktops
- The **shell** (console) is where commands are typed and executed.
- The shell interprets commands and returns text-based results.
- Different Linux distributions provide different desktop environments — choose based on your needs.

---

## 3. Standard Tools
- Linux comes with a collection of command-line tools (e.g., `ls`, `cp`, `mv`, `cat`, `grep`).
- These tools are part of the **GNU coreutils** package or sometimes **BusyBox**.
- Many commands are consistent across Linux systems, providing flexibility and portability.

**Example commands:**
```bash
ls       # list files and directories
cd       # change directory
mkdir    # create a new directory
cp       # copy files
mv       # move or rename files

4. Software and Packages

Software is often distributed through repositories — centralized sources for downloads and updates.

Package managers install software, resolve dependencies, and handle updates automatically.

Example package managers: apt, yum, dnf.

Some systems use sandboxed packages (e.g., Flatpak, Snap) that isolate applications.

Example commands:

sudo apt update
sudo apt install package-name
sudo apt remove package-name

5. Linux File System

Everything in Linux is represented as a file (including hardware and processes).

The File Hierarchy Standard (FHS) defines directory structure and purpose.

The system is organized under a single root/directory.

Key directories:

Directory	Description
/home	Personal files for each user
/bin	Essential binaries (commands)
/sbin	System binaries
/usr	User programs and data
/etc	Configuration files
/var	Variable data (logs, caches)
/dev	Device files
/proc	Process and system info
/sys	Kernel and hardware interfaces
6. Users and System Security

Linux supports multiple users, each with their own account and permissions.

The root user has full privileges — use cautiously.

Permissions control read (r), write (w), and execute (x) access for:

User (owner)

Group

Others

Example:

ls -l
chmod 755 script.sh
chown username file.txt

