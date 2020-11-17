# Traefik V2 docker stack

Traefik is edge router routing Nginx reverse proxy to host multiple domains and apps on a single VPS. Treafik also serves as load balancer.

see guide at https://medium.com/@containeroo/traefik-2-2-docker-global-entrypoint-configuration-ff11d7f84913

File structure:

```
/opt/containers/
+-- traefik
|   +-- docker-compose.yml  // 
|   +-- data
|   |   +-- traefik.yml     // 
|   |   +-- config.yml      // 
|   |   +-- acme.json       // 
+-- portainer
|   +-- docker-compose.yml  //
+-- netdata
|   +-- docker-compose.yml  // 
+-- wordpress
|   +-- docker-compose.yml  // 

```
