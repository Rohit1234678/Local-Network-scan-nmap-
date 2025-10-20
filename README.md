# Task 1 — Local Network Port Scan (Short)

**Author:** Rohit Madhav Sabale

**Summary:** Short report for a local network Nmap scan. 

**Environment**
- Scanner host: 10.0.2.15
- Network scanned: 10.0.2.0/24
- Tool: Nmap 7.92

**Commands used**
```bash
nmap -sn -oA host_discovery.txt 10.0.2.0/24
nmap -sS -oA nmap_all_output.xml 10.0.2.0/24
nmap -sS -sV -oNnmap_srv.txt 10.0.2.0/24
```

**Quick findings (example)**
- 10.0.2.3 — port 53 — dnsmasq 2.51
- 10.0.2.15 — port 22 — OpenSSH 8.7
- 10.0.2.2 — all TCP ports filtered




--- 
Thank you — Rohit
