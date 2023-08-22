# Bluefoxglove - Persistence
## Description
This repository contains the files necessary for the Persistence of the data used in the Bluefoxglove game. 

## Installation
Before install ensure that you meet the follwoing prerequisites
[] Installed Docker Desktop on your local machine.

### Run the Docker Compose command
In the project's directory, run the following command in the terminal of your choice
```
docker-compose up
```
### Create a Docker network
Enter the following command in your container in Docker Desktop
```
docker network create {NETWORK NAME}
```
### Once container is created and running, enter the Monog DB shell
Enter the following command in your container in Docker Desktop
```
mongosh
```
### Create the required Database and Collections
Once you have entered the Mongo shell, create the Database with the following command:
```
use {DATABASE NAME}
```

On success, you can then create the collection by running the following commands:
```
db.createCollection("{COLLECTION NAME}")
```
