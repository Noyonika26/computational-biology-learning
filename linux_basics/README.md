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


## 4. Software and Packages
- Software is often distributed through repositories — centralized sources for downloads and updates.
- Package managers install software, resolve dependencies, and handle updates automatically.
- Example package managers: apt, yum, dnf.
- Some systems use sandboxed packages (e.g., Flatpak, Snap) that isolate applications.

Example commands:

sudo apt update
sudo apt install package-name
sudo apt remove package-name

## 5. Linux File System
- Everything in Linux is represented as a file (including hardware and processes).
- The File Hierarchy Standard (FHS) defines directory structure and purpose.
- The system is organized under a single root/directory.
- Key directories:

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

## 6. Users and System Security
- Linux supports multiple users, each with their own account and permissions.
- The root user has full privileges — use cautiously.
- Permissions control read (r), write (w), and execute (x) access for: User (owner, Group, Others

---

# Getting Started with Linux

## 1. Choosing a Linux distribution
- Linux distributions, or distros, are variations of the Linux operating system, each with unique tools and configurations.
- All distros share the Linux kernel but differ in software packages, support duration, and target use cases (e.g., servers, desktops, embedded devices).
- Popular desktop distros include Ubuntu, Debian, and Linux Mint, while server distros include Red Hat Enterprise Linux and Ubuntu Server.
- Knowing the differences between distros is important, especially when following tutorials or seeking help.
- Ubuntu is broadly used -> recommended for beginners

## 2. Planning your system
- Decide on your goals for using Linux to choose the appropriate distribution and setup.
- Consider whether you need a desktop environment or just command-line access.
- Options for running Linux include virtual machines, native installs, live boot environments, and cloud services.

## 3. Installing Ubuntu in VirtualBox
- VirtualBox Installation: Download and install VirtualBox on your operating system.
- Ubuntu Download: Download the Ubuntu Desktop Linux ISO image from ubuntu.com.
- Virtual Machine Setup: Create a new virtual machine in VirtualBox, allocate memory, CPUs, and set up the virtual hard disk.
- Ubuntu Installation: Install Ubuntu in the virtual machine by following the prompts and configuring settings like language, keyboard, and user account.
- Post-Installation: Restart the virtual machine, log in, and start exploring your new Linux environment.

## 4. Using Ubuntu Desktop
- Graphical Interface: Learn to navigate the GNOME desktop, the default for Ubuntu Desktop Linux, and use the app selector menu to find and install applications.
- System Settings: Access and modify system settings, such as display resolution and network settings, through the Settings application.
- File System Navigation: Browse the file system using the Files app, starting with your home directory and exploring other locations.
- Terminal Usage: Open the Terminal application to work with the command-line interface, using basic commands like cd, mv, cp, and the man command for help documentation.

## 5. Building your skills 
- 
