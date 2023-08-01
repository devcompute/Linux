Last login: Mon Jan 30 21:36:16 on ttys000


 ~ % ssh Nimbus@10.211.55.2
Nimbus@10.211.55.2's password:


Last login: Mon Jan 30 19:19:50 2023 from 10.211.55.1


[Nimbus@RedHat ~]$ ls
LinuxProject


[Nimbus@RedHat ~]$ cd LinuxProject


[Nimbus@RedHat LinuxProject]$ chmod +x sysinfo.sh


[Nimbus@RedHat LinuxProject]$ ./sysinfo.sh


CPU load: 


0.10 0.03 0.01 1/185 1526


Memory usage: 
               total        used        free      shared  buff/cache   available

               
Mem:            3578         355        3097          12         277        3223


Swap:           4027           0        4027


Disk usage: 


Filesystem                    Size  Used Avail Use% Mounted on


devtmpfs                      4.0M     0  4.0M   0% /dev


tmpfs                         1.8G     0  1.8G   0% /dev/shm


tmpfs                         716M  8.9M  707M   2% /run


/dev/mapper/rhel_redhat-root   40G  1.4G   38G   4% /


/dev/vda2                    1014M  195M  820M  20% /boot


/dev/vda1                     599M  7.0M  592M   2% /boot/efi


/dev/mapper/rhel_redhat-home   20G  170M   20G   1% /home


tmpfs                         358M     0  358M   0% /run/user/1000


Netowrk usage: 


./sysinfo.sh: line 9: ifconfig: command not found


Active logged in users: 


Nimbus   tty1         2023-01-30 18:26


Nimbus   pts/0        2023-01-30 19:15 (10.211.55.2)


Nimbus   pts/1        2023-01-30 19:24 (10.211.55.1)


[Nimbus@RedHat LinuxProject]$ sudo nano /etc/hosts
[sudo] password for Nimbus: 
sudo: nano: command not found


[Nimbus@RedHat LinuxProject]$ sudo nano /etc/hosts
sudo: nano: command not found


[Nimbus@RedHat LinuxProject]$ sudo vi /etc/hosts


[Nimbus@RedHat LinuxProject]$ 
