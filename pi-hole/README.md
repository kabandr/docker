# Before you run this container

Copy the env. example file provided in this folder and change it with your details.

```
cp .env.example .env
```
# Running Pi-Hole

Depending on your docker compose version, run:

```
docker compose up -d 

or 

docker-compose up -d 
```

## Access Pi-Hole Web Admin

Replace `DNS_IP` in the URL below with your DNS IP, then browse to this link to access the Web Dashboard where you can manage your Pi-Hole.

```
http://DNS_IP:8080/admin/
```
The password you log in with, you'd added it to the .env file