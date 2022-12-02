git clone 

cd ./cors-proxy

docker compose up
docker compose up -d
docker compose up -d --build

docker compose down

## Sencha CMD:

To disable Sencha CMD webserver but watch for changes.

    sencha app watch -w 