Bigboy0028@htb[/htb]$ sudo nmap --open -oA inlanefreight_ept_tcp_1k -iL scope 

Starting Nmap 7.92 ( https://nmap.org ) at 2022-06-20 14:56 EDT
Nmap scan report for 10.129.203.101
Host is up (0.12s latency).
Not shown: 989 closed tcp ports (reset)
PORT     STATE SERVICE
21/tcp   open  ftp
22/tcp   open  ssh
25/tcp   open  smtp
53/tcp   open  domain
80/tcp   open  http
110/tcp  open  pop3
111/tcp  open  rpcbind
143/tcp  open  imap
993/tcp  open  imaps
995/tcp  open  pop3s
8080/tcp open  http-proxy

Nmap done: 1 IP address (1 host up) scanned in 2.25 seconds
