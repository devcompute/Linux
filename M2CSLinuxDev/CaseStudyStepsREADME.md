#Case study completed in Kali Linux machine.









$ mkdir LinuxDev




$ cd LinuxDev



$ ls




$ ls -l




total 0




$ ls -al
total 8
drwxr-xr-x  2 Nimbus Nimbus 4096 Jan 26 19:01 .
drwxr-xr-x 18 Nimbus Nimbus 4096 Jan 26 19:01 ..




$ pwd
/home/N***/LinuxDev




$ sudo apt update
[sudo] password for Nimbus: 
Get:1 http://kali.download/kali kali-rolling InRelease [30.6 kB]
Get:2 http://kali.download/kali kali-rolling/main arm64 Packages [18.9 MB]
Get:3 http://kali.download/kali kali-rolling/main arm64 Contents (deb) [43.1 MB]
Get:4 http://kali.download/kali kali-rolling/contrib arm64 Packages [90.8 kB]
Get:5 http://kali.download/kali kali-rolling/contrib arm64 Contents (deb) [134 kB]
Get:6 http://kali.download/kali kali-rolling/non-free arm64 Packages [188 kB]
Get:7 http://kali.download/kali kali-rolling/non-free arm64 Contents (deb) [871 kB]
Fetched 63.3 MB in 5s (11.6 MB/s)                                    
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
215 packages can be upgraded. Run 'apt list --upgradable' to see them.




$ sudo apt-get install git
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
git is already the newest version (1:2.39.0-1).
git set to manually installed.
0 upgraded, 0 newly installed, 0 to remove and 215 not upgraded.




$ git --version
git version 2.39.0




$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
Initialized empty Git repository in /home/Nimbus/LinuxDev/.git/




$ mkfifo mypipe




$ exec 3<>mypipe




$ echo "Hello, John!" >&3




$ exec 3<>mypipe




$ cat <&3
Hello, John!



exit
^C




$ touch README.md




$ nano README.md




$    







*****************************README file inside LinuxDev below:



#This will explain the theoretical steps for what Tom and Jane could use for continuing depedning on the specific IPC, UDS, and network domain sockets libraries and APIs choos>




- For IPC, Tom and Jane can use message queues, semaphores, and shared memory. The System V IPC commands of ipcs, ipcrm and msgctl can be used for creating and managing the me>
        Commands: create message = 'ipcmk -Q", remove message = "'ipcrm -Q <queue_id>'", view message status "'ipcs -q'"


  

- For UDS, use the sockets. socket(), bind(), connect(), and accept() system calls from the socket library to cerate and manage the UDS. Also necessary libraries and functions>




- For the  network domain sockets: 
         the socket()  system can be used to call and create sockets.
         connect() system call for connecting remote machines.
         send() and recv() system calls for sending and receiving data.


  

- Finally for git use:




        "git add" command to add files to staginng area.

        "git commit -m 'Message'" to save the changes to the repository.

        "git push" to push the upload changes to the remote repository.

        "git pull" to download changes.

