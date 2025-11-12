# Computational Biology Learning
Welcome! 👋  
This repository documents my progress as I strengthen my computational biology and data analysis skills.  
It includes practice scripts, notes, and small exercises from courses and tutorials I’m currently completing in:

- Linux / Command Line
- Git & GitHub
- Python programming
- Introductory Bioinformatics
- Data analysis & visualization

## Goals
- Build a solid foundation in computational tools used in biological research.
- Learn how to navigate and manage data using Linux and Git.
- Develop proficiency in Python for biological data analysis.
- Connect computational methods to real biological applications.

## Current Learning Resources
- [LinkedIn Learning – Learning Linux Command Line](https://www.linkedin.com/learning/)
- [LinkedIn Learning – Git Essential Training](https://www.linkedin.com/learning/)
- [Coursera – Python for Everybody (University of Michigan)](https://www.coursera.org/learn/python)
- [Coursera – Bioinformatics Specialization (UC San Diego)](https://www.coursera.org/specializations/bioinformatics)

## About Me
I’m a biology researcher transitioning into computational biology.  
My background includes molecular biology, protein analysis, and microscopy — and I’m now expanding into data-driven approaches for biological discovery.

---

🧬 *This repo is part of my continuous learning journey — feedback and suggestions are always welcome!*

## Linux Fundamentals 

1) Kernels
- Can be edited to make changes, but is not used directly 
- You need to edit the source code of the Kernel 

2) Terminals and Desktops
- Shell = console
- We type commands for the shell to run, and the shell returns text
- Pick the operating system for your needs

3) Standard tools
- There are many different commands used as part of the Ubuntu desktop installation; common ones should be memorized
- BusyBox can be used instead of GNU coreutils
- Overlapping commands amongst different installations are the same across Linux - this is what makes it so flexible

4) Software and packages
- Software repositories (a system's security updates usually come from these repositories)
- Package management software takes a software package, copies the content, and puts it where it belongs
- Software in packages is built through source code (create code -> use compiler -> create executable programs 
- Sandboxed packages: they manage software as isolated applications instead of installing through our file system
- Not all software is in all package formats discussed (you may have to use different forms of installing software)

5) Linux file system
- System made of files and directories
- FHS: File Heirarchy Standard
- "File system" - can refer to both the layout of files or the format/strategy that represents data
- Linux files and directories are organized into a single file system hierarchy, starting with the root directory represented by a single slash (/).
- Important directories include the home directory for personal files, and system directories like Bin, Sbin, Usr, ETC, and VAR for various types of system files and logs.
- The kernel creates some directories like Dev, Proc, and Sys to represent hardware and system processes.
- Everything on a Linux system, including hardware and processes, is represented as a file.

6) User and System Security
- Linux uses a multi-user model, allowing each user to have their own account with separate files and settings.
- The root account is a super user with privileges to access any file and change system-wide settings, but it's used sparingly for security reasons.
- Permissions in Linux determine which users can read, write, or execute files, and are represented by numbers or letters for user, group, and others.

