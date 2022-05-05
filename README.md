### PORT LIST
| App | Ports |
|---|---|
| Jenkins | 8080 |
|...||


## Zzz
#### docker-compose up 
- start and restart all the services defined in docker-compose.yml

#### docker-compose start 
- command will only restart containers stopped previously

#### docker-compose stop 
- command will stop running containers but won’t remove them

#### docker-compose down
- Stop and remove containers, networks..

#### docker-compose down --volumes
- Down and remove volumes

#### docker-compose down --rmi <all|local>
- Down and remove images