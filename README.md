# Docker Compose Services

A collection of Docker Compose files for services I frequently use for development, testing, and infrastructure. 

Over 40 pre-configured services including databases, monitoring tools, CI/CD platforms, and development environments.

Each service is organized in its own directory with configuration files and setup instructions.

## Services

- [Authentik](authentik)
- [ELK Stack (Elasticsearch, Logstash, Kibana)](elk)
- [Gitea](gitea)
- [Gitea with PostgreSQL](gitea-postgres)
- [GitLab](gitlab)
- [Grafana](grafana)
- [Immich](immich)
- [Jenkins](jenkins)
- [K3s Kubernetes](k3s)
- [Apache Kafka](kafka)
- [LocalStack](localstack)
- [MongoDB](mongo)
- [MySQL](mysql)
- [MySQL Workbench](mysql-workbench)
- [Nextcloud](nextcloud)
- [Nginx Proxy Manager](nginx-proxy-manager)
- [OpenSearch](opensearch)
- [pgAdmin](pgadmin)
- [Pi-hole](pi-hole)
- [Plex](plex)
- [Portainer](portainer)
- [PostgreSQL](postgres)
- [Prometheus](prometheus)
- [Prowler](prowler)
- [Rancher](rancher)
- [Rancher Traefik](rancher-traefik)
- [RethinkDB](rethinkdb)
- [RustDesk](rustdesk)
- [SingleStore (formerly MemSQL)](singlestore)
- [SQL Server 2022](sql-server-2022)
- [TeamCity](teamcity)
- [Traefik](traefik)
- [Ubuntu 22.04](ubuntu-22)
- [Ubuntu Desktop with LXDE](ubuntu-desktop-lxde)
- [Unifi Controller](unifi-controller)
- [Uptime Kuma](uptime-kuma)
- [VS Code](vscode)
- [WireGuard](wireguard)
- [WordPress](wordpress)

## How to Use

### Prerequisites

- Docker and Docker Compose installed on your system
- Sufficient disk space and system resources for the services you plan to run

### Basic Setup

1. Navigate to the service directory of your choice:

   ```bash
   cd /path/to/service
   ```

2. Review any service-specific documentation (README or comments in the compose file)

3. Start the service:

   ```bash
   docker compose up -d
   ```

4. Verify the service is running:

   ```bash
   docker compose ps
   ```



### Notes

- Some services may require environment variables or additional configuration before starting
- Check each service's directory for specific setup instructions
- Services may expose different ports


## Contributing

Feel free to contribute or report issues if you encounter any problems or have suggestions for improvements. Pull requests are welcome.

Happy containerising!

