# Task 5: Network Packet Capture and Analysis

## 📚 Description
This task involved capturing live network packets using Wireshark and performing protocol-level traffic analysis. The `.pcapng` data was exported and reviewed in raw format (`taskk5.txt`) for deep inspection.

## 📦 Files Included
- `taskk5.txt`: Raw hexadecimal packet output from Wireshark
- `report.md`: Full analysis based on actual packets in the capture
- `report.txt`: Same as `report.md`, in plain text format

## 🧪 Objective
- Identify protocols in use
- Understand packet structure
- Detect encrypted and unencrypted traffic
- Recognize active services, devices, and destinations

## 🛠 Tools Used
- Wireshark v4.x for packet capture and export
- Manual analysis from raw hex format

## 📎 Summary
Traffic includes encrypted TLS communication, UDP-based service discovery (SSDP, mDNS), and several ARP exchanges. The capture reflects typical system and browser activity at network startup.
