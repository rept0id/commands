# commands

## Favorites

| Command | Enviroments | Description |
|--- |--- |--- |
| git rebase -i \<COMMIT HASH\> | Git | Git squash (change pick to squash were wanted) |
| docker run -it -p \<EXTERNAL PORT>:\<INTERNAL PORT> --rm \<IMAGE> | Linux | Docker run temporary (--rm) an image |
| which \<BINARY> | Linux | Where is a binary |
| apt get install openssh-server | Linux | Install openssh server (APT / Debian-based) |
| git reset --hard \<COMMIT HASH\> | Git | Git reset |
| nmap -sn 192.168.1.0/24 | Linux | Devices on 192.168.1.0/24 subnet |
| python3 -m venv venv | Python | Python virtual environment |
| python3 -m http.server | Python | Python HTTP server |
| source venv/bin/activate | Linux | Python activate virtual environment (Linux) |
| .\venv\Scripts\activate | Windows | Python activate virtual environment (Windows) |
| pip freeze > requirements.txt | Python | Python PIP modules list to files |

## More

| Command | Enviroments | Description |
|--- |--- |--- |
| traceroute \<ADDRESS\> | Linux | Network path to {web addr} | 
| netstat | Linux | Network statistics |
| arp -a | Linux | Network devices recently communicated |
| strace -c ls | Linux | System calls data for ls |
| curl parrot.live | Linux | Shows a parrot dancing (parrot.live is a web address) |
| echo -n -e 's' &#124; nc -u -w 2 \<IP\> \<PORT\> &#124; hexdump -C | Linux | ASE protocol mostly for game servers. Port is usually main port + 123 |
| docker system prune -a --volumes | Linux | Docker remove everything, even volumes |
| docker stats | Linux | Docker resource monitor |
| ip a | Linux | Get IP interfaces |
| ip neigh | Linux | Get IP neighbours |
| nslookup \<URL\> \<DNS server\> | Linux | Query DNS server for a URL |
| dig @\<DNS server\> \<URL\> | Linux | Query DNS server for a URL |
| git log | Git | Git log |
| git checkout -b \<NEW BRANCH NAME\> | Git | Git new branch |
| host -t MX \<ADDRESS\> | Linux | Get info about email of address |
| host -t NS \<ADDRESS\> | Linux | Get info about nameservers of address |
| passwd | Linux | Change password |
| sudo apt --fix-broken install | Linux | Fix missing dependencies (APT / Debian-based) 
