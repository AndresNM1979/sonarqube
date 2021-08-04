# Start SonarQube in a docker container

Run these instructions

```bash
sudo sysctl -w vm.max_map_count=524288
sudo sysctl -w fs.file-max = 131072
docker-compose up -d
```
