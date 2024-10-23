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
### OUTPUT:
<img width="390" alt="ethical lab04" src="https://github.com/user-attachments/assets/cb11d022-3aa5-46f9-8c81-9c4b2b657d2c">


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:

<img width="596" alt="ethical lab04 2" src="https://github.com/user-attachments/assets/a72f5803-a215-47f2-8d8d-6a9bb6cd323c">

###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:



<img width="590" alt="ethical lab04 3" src="https://github.com/user-attachments/assets/278dccd0-64b6-4266-90e2-bda39843f43f">


In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

<img width="576" alt="ethical lab04 4" src="https://github.com/user-attachments/assets/4d6079b4-d613-4355-bfcd-63098dd546e4">

Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="859" alt="image" src="https://github.com/user-attachments/assets/464459ce-9465-4d62-bf0f-f9dadf617d47">

### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
