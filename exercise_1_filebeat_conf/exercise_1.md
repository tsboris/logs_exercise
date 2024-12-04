# Elastic Stack Exercise 1
In this exercise, you will start with a simple Filebeat configuration and add three log parsing configurations:
1. Parse Nginx Access logs
2. Parse Nginx Error logs
3. Parse Python logs (with multiline support for Tracebacks)

The end goal is to have all the logs in json format and each part of the log message is a field in the json.

## Need to know
Because we are ingesting the logs from a text file and NOT from a data stream, for every change in filebeat.yml, you will need to run the following command to delete all volumes and start from new:
```shell
docker compose down -v
```

## Commands
```shell
# Files location
cd ~/develeap/seniority/log_analysis/elastic_stack/exercise_1_filebeat_conf

# Start docker compose
docker compose up --build

# Stop docker compose
docker compose down

# Or, stop docker compose and delete all volumes
docker compose down -v
```

## Kibana login
[http://localhost:5601](http://localhost:5601)  
**User:** elastic  
**Pass:** password
