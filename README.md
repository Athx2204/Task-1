# Task-1:Scan Your Local Network for Open Ports

# Objective: Learn to discover open ports on devices in your local network to understand
network exposure.

## Command Used:
nmap -sT -p 22,80,443,139,3389 192.168.0.0/24 -oN scan_results.txt

## Output:
See \`scan_results.txt\` for scan details.

## Learnings:
- Learned how to perform a TCP scan on a subnet
- Understood how open ports indicate running services
- Gained awareness of local network exposure risks


