# Linux - Nginx - PostgreSQL - PHP environment for Docker

#### PHP Extensions included
`curl`, `gd`, `imagick`, `intl`, `json`, `mbstring`, `mysqli`, `opcache`, `pdo_pgsql`, `xdebug`, `xsl`, `zip`

#### Setup

`.docker/postgres/initdb.d` - put shell scripts and sql dumps into this folder to apply them on container start.  

To start container run in console

```
docker-compose up -d
```

To stop container run in directory of this repo
```
docker-compose down
```
