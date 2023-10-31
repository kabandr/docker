# Portainer

## Step 1: Create a volume for portainer data

Before you run this container, you need to first create a volume.

```
docker volume create portainer_data
```
## Step 2: Run container

```
docker compose up -d
```