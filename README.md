 Basic Network Scanning with Nmap

 Objective
The objective of this project is to perform a basic network scan using Nmap to identify open ports and services running on the local machine.

 Tool Used
- Nmap 7.99
- Command Prompt
- Windows 11

 Scan Command Used

```bash
nmap -sV 127.0.0.1 -oN clean_scan.txt
```

 Scan Results

The scan identified the following open ports:

| Port | State | Service | Description |
|------|------|------|------|
| 135/tcp | Open | msrpc | Microsoft Remote Procedure Call |
| 445/tcp | Open | microsoft-ds | SMB file sharing service |

 Observations

- The localhost machine was active.
- 998 ports were closed.
- 2 ports were open.
- Service version detection was successful.

 Conclusion

The Nmap scan successfully identified open ports and running services on the local system. This project demonstrates the use of Nmap for basic network reconnaissance and service detection.

 Learning Outcomes

- Learned how to install and use Nmap for basic network scanning.
- Understood how to identify open ports and running services on a system.
- Gained knowledge about common network ports and their purposes.
- Learned the importance of network reconnaissance in cybersecurity.
- Improved understanding of basic network security assessment techniques.
