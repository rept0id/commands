# commands

| Command | Enviroments | Description |
|--- |--- |--- |
| `traceroute example.com` | Linux | Network path to `example.com` | 
| `netstat` | Linux | Network statistics |
| `arp -a` | Linux | Network devices recently communicated |
| `nmap -sn 192.168.1.0/24` | Linux | Devices on `192.168.1.0/24` subnet |
| `nslookup example.com` | Linux | DNS data for `example.com` |
| `strace -c ls` | Linux | System calls data for `ls` |
| curl parrot.live | Linux | Shows a parrot dancing (parrot.live is a web address) |
| echo -n -e 's' | nc -u -w 2 <IP> <PORT> | hexdump -C | ASE protocol mostly for game servers. Port is usually main port + 123 |