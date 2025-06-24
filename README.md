# Cybersecurity-task1
Cyber Security Internship - Task 1: Network Port Scanning

Objective
Perform a TCP SYN scan on the local network to identify open ports and understand network exposure.

Tools Used

    Nmap
    Kali Linux
    (Optional) Wireshark

Steps Followed

    Checked IP using ip a

    My local IP: 192.168.1.8, Network: 192.168.1.0/24

    Run scan:
    sudo nmap -sS 192.168.1.0/24 -oN scan_results.txt

    Also run:
    sudo nmap -sn 192.168.1.0/24
    sudo nmap -sS 192.168.1.1 -oN single_host_scan.txt

Results

    Saved scan output in scan_results.txt or single_host_scan.txt
    Found [X] live host(s)
    Identified open ports and related services

Security Insights

    Open ports indicate active services.
    These could be entry points for attackers.
    Ports like SSH (22), HTTP (80), or SMB (445) need strong configuration.

