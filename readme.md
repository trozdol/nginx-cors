# Quick Start

    git clone https://github.com/trozdol/nginx-cors.git
    cd ./nginx-cors

Make changes to `docker/nginx.conf` to specifiy target server and base uri.

Update `./www/index.html` or put your own code there. 

Start Docker

    docker compose up
    docker compose up -d
    docker compose up -d --build

    docker compose down

- http://localhost/ to serve local files
- http://localhost/remote/uri to hit proxied server

### Sencha CMD Note:

To disable Sencha CMD webserver but watch for changes.

    sencha app watch -w 


