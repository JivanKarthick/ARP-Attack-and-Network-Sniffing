# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

### STEPS:

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

![image](https://github.com/JivanKarthick/ARP-Attack-and-Network-Sniffing/assets/121165867/72c486b3-f408-4328-8d8b-974b6ed2bf69)
)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/JivanKarthick/ARP-Attack-and-Network-Sniffing/assets/121165867/5571b9f6-dc59-4292-a329-f143cbcdabcf)


### dsniff:






#### In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![image](https://github.com/JivanKarthick/ARP-Attack-and-Network-Sniffing/assets/121165867/490d43f7-d1e3-4cab-8f28-fb882f2f1244)


### In Kali issue the following commands: sudo dsnifff
## OUTPUT:

![image](https://github.com/JivanKarthick/ARP-Attack-and-Network-Sniffing/assets/121165867/1c9278ab-f102-4bcc-89a0-c2090238a6e4)



### Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/JivanKarthick/ARP-Attack-and-Network-Sniffing/assets/121165867/080a387d-a6da-44df-a354-bab5f1593d04)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
