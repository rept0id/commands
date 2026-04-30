# commands

## Funny

| Command | Enviroments | Description | Favorite | 
|--- |--- |--- |--- |
| curl parrot.live | Linux | Shows a parrot dancing (parrot.live is a web address) | |

## Network

| Command | Enviroments | Description | Favorite | 
|--- |--- |--- |--- |
| traceroute \<ADDRESS\> | Linux | Network path to {web addr} | * | 
| netstat | Linux | Network statistics | |
| arp -a | Linux | Network devices recently communicated | * |
| ip a | Linux | Get IP interfaces | |
| ip neigh | Linux | Get IP neighbours | |
| nslookup \<URL\> \<DNS server\> | Linux | Query DNS server for a URL | |
| dig @\<DNS server\> \<URL\> | Linux | Query DNS server for a URL, detailed | |
| resolvectl show-cache | Linux | Shows DNS cache (systemd / systemd-resolve) | * |
| resolvectl flush-caches | Linux | Clears DNS cache (systemd / systemd-resolve) | * |
| host -t MX \<ADDRESS\> | Linux | Get info about email of address | |
| host -t NS \<ADDRESS\> | Linux | Get info about nameservers of address | |
| echo -n -e 's' &#124; nc -u -w 2 \<IP\> \<PORT\> &#124; hexdump -C | Linux | ASE protocol mostly for game servers. Port is usually main port + 123 | |
| nmap -sn 192.168.1.0/24 | Linux | Devices on 192.168.1.0/24 subnet | * |

## Docker

| Command | Enviroments | Description | Favorite | 
|--- |--- |--- |--- |
| docker system prune -a --volumes | Linux | Docker remove everything, even volumes | * |
| docker stats | Linux | Docker resource monitor | |
| docker run -it -p \<EXTERNAL PORT>:\<INTERNAL PORT> --rm \<IMAGE> | Linux | Docker run temporary (--rm) an image | * |

## Development

| Command | Enviroments | Description | Favorite | 
|--- |--- |--- |--- |
| python3 -m venv venv | Python | Python virtual environment | * |
| python3 -m http.server | Python | Python HTTP server | * |
| source venv/bin/activate | Linux | Python activate virtual environment (Linux) | * |
| .\venv\Scripts\activate | Windows | Python activate virtual environment (Windows) | * |
| pip freeze > requirements.txt | Python | Python PIP modules list to files | * |
| pip install -r requirements.txt | Python | Install requirements | * |

## Git

| Command | Enviroments | Description | Favorite | 
|--- |--- |--- |--- |
| git init | Git | Init | |
| git remote -v | Git | View remote | |
| git remote set-url origin git@github.com:rept0id/commands.git | Git | Set remote (SSH) | * |
| git clone git@github.com:rept0id/commands.git | Git | Clone (SSH) | * |
| git remote set-url origin https://github.com/rept0id/commands.git | Git | Set remote (HTTP) | * |
| git clone https://github.com/rept0id/commands.git | Git | Clone (HTTP) | * |
| git checkout -b \<NEW BRANCH NAME\> | Git | New branch | * |
| git log | Git | Log | |
| git status | Git | Status (tracked/untracked changes e.t.c) | * |
| git checkout -p . | Git | View all changes and get asked if you want them | * |
| git checkout -p <PATH> | Git | View file or directory changes and get asked if you want them | * |
| git rebase -i \<COMMIT HASH\> | Git | Squash (change pick to squash were wanted) | * |
| git reset --hard \<COMMIT HASH\> | Git | Reset | * |
| git add . | Git | Add all, don't use it | |
| git add <PATH> | Git | Add specific file or directory | |
| git commit -m <MESSAGE> | Git | Commit (new) | |
| git commit --amend | Git | Amend to previous commit (correction) | * |
| git push | Git | Push | |

## System

| Command | Enviroments | Description | Favorite | 
|--- |--- |--- |--- |
| strace -c ls | Linux | System calls data for ls | * |
| passwd | Linux | Change password | * |
| sudo apt --fix-broken install | Linux | Fix missing dependencies (APT / Debian-based) | * |
| which \<BINARY> | Linux | Where is a binary | * |
| apt get install openssh-server | Linux | Install openssh server (APT / Debian-based) | * |
