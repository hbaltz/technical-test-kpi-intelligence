# Technical test kpi intelligence
Candidates technical test https://www.kpi-intelligence.com/

## Requirement

* Docker : you can acces the installation documentation [here](https://docs.docker.com/install/)
* Docker Compose : you can find the installation guide [here](https://docs.docker.com/compose/install/)
* Have the 5000, 5432, 4200 port avaible

## Clone the repo with submodules
```bash
git clone --recurse-submodules -j8 https://github.com/hbaltz/technical-test-kpi-intelligence.git
```

## Launch the application
```bash
docker-compose up
```

## Use the application
Go to `localhost:4200`

## Stop the application
```bash
docker-compose down  
```