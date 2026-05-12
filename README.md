# TryHackMe: Blue Room Writeup

## Objective
Exploit a vulnerable Windows machine to gain user and root access.

## Tools Used
- Nmap
- Metasploit
- SMBClient

## Steps
1. Recon: Ran nmap -sV 10.10.x to find open ports.
2. Exploitation: Used Metasploit module ms17_010_eternalblue.
3. Post-Exploit: Retrieved user.txt and root.txt flags.

## Screenshots
Add screenshots here.

## What I Learned
How to use Metasploit and understand SMB vulnerabilities.
