# commands

| Command | Enviroments | Description |
|--- |--- |--- |
| `traceroute {web addr}` | Linux | Network path to {web addr} | 
| `netstat` | Linux | Network statistics |
| `arp -a` | Linux | Network devices recently communicated |
| `nmap -sn 192.168.1.0/24` | Linux | Devices on `192.168.1.0/24` subnet |
| `nslookup {web addr}` | Linux | DNS data for {web addr} |
| `strace -c ls` | Linux | System calls data for `ls` |
| `curl parrot.live` | Linux | Shows a parrot dancing (`parrot.live` is a web address) |
| echo -n -e 's' &#124; nc -u -w 2 {IP} {PORT} &#124; hexdump -C | ASE protocol mostly for game servers. Port is usually main port + 123 |