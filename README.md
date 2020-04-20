# 1988.taiwan

Base on https://github.com/1988-taiwan-gov-tw/1988.taiwan

## For Developer

### How to setup development environment

**Setup environment variables**

Create `.env` file base on `.env.example` file

**Startup docker container**

```
docker-compose up -d
```

**Restore data**

Using phpMyAdmin from `http://localhost:8080` and import `db.sql` into database which name is setted as `MARAIDB_DATABASE` value on `.env`

**Access wordpress**

`http://localhost`

### WordPress Admin

`http://localhost/wp-admin/`

Using `admin` as username and `admin` as passowrd to login wordpress admin.