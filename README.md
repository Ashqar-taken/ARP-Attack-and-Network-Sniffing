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
![1 wincmd](https://github.com/user-attachments/assets/81f54d84-4240-478e-ae42-4ca193fcc8aa)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![2 sudo ](https://github.com/user-attachments/assets/052845ce-0e03-4899-988c-84befaed10f1)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3ftp](https://github.com/user-attachments/assets/9a36d9d5-9146-4d4f-9832-73578309247e)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![4dsnif](https://github.com/user-attachments/assets/92194ab9-1b18-4c46-bf8e-926703fe2771)



Invoke the wireshark and examine the various menus  and controls of the tool:

![5wireshark](https://github.com/user-attachments/assets/307b7232-0055-4b10-be87-acb1213c33e6)

## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:

![6ett](https://github.com/user-attachments/assets/e5704e7d-6915-4f99-a99c-699cd32029b1)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
