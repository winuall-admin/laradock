<p align="center">
    <img src="https://s19.postimg.org/jblfytw9f/laradock-logo.jpg" alt="Laradock Logo"/>
</p>


1. Install docker and docker-compose
2. docker-compose exec workspace bash
3. composer install
4. docker-compose up -d nginx
5. docker-compose logs nginx to troubleshoot


## How to setup ssl with laradock?

To setup ssl certificate with nginx in laradock, follow these steps:

1. Generate certificates manually in personal laptop using certbot: sudo certbot certonly --manual
2. Verify by transfering the files to the server and running nginx on http
3. Once the domain is verified, transfer the certificate files in the laradock/nginx folder
scp -i winuallconnect.pem fullchain.pem ec2-user@mec2-50-17-16-67.compute-1.amazonaws.com:~/.

4. Modify laradock/nginx/Dockerfile and laradock/nginx/sites/default.conf
5. Build the nginx image again
6. Modify conf file to accept requests on 443
