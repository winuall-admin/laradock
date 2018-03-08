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

1. Generate certificates manually using certbot: sudo certbot certonly --manual
2. Verify by trasnfering the files to the server and running nginx on http
3. Once the domain is verified, transfer the certificate files in the laradock/nginx folder
4. Build the nginx image again
5. Modify conf file to accept requests on 443
