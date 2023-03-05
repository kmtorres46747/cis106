---
name: Kyle Torres
course: cis106
semester: Spring 2023
---

# Week Report 3

## Summary of Presentations

### Introduction to Linux
* **What is an operating system?**
  An operating system provides all fundamental software features of a computer. An OS enables you to use the computer's hardware providing you the basic tools that make the computer useful. All of those feature relay on the OS's kernel. Other OS features are owed to additional programs that run atop the kernel.
* **Aside from a kernel, what other parts make an operating system?**
  * Command-Line Shells
  * Graphical User Interfaces
  * Utility and Productivity Programs
  * Libraries
* **What is a Linux distribution?**
  A complete system package using Linux. A Linux Distribution is made up of:
  * A Linux Kernel
  * Core Unix Tools
  * Supplemental Software
  * Startup Scripts
  * An installer
* **What is Ubuntu?**
  A Linux distribution that is freely available with both community and professional support.
* **Define the following terms: Open Source, Closed source, free software**
  * Open Source - The software may be distributed for a fee or free. The source code is distributed with the software.
  * Closed Source - The software is not distributed with the source code. The user is restricted from modifying the code.
  * Free software - The software is distributed with the source code. The software can be free of charge or obtained by a fee.
* **What are the 4 freedoms defined by the free software foundation?**
  * Freedom 0: Use the software for any purpose.
  * Freedom 1: Examine the source code and modify it as you see fit.
  * Freedom 2: Redistribute the software.
  * Freedom 3: Redistribute your modified software.

### The basics of Virtualization
* **What is virtualization?**
  Defined as creating virtual versions of something. Often used to let multiple OSs run on one physical machine at the same time. It also allows administrators to divide the hardware and create multiple computers inside a single physical computer. Virtualization is an old concept; however, it has gained popularity due to the availability of faster, better, and cheaper, hardware. It is one of the corner stop technologies of Cloud computing.
* **List 3 benefits of virtualization**
  1.  Allows running multiple OSs on one machine without dual booting.
  2.  Offers the ability to save the state of a machine at a given time and roll it back or forward.
  3.  Allows applications to be tested before installing them on a host machine.
* **What is a hypervisor?**
  Hypervisor/Virtual Machine Manager (VMM): Software or Hardware in charge or creating, managing and running virtual machines.
  * Type 1 (bare-metal hypervisor): Runs directly on the hardware. The hypervisor is the operating system for the physical machine. It has better performance than Type 2 because there's no host OS involved and the system is dedicated to supporting virtualization.
  * Type 2: An application that runs on top of an operating system, most commonly used in client- side virtualization. The host OS consumes resources and a host OS failure means that the VM will fail as well.
* **What is VirtualBox**
    A powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. The only professional solution that is freely available as Open Source Software under the terms of the GNU General Public License (GPL) version 3.
### Exploring Desktop Environments
* **What is a desktop environment? (Provide 3 examples)**
    A desktop environment is an implementation of the desktop metaphor of a bundle of programs running on top of a computer operating system, which shares a common GUI, sometimes described as graphical shell.
  1. GNOME
  2. KDE
  3. Cinnamon
* **List 4 common elements of desktop environments**
  1. Panels
  2. System Tray
  3. Menus
  4. File Manager
* **What is Ubuntu’s default desktop environments?**
  It is GNOME 3. GNOME was an acronym for GNU Network Object Model Environment; however, the acronym was dropped because it no longer reflected the vision of the GNOME project. It is prt of the GNU project and developed by The GNOME Project.
* **What are the official flavors of Ubuntu?**
  * Kubuntu
  * Lubuntu
  * Xubuntu
  * Ubuntu Budgie
  * Ubuntu Unity
  * Ubuntu Studio
  * Ubuntu MATE
  * Ubuntu Kylin 

### What is a Shell?
* **What is Bash?**
    A program that provides interactive access to the Linux system. It runs as a regular and is normally started whenever a user logs in into a terminal.
* **How do you access the Linux CLI?**
    Through a terminal emulator or Linux console. You can use the GUI to find either one or a keystroke typically requiring holding down Ctrl+Alt and pressing a function key (F1 through F7) for the console.
* **What is a console terminal?**
    Taking the Linux system out of graphical desktop mode and placing it in text mode. It emulates the old days of a hard-wired console terminal and is a direct interface to the Linux system.
* **What is a terminal emulator?**
    A program that allows you to access the Linux CLI.
* **Provide 3 examples of Linux commands**
    1. date - displays the current time and date
    2. free - displays the amount of free memory
    3. clear - clears the screen

### Managing Software
* **Which command is used for updating ubuntu**
    sudo apt update; sudo apt upgrade -y
* **Which command is used for installing software. Provide an example.**
    sudo apt install cowsay
* **Which command is used for removing software. Provide an example.**
    sudo apt remove toilet
* **Which command is used for searching for software. Provide an example.**
    apt search "video player"
* **Definition of the following terms:**
  * Package - Archives that contain binaries of software, configuration files, and information about dependencies.
  * Library - Reusable code that can be used by more than one function or program.
  * Repository - A large collect of software available for download.