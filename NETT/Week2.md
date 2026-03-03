Review Questions: 


Tutorial Problem:

# Lab:
### 2.1 
(a) What are the tools used for?
Ping - Shows how long it takes for packets to reach host
Traceroute - Traces the route of packets to destination host from our server
DNS Lookup - Look up DNS record 

(b) What is your IP address? How much is packet loss in ping? What is the IP address of google.com in DNS lookup? When was the domain, i.e., google.com, updated? What is the hostname of 8.8.8.8? 
My IP address - 1.145.69.188
![[Pasted image 20260303191445.png]]

IP address of google - 142.251.38.110
Reverse lookup got host name - lcarna-ac-in-f14.1e100.net
Hostname of 8.8.8.8 - dns.google

(c) Try other tools and your own parameters. 
done

### 2.2 

(a) Find destination (e.g., nslookup google.com.au) IP address: 172.217.24.46
(b) Perform “ping” to the IP address to find the average round-trip delay: 267ms
(c) Use Wireshark to find “ping” outgoing packet information.
Protocol: ICMP
Packet type (Info):  ECHO
(d) User Wireshark to find “ping” incoming packet information.
Protocol: ICMP
Packet type (Info): ECHO

### 2.3
Using “traceroute” to measure network delay and discover network path. In your Lab PC, perform “tracert” to a destination IP address within Australia.
Find the average round-trip delay: 27 ms

(a) Use Wireshark to find “tracert” outgoing packet information.
Protocol: ICMP
Packet type (Info): Echo

(b) Use Wireshark to find “tracert” incoming packet information.
Protocol: ICMP
Packet type (Info): Echo

(c) Try to identify the number of ISP networks that the Traceroute packets pass through from source to destination(How many hops are taken). Routers with similar names and/or similar IP addresses should be considered as part of the same ISP. In your experiments, do the largest delays occur at the peering interfaces between adjacent ISPs? = 10




