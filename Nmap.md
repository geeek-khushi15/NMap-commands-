

| **Command** | **Description** |
|-------------|-----------------|
| `nmap <target>` | Basic scan to check if the host is up and discover open ports. |
| `nmap -sS <target>` | TCP SYN scan (Stealth scan). |
| `nmap -sT <target>` | TCP Connect scan (Full connection). |
| `nmap -sU <target>` | UDP scan. |
| `nmap -sA <target>` | ACK scan to check firewall rules. |
| `nmap -sW <target>` | Window scan to detect open ports. |
| `nmap -sM <target>` | Maimon scan to bypass certain firewalls. |
| `nmap -Pn <target>` | Disable host discovery (scan even if ICMP is blocked). |
| `nmap -p <port>` | Scan specific port (e.g., `-p 80`). |
| `nmap -p- <target>` | Scan all 65535 ports. |
| `nmap -p 1-100 <target>` | Scan port range from 1 to 100. |
| `nmap -F <target>` | Fast scan (Top 100 ports). |
| `nmap -sV <target>` | Version detection of services. |
| `nmap -A <target>` | Aggressive scan (OS detection, version detection, script scanning, and traceroute). |
| `nmap -O <target>` | OS detection. |
| `nmap -v <target>` | Verbose output. |
| `nmap -vv <target>` | Very verbose output. |
| `nmap -T0 <target>` | Paranoid scan (slowest, for IDS evasion). |
| `nmap -T5 <target>` | Insane scan (fastest). |
| `nmap -sC <target>` | Default scripts scan. |
| `nmap --script=<script-name> <target>` | Run a specific NSE script. |
| `nmap -oN output.txt <target>` | Save output in normal format. |
| `nmap -oX output.xml <target>` | Save output in XML format. |
| `nmap -oG output.gnmap <target>` | Save output in Grepable format. |
| `nmap -iL list.txt` | Scan targets from a list of IPs. |
| `nmap --traceroute <target>` | Perform a traceroute to the target. |
| `nmap -6 <target>` | Scan IPv6 address. |
| `nmap --open <target>` | Show only open ports. |
| `nmap --top-ports <number> <target>` | Scan the top N most common ports. |
| `nmap --script vuln <target>` | Scan for vulnerabilities using NSE scripts. |
| `nmap -D RND:10 <target>` | Decoy scan with random IPs for stealth. |
| `nmap -S <spoofed-IP> <target>` | Spoof source IP. |
| `nmap -f <target>` | Fragment packets to bypass firewalls/IDS. |
| `nmap --reason <target>` | Show reasons for each port state. |



