# linux-
Linux-Interview-Questions

General Concepts :

  What is Linux?
Ans:linux is karnal base opereting system

  What are the differences between Linux and Windows and Unix?
Ans:linux is open source ,strong network security
    windows is closed source ,poore network security
    unix is closed source, strong network security

  What is the Linux kernel ?
Ans:The linux kernel is the core of the linux operating system OS that manages
     hardware and software interactions

 What are the advantages of using Linux ?
Ans:The advantages of using linux is security, stability, and customization.

 What are the different types of Linux distributions ?
Ans:Linux distributions fedora,ubuntu,debian,red hat,enterprise linux,
   linux mint, Arch linux, Centos, Manjaro and Gentoo


   Explain the Linux architecture ?
Ans:The linux architecture is structured around a core component called the Kernel which directly
    interface with the hardware, while user applications and a shell interface allow users to 
    interact with the system.


  What is shell ?
Ans:A shell is a computer program that allows users to interact with an operating system OS.

#Basic Commands :

  What command is used to display the current date and time?
Ans:The date command

  What is the purpose of the ls command?
Ans:The ls command purpose is the lists files and directories in a file system

 How do you create a new directory and file in Linux?
Ans:To create a new directory in linux use the command mkdir and for a creat file in linux use touch command

 How do you copy files and directories?
Ans:To copy files or directories in linux use the cp command followed by the source file or directory path then the destination path
   where you want the copy to be placed


 What is the difference between cp and mv commands?
Ans:cp command for copies a file or directory, while mv command for moves or renames a file or directory.

 How do you delete files and directories in Linux?
Ans: To delete files and directories in linux use command rm for files and rmdir for directories

 What is the command to rename the file?
Ans: mv command for rename the file

 Which commands do you used to read the file?
Ans: cat command for the read the file

 What is the difference between head and tail command?
Ans: The difference between both the commands is head prints the lines from the beginning of the files,
    and tail prints the lines from the end of the files

  How will you list the hidden files?
Ans: ls -a command for list the hidden files

 What is the purpose of the cat command?
Ans: cat command it used for displaying, combining and manipulating text files

 What is command to check kernel name and version?
Ans: To check for kernel name command uname and for a version command uname -r

 What is the use of tree command?
Ans:The tree command displays the direcotry structure of a path or disk in a tree like
  format

 How will you check current working directory?
Ans: use the pwd command to check current working directory

 What does the alias command do?
Ans: Alias lets you create a command file name or any shell text

#Linux File System Hierarchy :

 What is the purpose of the root (/) directory in Linux?
Ans: In the linux 

 What is the difference between /bin and /sbin?
Ans:bin files are available to all users, while sbin files are usually restricted to system administrators

 What is the purpose of the /etc directory?
Ans: The purpose of the /etc directory in a linux system serves as a central repository for storing critical system
   configuration files

 What type of files are stored in the /home directory?
Ans: In the home directory strored all local users files

 What is the use of the /root directory?
Ans: The root directory is the topmost level of a file system,acting as the starting point
  from which all other files and folders branch out, essentially serving as the foundation
  for organizing all data on a computer or device

 What is the difference between a relative path and an absolute path in the Linux file system?
Ans:In a linux file system an absolute path is a complete file location starting from the root directory
   (/) specifying every directory leadingto a specific file while a relative path describes a file
    location relative to the current working directory

 How can you check the disk usage of a specific directory?
Ans: To check the disk usage of a specific directory use the du command followed by the directory
     path you want to analyze

 What is the default mount point for external devices in Linux?
Ans: In linux the default mount point for external devices like USB drives is typically /media

#Vim editor :

What is Vim editor?
Ans: Vim is a free opensource text editor that's available 
  on many platforms 

What are the different modes in Vim?
Ans: command mode,
     insert mode,
     normal mode,
     execute mode and
     visual mode

 How do you switch between insert mode and command mode?
Ans: To switch between insert mode and command mode press the Esc key once

 By default which mode get open when you use the vim editor?
Ans: Normal mode

 How do you copy and paste text in Vim?
Ans: You can copy with the y (yank) command and paste with p (put)

 How do you delete a line in Vim?
Ans: The command to delete is d. you can move to the beginning of
   the line,press v,move to the end of the line,and press d.

 How do you undo and redo changes in Vim?
Ans: Vim undo feature allows you to reverse unwanted changes with the u command and restore them using Ctrl +r.

How do you exit Vim without saving changes?
Ans: You want to exit vim without saving chages use the :q! command

 How do you exit Vim with saving changes?
Ans: If you want to save your changes and exit vim you can use the :wq! command

How do you search for a specific word or pattern in a file?
Ans:

How do you perform a search and replace in Vim?
Ans:
How do you move to the beginning or end of a line in Vim?
Ans:

How do you enable line numbers in Vim?
Ans:

What is the use of visual mode and how will you open it?
Ans:
#User Management :

 How do you create a new user in Linux?
Ans: To create a new user in linux you can use useradd and adduser command

 What is the purpose of the /etc/passwd file?
Ans: The purpose of /etc/passwd file is store a user information

 How do you delete a user in Linux?
Ans: To delete a user in linux you can use userdel command

 How do you modify user information in Linux?
Ans: we can modify user information in linux use usermod command

 What is the purpose of the /etc/shadow file?
Ans:The purpose of the /etc/shadow file stores encrypted passwords and related information user account

 How do you change a user's password in Linux?
Ans: passwd command use for change a user password in linux

 What is the command to list all users in Linux?
Ans:To list all user in linux you can use the command cat/etc/passwd

 How do you lock and unlock a user account?
Ans: To lock user you can use usermod -L and to unlock user you can use usermod -U command

 How do you switch to another user in Linux?
Ans:To switch to another user in linux you can use su command

 How do you view information about the currently logged-in user?
Ans:To view information about the currently logged in user you can use who and w command

 What is the purpose of the /etc/skel directory? 
Ans: The purpose of the /etc/skel directory servees as a template for a new user's home directory

 How do you view and modify a user's account expiration?
Ans:To you view and modify a user's account expiration in active directory you can use powershell cmdlets like GET-ADUser to 
    view and Set ADAccount Expiration to modify the expiration date
    
What is the meaning of minimum, maximum and warning days of user password?
Ans: Maximum days How many days the password is active before it expires.Minimum days How many days a password must be active
     before it can be changed by a user.warning days The number of days a warning is issued to the user before an impending password expiry.

     
#Group Management :

What is a group in Linux, and why is it used?
Ans: In linux agroup is a collection of users who share the same access rights to files and system resources

How do you create a new group in Linux?
Ans:To create a new group in linux you can use groupadd command

How do you delete a group in Linux?
Ans:To delete a group in linux use the groupdel command

What is the purpose of the /etc/group file?
Ans:The purpose of the /etc/group file is store group releted information

How do you add a user to a group?
Ans:To add a user to a group you can use gpasswd -a command

How do you remove a user from a group?
Ans: To remove a user from a group you can use 

What is a primary group and a supplementary group?
Ans:

How do you change a user's primary group?
Ans:

How do you view the groups a user belongs to?
Ans:

How do you change group ownership of a file or directory?
Ans: To change group ownership of file or directory you can use chgrp command

How do you change the password of group?

#File Permissions and Access Control :

What is the difference between user, group, and others in file permissions?
Ans:

What is the meaning of Read, Write and execute permission over file and directory?
Ans:Read meanning is you can read and view file
    Write meaning is you can write and delete 
    execute meaning is you can run a file
    
How do you change ownership of a file or directory?
Ans: To change ownership of a file or directory you can use chown command

How do you view file permissions in Linux?
Ans:To view file permission in file you can use ls-l command

How may types files in Linux system?
Ans: There is seven types files in linux system 
      Normal file/Regular File 
      Directory d 
      Link file l 
      Block Device File 
      Character Device File 
      Socket File  
      Normal Pipe File 
      
How do you set permissions using chmod with examples?
Ans: set permissions use chmod 644

How many type of link files in Linux system?
Ans: There is two type of link files in linuux system hardlink and softlink

What is the difference between hard link and Soft link?
Ans:Hardlink contain actual data from the file
    Softlink contain path of original file and not the 
    actual data
    
#Archive and Compression :

What is the purpose of archive?
Which tool do you used for archiving the files?
What is compression?
Which tools do you used for compression the data?
How will you archive and compress the data in single command?

#Scheduling task :

What is task scheduling, and why is it important?
Which tool do you used for scheduled the task non-periodically?
What is crontab, and How will you use it?
What are the fields of crontab?
How do you list the crontab jobs?

#Search and Filter utility in Linux :

What is the use of sort command?
What is the use of uniq command?
What is the use of wc command?
How will you find the path of file or directory in Linux file system?
What is the use of grep command?

#Process management :

How do you view running processes in Linux?
What is the difference between foreground and background processes?
How do you terminate a process in Linux?
What is a daemon in Linux?
What are the shell jobs?
What are the process state in Linux?

#Networking:

How do you check your IP address in Linux?
How do you test network connectivity?
What is SSH, and how is it used?
What is the difference between static IP and dynamic IP?
