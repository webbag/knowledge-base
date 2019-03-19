ssh-copy-id username@host
ssh-keygen

sudo useradd -m packagist -s /bin/bash
passwd packagist

sudo usermod -aG sudo packagist

sudo openvpn --config firstname.lastname.ovpn


Testing that everything is set up correctly
ssh -T git@gitlab.com

scp -r uzytkownik@serwer.pl:/scieżka/plik_serwer plik_lokalny
scp plik_lokalny uzytkownik@serwer.pl:/sciezka/plik_serwer


sudo lsof -nP -i | grep LISTEN



Checking Debian Version from the Command Line
The lsb_release utility displays LSB (Linux Standard Base) information about the Linux distribution.
```
lsb_release -a
```    
