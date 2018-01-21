# typo3-docker
Startingpoint to create a typo3 installation and fill it with data from an SQL Dump

Initialize:

```
  docker-compose up
```

Shut down:

```
  docker-compose down --volumes
 ```
 
 In order to fill the database with data when starting the containers create a `data` folder and add a `dump.sql`. It will be imported once the database was created.
