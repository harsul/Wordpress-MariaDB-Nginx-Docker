# Wordpress-MariaDB-Nginx-Docker

Setup and configuration

Make the folders in the cloned repository
  mkdir -p certs/ certs-data/ logs/nginx/ mysql/ wordpress/

1. Change the domain name in nginx folder 
   
2. SSL certificate
  ./letsencrypt-init.sh FQDN_OR_IP, where FQDN_OR_IP is the publicly registered domain
  
3. Docker
  docker-compose up -d
