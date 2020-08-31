---
layout: post
title: Basic Linux Commands
feature-img: "https://i.imgur.com/4KpVtQF.png"
date: 31 August 2020
---
## Introduction
Linux commands are issued to a computer program called
`shell`. The shell enables us to send commands to the
computer and receive output. It is also referred to as
the terminal or command line.

Some computers include a default Unix Shell program.
The steps below describe some methods for identifying
and opening a Unix Shell program, if you already have
one installed. There are also options for identifying
and downloading a Unix Shell program, a Linux/UNIX
emulator, or a program to access a Unix Shell on a
server.

## Setup
You need to download some files to follow this lesson.
Download [data-shell.zip](http://swcarpentry.github.io/
shell-novice/data/data-shell.zip) and move the file to
your Desktop. Unzip/extract the file. You should end up
with a new folder called data-shell on your Desktop.
Open a terminal. If you’re not sure how to open a
terminal in your operating system, see the instructions
below. In the terminal type `cd` then press the 'Return'
key. This step will make sure you start with your home
folder as your working directory. In the lesson, you will
find out how to access the data files in this folder.

### [Windows](#tab/windows)
Computers with Windows operating systems do not
automatically have a Unix Shell program installed.
In this lesson, we encourage you to use an emulator
included in Git for Windows, which gives you access
to both Bash shell commands and Git.

Once installed, you can open a terminal by running
the program Git Bash from the Windows start menu.

Other solutions are available for running Bash commands
on Windows. There is now a Bash shell command-line tool
available for Windows 10. Additionally, you can run Bash
commands on a remote computer or server that already has
a Unix Shell, from your Windows machine. This can usually
be done through a Secure Shell (SSH) client. One such
client available for free for Windows computers is PuTTY.
See the reference below for information on installing and
using PuTTY, using the Windows 10 command-line tool, or
installing and using a Unix/Linux emulator.

*Reference*
	* [Git for Windows](https://gitforwindows.org/) - Recommended
*For advanced users, you may choose one of the following alternatives:*   

  * [Install the Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
  * [Using a Unix/Linux emulator (Cygwin) or Secure Shell (SSH) client (Putty)](http://faculty.smu.edu/reynolds/unixtut/windows.html)
Please note that commands in the Windows Subsystem for Linux (WSL) or Cygwin may differ slightly from those shown in the lesson or presented in the workshop.       
### [macOS](#tab/macOS)
For a Mac computer running macOS Mojave or earlier
releases, the default Unix Shell is Bash. For a Mac
computer running macOS Catalina or later releases,
the default Unix Shell is `Zsh`. Your default shell is
available via the Terminal program within your Utilities
folder.       
           
To open Terminal, try one or both of the following:

  * In Finder, select the Go menu, then select Utilities. Locate Terminal in the Utilities folder and open it.
  * Use the Mac `Spotlight` computer search function. Search for: `Terminal` and press 'Return'.

To check if your machine is set up to use something other than Bash, type `echo $SHELL` in your terminal
window.
           
If your machine is set up to use something other than Bash, you can run it by opening a terminal and typing
`bash`.

  * [How to Use Terminal on a Mac](http://www.macworld.co.uk/feature/mac-software/how-use-terminal-on-mac-3608274/)

#### [Linux](#tab/Linux)
The default Unix Shell for Linux operating systems is
usually Bash. On most versions of Linux, it is accessible
by running the [Gnome Terminal](https://help.gnome.org/users/gnome-terminal/stable/) or [KDE Konsole](https://konsole.kde.org/) or [xterm](https://en.wikipedia.org/wiki/Xterm), which can be found via the applications menu or the
search bar. If your machine is set up to use something
other than Bash, you can run it by opening a terminal
and typing bash.        


1. [Introducing the Shell](#TheShell)
2. [Navigating Files and Directories](#FilesDirectories)
3. [Pipes and Filters](#PipesFilters)
4. [Finding Things](#FindThings)

