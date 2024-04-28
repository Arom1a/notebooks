## 1 Basic Model
| Layers | Name         | Usage                                               | Examples                                                 |
| ------ | ------------ | --------------------------------------------------- | -------------------------------------------------------- |
| 7      | Application  | Network process to application                      | DNS, www/HTTP, FTP, SMTP, NFS, Telnet, P2P               |
| 6      | Presentation | Data representation and encryption                  | DOC, JPG, PNG, GIF, CSS, HTML, Sockets                   |
| 5      | Session      | Interhost communication                             | TEL, SIP, RTP, RPC-named pipes                           |
| 4      | Transport    | Ene-to-end connections and reliability              | TCP, UDP, SCTP, SSL, TLS                                 |
| 3      | Network      | Path determination and logical addressing (Routing) | IPv4, IPv6, ARP, IPsec, ICMP, IGMP, OSPF                 |
| 2      | Data Link    | Physical addressing (Switching)                     | Ethernet, MAC/LLC, VALN, ATM, HDP, Fiber Channel, HDLC   |
| 1      | Physical     | Media, signal, and binary transmission (Cabling)    | RS-232, RJ45, v.34, 100BASE-TX, SDH, DSL, Ethernet, WiFi |

## 2 Cyber Security
| Layers          | Attacks & Exploits                                                     | Function                                                                            |
| --------------- | ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| 7. Application  | Interface to end users, interaction directly with software application | Phishing & email compromise; Password cracking; Buffer overflow / SQL injection     |
| 6. Presentation | Formats data to be "presented" between application-layer entities      | Injection attacks; File inclusion; Cross-site scripting; Cross-site request forgery |
| 5. Session      | Manages connections between local and remote application               | Session hijacking; Access control bypass; Adversary-in-the-middle                   |
| 4. Transport    | Ensures integrity of data transmission                                 | Port scanning; DNS poisoning; Lateral movement                                      |
| 3. Network      | Determines how data gets from one host to another                      | IP spoofing; Manipulating routing tables; DDoS flooding                             |
| 2. Data Link    | Defines format of date on the network                                  | MAC & ARP spoofing; Gateway id check; Rogue APs                                     |
| 1. Physical     | Transmits raw bit stream over physical medium                          | Device tampering; Physical disruption; Traffic eavesdropping                        | 
