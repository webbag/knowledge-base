ssh-copy-id username@host
ssh-keygen

sudo useradd -m gitlab.aaaa -s /bin/bash
passwd gitlab.devggp

sudo usermod -aG sudo firstname.lastname

sudo openvpn --config firstname.lastname.ovpn


Testing that everything is set up correctly
ssh -T git@aaaaaaaaaa.com

scp -r uzytkownik@serwer.pl:/scieżka/plik_serwer plik_lokalny
scp -P 1234 user@host:/path_file_name path/
scp plik_lokalny uzytkownik@serwer.pl:/sciezka/plik_serwer


sudo lsof -nP -i | grep LISTEN

https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04

Checking Debian Version from the Command Line
The lsb_release utility displays LSB (Linux Standard Base) information about the Linux distribution.

```
lsb_release -a
```

​rsync --progress --delete -ax

rsync --progress -av --delete \
   --exclude /path \
   /path \
   -e 'ssh -p 1234' /local_path \
    user@host:/remote_path

bzip2 -d path_file_name.bz2 


https://www.flynerd.pl/2018/06/20-polecen-terminala-unix-podstawowe-komendy-linux-ktore-trzeba-znac.html#locate
