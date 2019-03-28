# docker
docker run -p8080:8080 kushguptacse/docker-spring-test
To Test application. goto browser and type - http://localhost:8080/print/{msg}

# docker compose
docker-compose up
To Test application. goto browser and type - http://localhost:9096

GET: http://localhost:9096/data/{id}

POST: http://localhost:9096/data
{
"content" : "hello from docker compose test"
}
