# Nmap Network Scanning Lab

## Objective
Learn how to discover hosts and scan open ports using Nmap.

## Tools Used
- Nmap

## Key Concepts
- Port scanning
- Service detection
- Nmap Switches
- Scan Types(TCP connect Scan,SYN Scan,UDP Scan, NULL, FIN and Xmas)
- NSE Scripts(Working with the NSE,Searching for Scripts)
- Firewall Evasion


## Commands Used

### Basic Scan
nmap <target-ip>

### Scan Specific Ports
nmap -p 80,443 <target-ip>

### Service Version Detection
nmap -sV <target-ip>

### OS Detection
nmap -O <target-ip>

### Aggressive Scan
nmap -A <target-ip>

### TCP Scan
namp -sT -p <port> <target-ip>

## What I Learned
- How to identify open ports
- How to detect running services

## Key Takeaways
- Nmap helps security professionals map networks
- Open ports can reveal vulnerabilities



