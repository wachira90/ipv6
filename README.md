# ipv6
ipv6 implement

## class

````
fe80::/x => localhost ip 127.0.0.1

fc00::/64 => private ip 192.168.x.x

2xxx::/64 = public ip

````

## dual stack implement

````
old IP => 192.168.1.55

C:\Users\admin>ping fd01::192.168.6.55
Pinging fd01::c0a8:637 with 32 bytes of data:
Control-C
^C
C:\Users\admin>

for new ipv6 => fd01::c0a8:637

````

## allow limit ssh /etc/hosts.deny

````
nano /etc/hosts.deny

nginx : .internettl.org
sshd : ALL EXCEPT 192.168.4.0/24 [fc00:1000::]/64
````
