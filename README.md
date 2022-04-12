# ipv6
ipv6 implement

## class

````
fe80::/x => 127.0.0.1

fc00::/64 => private ip 192.168.x.x

2xxx::/64 = public IP

````

## dual stack implement

````
old IP => 192.168.1.55
ping fc00::192.168.1.55
````

## allow limit ssh /etc/hosts.deny

````
nano /etc/hosts.deny

nginx : .internettl.org
sshd : ALL EXCEPT 192.168.4.0/24 [fc00:1000::]/64
````
