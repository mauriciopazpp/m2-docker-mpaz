![Build to use with](https://img.shields.io/static/v1?label=Build%20to%20use%20with&message=Magento%202&color=green) 
![Docker](https://img.shields.io/static/v1?label=For&message=Docker&&color=blue)
--- 
## Magento 2 Docker

Commands avaliable:
```bash
./docker/linux/install #Linux docker instalation 
```

```bash
./docker/start #Start the containers
```
```bash
./docker/stop  #Stop the containers
```
```bash
./docker/restart  #Restart the containers
```
```bash
./docker/kill  #Kill all the containers
```
```bash
./docker/shell  #Open the php shell
```

```bash
./docker/db   #Open the database shell
```
```bash
./docker/delete-db-file  #Copy the database to the db container
```
```bash
./docker/import-db  #Import the database outside the container, import the database, update the URL, and delete the database file from the db container
```
```bash
./docker/copy-db-file  #Copy the database file into the database container
```

```bash
./docker/update-magento-urls  #Update the magento URL
```

```bash
./docker/clean-folders  #Remove content from some folders, like var/view_preprocessed/*, pub/static/* etc...
```
```bash
./docker/grunt #Run grunt
```
```bash
./docker/grunt-init  #Grunt init
```

```bash
./docker/enable-xdebug #Enable xdebug on php container
```
