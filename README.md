# Task-1-
Local Network Scanning for Open Ports  Via Nmap & Wireshark 

Step 1 : I have scan my network with  basic nmap command : nmap -sS 192.168.244.128
Step 2 : In second while i have scan for version detection : nmap -sV 192.168.244.128 
Step 3 : Then check for open port : nmap -sS -PN 192.168.244.128/24 
Step 4 : After all this saving the command output in a file :  nmap -sS 192.168.244.128/24 -oN scan_output.txt 

# After i will scan network with Wireshark . 

In wireshark i have found one open port which also show services & version running on that port.
It also show lot's of detail about that ip address and open port 
