# homelab - influxdb
Homelab docker containers

## Create data volume
docker volume create influxdb_data

## Variable overrides
- INFLUXDB_DB=telegraf
- INFLUXDB_USER=telegraf
- INFLUXDB_ADMIN_ENABLED=true/false
- INFLUXDB_ADMIN_USER=xxx
- INFLUXDB_ADMIN_PASSWORD=xxx
