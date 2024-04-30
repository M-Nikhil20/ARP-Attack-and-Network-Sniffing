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
![Screenshot 2024-04-22 222620](https://github.com/R-Udayakumar/ARP-Attack-and-Network-Sniffing/assets/118708024/332ab58a-8689-41fa-8708-9e20004a8f96)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/R-Udayakumar/ARP-Attack-and-Network-Sniffing/assets/118708024/82dceb7d-090e-4c76-b9e2-a91ad13249f0)


 dsniff:





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/R-Udayakumar/ARP-Attack-and-Network-Sniffing/assets/118708024/a2cb6d0a-801c-48d5-aa23-3883aadc9d3c)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/R-Udayakumar/ARP-Attack-and-Network-Sniffing/assets/118708024/11216821-d848-4cab-b11d-da3a651ba779)



Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2024-04-24 225945](https://github.com/R-Udayakumar/ARP-Attack-and-Network-Sniffing/assets/118708024/36b29d59-d5be-4f93-9c80-c7f35f8a4e9d)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
