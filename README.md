# kubernetes-spring


## Postgress image  `https://www.baeldung.com/ops/postgresql-docker-setup`

docker run -itd -e POSTGRES_USER=htrix -e POSTGRES_PASSWORD=sasa -p 5432:5432 -v /data:/var/lib/postgresql/data --name postgresql postgres

## PG administrator
docker pull dpage/pgadmin4:latest

docker run --name pgadmin -p 5051:80 -e "PGADMIN_DEFAULT_EMAIL=user@htrix.com" -e "PGADMIN_DEFAULT_PASSWORD=sasa" -d dpage/pgadmin4

