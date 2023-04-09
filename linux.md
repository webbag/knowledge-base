Użytkownicy:

useradd - tworzy nowego użytkownika
userdel - usuwa użytkownika
usermod - modyfikuje ustawienia użytkownika, np. dodaje go do grupy
passwd - ustawia hasło dla użytkownika
su - zmiana użytkownika (do innej sesji)
sudo - wykonanie polecenia jako inny użytkownik (zwykle administrator)
Grupy:

groupadd - tworzy nową grupę
groupdel - usuwa grupę
groupmod - modyfikuje ustawienia grupy, np. zmienia jej nazwę
gpasswd - zarządza hasłem grupy, umożliwiając dostęp do niej tylko osobom, które znają hasło
newgrp - zmiana grupy bieżącego użytkownika (do tej samej sesji)




1. Generowanie klucza SSH: `ssh-keygen`
2. Kopiowanie klucza SSH na zdalny serwer: `ssh-copy-id username@host`
3. Dodanie nowego użytkownika w systemie: `sudo useradd -m gitlab.aaaaaaaa -s /bin/bash` 
4. Ustawienie hasła dla nowego użytkownika: `passwd gitlab.aaaaaaaaa`
5. Dodanie użytkownika do grupy sudo: `sudo usermod -aG sudo firstname.lastname`
6. Uruchomienie OpenVPN z podaną konfiguracją: `sudo openvpn --config firstname.lastname.ovpn`
7. Testowanie połączenia SSH: `Testing that everything is set up correctly ssh -T git@aaaaaaaaaa.com`
8. Pobieranie pliku ze zdalnego serwera: `scp user@host:/path_file_name path/` lub `scp -r uzytkownik@serwer.pl:/scieżka/plik_serwer plik_lokalny`
9. Wysyłanie pliku na zdalny serwer: `scp -r -P 1234 katalog_lokalny uzytkownik@serwer.pl:/sciezka/plik_serwer`
10. Wyświetlanie informacji o otwartych portach sieciowych: `sudo lsof -nP -i | grep LISTEN`
11. Instalacja MySQL na Ubuntu 18.04: https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04
12. Sprawdzanie wersji Debian z poziomu linii komend: `lsb_release -a`
13. Synchronizacja plików między serwerami: `rsync --progress -av --delete --exclude /path /path -e 'ssh -p 1234' /local_path user@host:/remote_path`
14. Rozpakowywanie pliku skompresowanego formatem Bzip2: `bzip2 -d path_file_name.bz2`
15. Wyszukiwanie plików na systemie: https://www.flynerd.pl/2018/06/20-polecen-terminala-unix-podstawowe-komendy-linux-ktore-trzeba-znac.html#locate
16. Tworzenie pliku tar z archiwum gzip: `tar cvzf targetfile.tar.gz sourcedirectory`
17. Rozpakowywanie pliku tar: `tar -xzf directory.tar.gz`
18. Zmiana uprawnień dla katalogów: `find dist/ -type d -print0 | xargs -0 chmod 755`
