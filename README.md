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
![274469362-100e445d-dcde-43d9-882c-66aa3f117336](https://github.com/ASHWINKUMAR2903/ARP-Attack-and-Network-Sniffing/assets/119407186/d0e70146-81f1-4244-8f68-1b38dcae41fb)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![274469802-8f92f656-51a7-487e-b67c-74b434542f7c](https://github.com/ASHWINKUMAR2903/ARP-Attack-and-Network-Sniffing/assets/119407186/4d8cc881-e0a3-42f1-b30c-ee134a0de72c)

dsniff:    
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![274469825-16be6860-380c-46c6-b56e-173cee946f1e](https://github.com/ASHWINKUMAR2903/ARP-Attack-and-Network-Sniffing/assets/119407186/e0ce51b3-baaf-4cd5-b592-5704a5d9a61a)

In Kali issue the following commands:    
sudo dsnifff
## OUTPUT:

![274469872-791f34a9-7389-4eab-9bc0-576b9930a265](https://github.com/ASHWINKUMAR2903/ARP-Attack-and-Network-Sniffing/assets/119407186/312f14fa-ee6f-469e-97cb-0b1bbded8da3)


Invoke the wireshark and examine the various menus  and controls of the tool:

![274469920-dde6ff86-717e-42ea-a1cf-44c170104b90](https://github.com/ASHWINKUMAR2903/ARP-Attack-and-Network-Sniffing/assets/119407186/92c83eb4-b3af-4813-9874-e35b2fe88aab)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
