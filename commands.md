# Commands Used (pfSense Firewall & WAN Security Assessment)

## Host Discovery
- nmap 110.39.164.74
- nmap -Pn 110.39.164.74

## Firewall Behavior (ACK Scan)
- nmap -sA 110.39.164.74

## TCP Port Scanning
- nmap -T3 --top-ports 100 110.39.164.74
- nmap -sV -p 53,80 110.39.164.74

## UDP Scan (limited)
- nmap -sU --top-ports 20 <TARGET_IP>

## Web Enumeration
- curl -I http://110.39.164.74
- nmap -p 80 --script http-enum 110.39.164.74
- dirb http://110.39.164.74/
- whatweb http://110.39.164.74
