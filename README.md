Requirement :

1. Docker (installation flow : install.sh)
2. Docker Compose (Installation flow : install.sh)
3. Cloudflare pem and key  

Installation step :

1. make new folder on proxy with your domain name
2. add certificate.crt and private.key
3. change domain on proxy/default.conf.template to your domain
4. run container with this command `docker-compose up -d`
5. to stop container compose with this comman `docker-compose stop`
