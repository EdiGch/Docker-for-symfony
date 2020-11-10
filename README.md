# Commands

##### Image Search Cli

```docker search mysql```

##### Downloading the image without loading the container at the same time.
```docker pull mysql```
##### Display detailed information about the image
``` docker inspect mysql```
``` docker inspect db2b37ec6181```

##### Deleting a container
```docker rm 550e01740d26```
```docker ps -a```

#### Run containers
```docker-compose up -d --build```
or
```docker-compose build```
```docker-compose up```
#### Stop and down containers
```docker-compose stop```
```docker-compose down```
#### Listing:
##### Listing images
```docker images```
##### Listing of active containers
```docker ps```
##### Listing (inactive) containers with status Exited
```docker ps -a```
##### Information about the last closed container
```docker ps -l```