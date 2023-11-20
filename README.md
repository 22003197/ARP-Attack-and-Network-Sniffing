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
![image](https://github.com/22003197/ARP-Attack-and-Network-Sniffing/assets/124332243/80dccc83-c080-4ac8-9202-7b37564a9c7d)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/22003197/ARP-Attack-and-Network-Sniffing/assets/124332243/0755b561-dc06-4048-8944-f765f06233b1)


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/22003197/ARP-Attack-and-Network-Sniffing/assets/124332243/1c8d3194-385a-4518-bf43-3e07424a9ee5)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/22003197/ARP-Attack-and-Network-Sniffing/assets/124332243/819bb356-7213-4827-8bb4-38746338bf24)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
