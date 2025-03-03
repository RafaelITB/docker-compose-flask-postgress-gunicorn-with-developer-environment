## Docker Setup for VNC and VSCode

### Default Credentials for every service

- **User**: `rgs`
- **Password**: `sjo`


### Building the Docker Image

Download the repo and run the following command in the same directory:
```
docker-compose up --build
```

### Important Notes

- vnc port : `5901`
- postgre port : `5432`
- flask website port: `5000`

- flask files can be found in `/var/www/html`
- database files can be found in `/var/lib/postgresql/data`
- data base name is `appdb`
---
