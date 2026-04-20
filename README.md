# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
To capture live network traffic and identify different protocols using Wireshark.

## Tools Used
- Wireshark
- Kali Linux

## Steps Performed
i. Installed and launched Wireshark  
ii. Selected the active network interface (wlan0)  
iii. Started packet capture  
iv. Generated traffic by browsing websites and using ping  
v. Stopped capture after about one minute  
vi. Applied filters to analyze captured packets  
vii. Saved the capture file as .pcap  

## Protocols Identified

### 1. DNS (Domain Name System)
- Used to translate domain names into IP addresses  
- Example observed: DNS query for a website (e.g., google.com)  

### 2. TCP (Transmission Control Protocol)
- Connection-oriented protocol  
- Ensures reliable data transmission  
- Observed TCP handshake (SYN, SYN-ACK, ACK)  

### 3. TLS / HTTPS
- Used for secure web communication  
- Encrypts data between client and server  
- Most web traffic captured was encrypted  

## Observations
- DNS queries occur before accessing websites  
- TCP establishes a connection before data transfer  
- Most traffic is encrypted using HTTPS (TLS)  
- No plain HTTP traffic was observed due to modern security practices  

## Conclusion
Wireshark is a powerful tool for capturing and analyzing network traffic.  
It helps in understanding how different protocols communicate and is useful for troubleshooting and security analysis.

## Files Included
- capture.pcap (packet capture file)
