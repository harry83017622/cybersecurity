Please Use This Repo Legally.

Requirement: Nmap, Scapy

Use nmap to do port scanning
```
// nmap port scanning
time nmap -T4 -sT -p T:1-65535 192.168.1.1


/*
PORT    STATE   SERVICE
53/tcp    open  domain
5556/tcp  open freeciv                  
52869/tcp open  unknown            
52881/tcp open  unknown 
*/
```

Then put this result in your secret.cfg

run .py then wait for about 3-5min depend how strong is your router...