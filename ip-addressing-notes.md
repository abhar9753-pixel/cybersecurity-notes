# IP Addressing Notes

## What is an IP Address
- Unique address given to a device on a network
- Format: 192.168.1.1 (4 numbers, 0–255 range)

## Types of IP
- Public IP: visible on the internet, given by ISP
- Private IP: used inside local network (e.g. 192.168.x.x, 10.x.x.x)

## IP Classes
- Class A: 1.0.0.0 – 126.255.255.255
- Class B: 128.0.0.0 – 191.255.255.255
- Class C: 192.0.0.0 – 223.255.255.255

## Subnet Mask
- Defines which part of IP is network vs host
- Example: 255.255.255.0

## CIDR Notation
- Example: 192.168.1.0/24
- /24 means first 24 bits = network part

## Practice
- Used `ifconfig` / `ipconfig` to check my own IP
- Completed TryHackMe room: [room name]
- Key takeaway: [what I learned]
## TryHackMe Progress

### Room: Offensive Security Intro
- Completed on: 26 July 2026
- What I learned:
  - Difference between Offensive Security and Defensive Security
  - Used `dirb` tool to find hidden directories on a website
  - Found hidden admin panel and exploited it to change account balance
  - Practiced basic web exploitation in a safe, legal environment
- Key takeaway: Small misconfigurations (like exposed admin panels) can lead to big security issues
