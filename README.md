# Instrukcja
W folderze z docker-compose.yml:
```sh
docker swarm init 
docker stack deploy -c docker-compose.yml memory_stress_test 
```
Usuwanie:
```sh
docker swarm leave --force 
``` 
