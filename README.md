docker compose run --rm rails bundle exec rails db:chatwoot_prepare

docker compose up -d

http://localhost:41200



en error
docker compose up -d postgres redis
docker compose logs -f postgres

docker compose run --rm rails bundle exec rails db:chatwoot_prepare
docker compose up -d
