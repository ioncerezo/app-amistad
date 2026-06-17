#iniciar
sudo systemctl start docker

#empezar un compose
docker compose up -d    || docker compose down
docker compose logs -f