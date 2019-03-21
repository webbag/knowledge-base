# Nginx

Test confoc
nginx -t -c /etc/nginx/nginx.conf
nginx -t

sudo ln -s /etc/nginx/sites-available/example.com /etc/nginx/sites-enabled/

systemctl start nginx
systemctl restart nginx


sudo systemctl disable apache2
sudo apt-get update
sudo apt-get remove apache2
sudo apt-get purge apache2


sudo iptables -L -n

apt search php- | less

sudo ufw app list
ip addr show enp1s0 | grep inet | awk '{ print $2; }' | sed 's/\/.*$//'

https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04

sudo systemctl stop apache2sudo systemctl disable apache2
sudo systemctl disable apache2
sudo apt-get update
sudo apt-get remove apache2
sudo apt autoremove
sudo apt-get purge apache2


We can set the setgid bit on every directory in our WordPress installation by typing:
sudo find /var/www/html -type d -exec chmod g+s {} \;
