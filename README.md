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

![image](https://github.com/indrajasukumar/ARP-Attack-and-Network-Sniffing/assets/145115195/d91c142e-57ae-46ca-bf1a-9c376d04f99c)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/indrajasukumar/ARP-Attack-and-Network-Sniffing/assets/145115195/3a59f6dd-ae23-46c9-b1fc-e90b17acdf7b)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/indrajasukumar/ARP-Attack-and-Network-Sniffing/assets/145115195/22807375-a23a-409d-b61f-d9b102def24b)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/indrajasukumar/ARP-Attack-and-Network-Sniffing/assets/145115195/e97de9fd-ff85-4c8e-9c16-7ffd9e597ee8)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/indrajasukumar/ARP-Attack-and-Network-Sniffing/assets/145115195/64975d18-6abc-4f84-8d91-174ee415ffeb)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
