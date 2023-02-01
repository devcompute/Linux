#Work below is done in Kali Linux.








$ mkdir LinuxM1C3
$ cd LinuxM1C3
$ whoami
Nimbus
$ ls
$ touch README.md
$ nano README.md
$ nano README.md
$ 


  GNU nano 7.1                                                                        README.md                                                                                 

#Steps in order to complete case study of connecting Tom and Tina`s laptops.


1. Connect the laptops using a LAN cable or wireless connection.
2. Open terminal and run the command ifconfig (or ipconfig if necessary) ob both machines to see if the subnets are the same for them.
3. Ping each other machines using their IP address in each one`s terminal.
4. For the remote login, Tina would need to run the command "sudo apt-get install openssh-server" to install the SHH server on her machine. Tom, on the otherhand, can use the >
5. To file share the "scp" command is needed to secure and copy files for the machines. Example: Tina runs "scp (file)(username)@(Tom`s IP Address):(destination)" to send the >
6. For troubleshooting issues on the network, if necessary, tools such as Tcpdump, WireShark, Netstat can be used fo diagnosis.
7. To open ports on the fire use the command "ufw". Example: "sudo ufw allow 22/tcp."
8. For DoS protection the firewall can block the unwanted incoming traffic and IDS to detect and respond to attacks.


- Set strong passwords for accounts and change if necessary or regularly.
- Use public authentication instead of the password authentication.
- Keep laptop and software up to date.
- Use VPN to encrypt their internal traffic and protect their data from interception.
- Know risk of file sharing on networks for sensitive data.
- Know risk of security for opening ports at the firewall level to mitigate them.


