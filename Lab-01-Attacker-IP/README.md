# Lab 01: Identify the Attacker's IP

## Objective
To identify the suspicious IP address by analyzing network traffic in Wireshark.

## Tool Used
- Wireshark
- NetworkWalks Online Lab

## Analysis
I analyzed network packets and investigated source and destination IP addresses.

## Wireshark Filter
```text
tcp.flags.syn == 1 && tcp.flags.ack == 0
```

## Findings
- Attacker IP: To be added after verification
- Target IP: To be added after verification
- Attack Type: TCP SYN Port Scanning

## Screenshots
Screenshots of the practical investigation are included in this folder.

## Learning Outcome
Learned how to identify suspicious IP addresses and investigate TCP connection attempts.
