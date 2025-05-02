# Common Network Ports Table

| Port Number(s) | Protocol Type (TCP/UDP) | Protocol Full Form                        | Description                                                          |
| -------------- | ----------------------- | ----------------------------------------- | -------------------------------------------------------------------- |
| 20 / 21        | TCP (UDP optional)      | File Transfer Protocol (FTP)              | Used for transferring files. Port 21 for control, 20 often for data. |
| 22             | TCP, UDP                | Secure Shell (SSH)                        | Secure remote login, command execution, file transfers.              |
| 23             | TCP                     | Telnet                                    | Insecure remote login, largely replaced by SSH.                      |
| 25             | TCP                     | Simple Mail Transfer Protocol (SMTP)      | Sends email messages between servers and from clients to servers.    |
| 53             | TCP, UDP                | Domain Name System (DNS)                  | Resolves domain names to IP addresses.                               |
| 80             | TCP                     | Hypertext Transfer Protocol (HTTP)        | Unencrypted web browsing.                                            |
| 88             | TCP, UDP                | Kerberos                                  | Strong authentication for client/server applications.                |
| 110            | TCP                     | Post Office Protocol v3 (POP3)            | Retrieves email from server, older than IMAP.                        |
| 123            | UDP                     | Network Time Protocol (NTP)               | Synchronizes computer clocks.                                        |
| 139            | TCP                     | NetBIOS Session Service                   | File/printer sharing in older Windows networks.                      |
| 143            | TCP, UDP                | Internet Message Access Protocol (IMAP)   | Retrieves emails, supports folders and sync.                         |
| 161 / 162      | UDP                     | Simple Network Management Protocol (SNMP) | 161 for queries/commands, 162 for traps/alerts.                      |
| 389            | TCP, UDP                | Lightweight Directory Access Protocol     | Directory services access, e.g., Active Directory.                   |
| 443            | TCP                     | HTTPS                                     | Secure web browsing using TLS/SSL.                                   |
| 445            | TCP                     | Server Message Block (SMB)                | File/printer sharing in Windows networks.                            |
| 465            | TCP                     | SMTP over SSL                             | Secure email transmission (older method).                            |
| 500            | UDP                     | Internet Key Exchange (IKE)               | Establishes IPsec VPN tunnels.                                       |
| 636            | TCP, UDP                | LDAP over SSL (LDAPS)                     | Secure directory access using TLS/SSL.                               |
| 993            | TCP, UDP                | IMAP over SSL (IMAPS)                     | Secure retrieval of email using IMAP.                                |
| 995            | TCP, UDP                | POP3 over SSL (POP3S)                     | Secure retrieval of email using POP3.                                |
| 1433 / 1434    | TCP (1433), UDP (1434)  | Microsoft SQL Server                      | 1433 for SQL server, 1434 for SQL browser.                           |
| 1521           | TCP                     | Oracle Database                           | Default listener port for Oracle DB.                                 |
| 1812           | UDP                     | RADIUS Authentication                     | Centralized AAA (Authentication, Authorization, Accounting).         |
| 2049           | TCP, UDP                | Network File System (NFS)                 | File access over network, especially in Unix/Linux.                  |
| 3306           | TCP                     | MySQL                                     | Default port for MySQL database.                                     |
| 3389           | TCP                     | Remote Desktop Protocol (RDP)             | Graphical remote access to Windows machines.                         |
| 5060 / 5061    | TCP, UDP                | Session Initiation Protocol (SIP)         | VoIP and multimedia sessions; 5061 for secure SIP.                   |
| 5631 / 5632    | TCP, UDP                | pcAnywhere                                | Used by Symantec’s remote control software.                          |
| 6665 - 6669    | TCP                     | Internet Relay Chat (IRC)                 | Ports used for IRC chat communication.                               |
| 8080           | TCP                     | HTTP Alternate                            | Common for web proxies, alternate HTTP services, or app servers.     |

![image](https://github.com/user-attachments/assets/3a8273fd-226c-45af-bdf2-dfbc4ace2bb1)
