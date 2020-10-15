# App-Home-Assistant

## Running the Containers

1. Update the following mount point in [docker-compose.yml](./Docker/docker-compose.yml)
  - `../Data/homeassistant:/config`
2. Run `docker-compose -f ./Docker/docker-compose.yml up -d`

## First Time Setup

1. Visit <http://your-ip:8123>
2. Configure Home Assistant According to its [documentation](https://www.home-assistant.io/docs/configuration/)
3. Consider copying the configuration file and updating the docker compose file to load the configuration file
