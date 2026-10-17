Nmap Network Scanning

Project Overview
This project documents my practical learning experience using Nmap, a network scanning tool used in cybersecurity.

Objective
To learn how to identify open ports and services on a host using Nmap.

Tool Used
- Nmap 7.991

Lab Environment
- Operating System: Windows
- Target: Localhost (127.0.0.1)

Scan Command
nmap 127.0.0.1

Scan Results
The scan identified the following open TCP ports:

| Port | State | Service |
|------|-------|---------|
| 135/tcp | Open | MSRPC |
| 445/tcp | Open | Microsoft-DS |

Analysis
Port 135 is associated with Microsoft RPC services, while port 445 is associated with Microsoft-DS, commonly used for Windows file sharing through SMB.

These services may be legitimate, but they should be reviewed and secured appropriately.

What I Learned
- How to install Nmap on Windows.
- How to scan localhost.
- How to identify open TCP ports.
- How to interpret basic Nmap scan results.
Disclaimer
This scan was performed on my own local machine for educational purposes.
Step 3: Save your changes

1. Click **Commit changes**.
2. Keep the commit message GitHub suggests, or enter: `Document Nmap service detection results`.
3. Select **Commit changes** again.

---

4. What comes next?

After saving, we'll move on to another practical exercise: 
learning how to identify which ports are open on a computer and how to interpret the results.

You're building a portfolio that shows not only the tools you've used, but also your ability to interpret their findings and explain security implications.

For now, let's finish updating your README.

Tell me when you've clicked the pencil icon and opened the editing screen. I'll guide you through the next step. 💻
