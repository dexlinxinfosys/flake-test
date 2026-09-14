$ ./init_breach.sh --target=10.0.0.1 --stealth
[*] Establishing connection...
[*] Connection established. Handshake OK.
[*] Bypassing firewall rules... done (3/3 rulesets disabled)
[*] Enumerating open ports: 22, 80, 443, 3306, 8080
[*] Exploiting CVE-2024-XXXXX on port 8080...
[+] Shell obtained: uid=0(root) gid=0(root) groups=0(root)
[*] Escalating privileges... SUCCESS
[*] Dumping credentials from /etc/shadow...
    root:$6$Xk3f...:19876:0:99999:7:::
    admin:$6$Qw9z...:19876:0:99999:7:::
[*] Exfiltrating data... [##########] 100%
[*] Covering tracks: clearing auth.log, wtmp, bash_history
[+] Access maintained via backdoor on port 4444
[*] Mission complete. Time elapsed: 00:03:42
$ _
