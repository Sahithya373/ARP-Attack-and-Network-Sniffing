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
![image](https://github.com/Sahithya373/ARP-Attack-and-Network-Sniffing/assets/147017926/c3028e58-8331-4e11-b68d-b53ca3d2b108)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Sahithya373/ARP-Attack-and-Network-Sniffing/assets/147017926/6f41e787-6096-4205-888f-bd4212732eb9)


dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/Sahithya373/ARP-Attack-and-Network-Sniffing/assets/147017926/37812dd2-650d-46c2-87bc-d64430d74f3d)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Sahithya373/ARP-Attack-and-Network-Sniffing/assets/147017926/2ed902e5-f993-49dd-bbaa-54831c47a081)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Sahithya373/ARP-Attack-and-Network-Sniffing/assets/147017926/81742492-ec21-4a48-a1b5-e195b0eb38ef)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
