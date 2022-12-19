# odoo-docker-compose
Docker compose file for dev purpose.
This docker-compose use 3 volumes/host folders :
- odoo => Clone your dev addons into it.
- odoo-data => Persistence for odoo container. Delete this folder to refresh the containers persistence.
- db-data => Persistence for postgresql container. Delete this folder to refresh the containers persistence.

## Start :
In project repository :
```bash 
docker compose up -d .
```
## Stop :
In project repository :
```bash 
docker compose down .
```
## Addons : 
In project repository :
```bash 
mkdir odoo;
cd odoo;
git clone <addon_remote_repository>
```
