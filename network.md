Linux shell network
===========================

Skanowanie wewnetrznej sieci  
```
# aaaaaa
nmap -A -T4 192.168.0.1-255
```

Skanowanie portów  
```
nmap -p 0-65536 172.18.0.1
```

sudo netstat -lnp | grep redis
