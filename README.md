# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/M-Nikhil20/ARP-Attack-and-Network-Sniffing/assets/118707852/d0459999-2f5c-40fd-9ab4-f6399b90ec7b)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/M-Nikhil20/ARP-Attack-and-Network-Sniffing/assets/118707852/8ddfb282-cc74-41a6-a95c-76e92fde4df8)



 dsniff:





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/M-Nikhil20/ARP-Attack-and-Network-Sniffing/assets/118707852/5c01fb44-be1e-40ba-9948-86601d0bb7f5)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/M-Nikhil20/ARP-Attack-and-Network-Sniffing/assets/118707852/3076865b-0e9e-4223-a638-d1d238824e70)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/M-Nikhil20/ARP-Attack-and-Network-Sniffing/assets/118707852/96e2fb1b-0d0e-475c-81e0-77de5b14800a)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
