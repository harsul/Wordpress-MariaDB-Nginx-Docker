# Wordpress-MariaDB-Nginx-Docker

Setup and configuration

Make the folders in the cloned repository 
mkdir -p certs/ certs-data/ logs/nginx/ mysql/ wordpress/

Change the domain name (harunsuljagic.tk) in nginx folder, there is more than one, replace all
  
For SSL certificate run the letsencrypt-init.sh like this     
./letsencrypt-init.sh FQDN_OR_IP   (FQDN_OR_IP is the publicly registered domain). 

docker-compose up -d
