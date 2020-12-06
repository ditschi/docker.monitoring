
# Monitoring

Templates for setting up a Monitoring.

A global .env file is used to configure users and passwords. 
Fot this, all docker-compose commands are run from the repo root (where the .env is located) and the docker-compose.yml is passed using the -f option.


## Server

Docker-compose for setting up monitoring server with Grafana, InfluxDB, Chronograf and Telegraf. 

## Agents
For this the address to the monitoring server (InfluxDB) has to be set (in the telegraf configuration).
Docker-compose for setting up monitoring for different agents (mainly with telegraf to publish data to InfluxDB)  
