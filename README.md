# Wordpress-MariaDB-Nginx-Docker

Setup and configuration

Make the folders in the cloned repository 
mkdir -p certs/ certs-data/ logs/nginx/ mysql/ wordpress/

1. Change the domain name (harunsuljagic.tk) in nginx folder, there is more than one, replace all
   
2. For SSL certificate run the letsencrypt-init.sh like this     ./letsencrypt-init.sh FQDN_OR_IP   (FQDN_OR_IP is the publicly registered domain). 

3. 
docker-compose up -d
