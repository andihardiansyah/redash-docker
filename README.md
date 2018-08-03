# redash-docker
setup redash with dependecies (postgresql, redis) via docker-compose


# how to run
docker-compose run --rm server create_db      > intiate redash table
docker-compose up -d                          > running container
