## How to run

Before running the compose file, make sure to setup the environment variables.
You can use the `.env.example` file provided as a template for your `.env` file.

Simply copy the file and edit it to add your variables before running the service.
```
cp .env.example .env
// Edit .env file and save
docker compose up -d
``` 
 
## Check RethinkDB version

Make sure to run your container before running this command.
```
sudo echo $(docker exec -i $1 rethinkdb --version) |sudo  tee -a /data/logs/install_version.txt
```
