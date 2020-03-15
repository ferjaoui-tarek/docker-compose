
# Docker compose
Is a tool for defining & running multi-container docker applications
we use yaml files to configure application services ```docker-compose.yml```
You can start all services with a single command 
```
# docker compose up
```

You can stop all services with a single command 
```
# docker compose down
```
You can scale up selected services when required


Step 1 : install docker compose (already installed on windows and mac with docker)
```
# docker-compose -v
```

Step 2 : Create docker compose file at any location on your system
```
# docker-compose.yml
```

Step 3 : Check the validity of file by command
```
# docker-compose config
```

Step 4 : Run docker-compose.yml file by command
```
# docker-compose up -d
```

Steps 5 : Bring down application by command
```
# docker-compose down
```

TIPS to scale
```
create 4 container of database
# docker-compose up -d --scale database=4
```
