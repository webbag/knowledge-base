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
