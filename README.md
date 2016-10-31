# Docker LEMP

Docker Compose build scripts to create simple LEMP environment for local PHP 7 development

* Nginx
* PHP 7
* MariaDB
* phpMyAdmin

### Getting Started

Running the following command should bring the environment up

```bash
docker-compose up -d
```

### Notes

* Temporary/placeholder index page with `phpinfo()` dump so you can verify it's working
* Webroot gets mapped to `./public` folder in project
* Access webroot at [http://192.168.99.100](http://192.168.99.100)
* phpMyAdmin access at [http://192.168.99.100:8183](http://192.168.99.100:8183)
    * username: root
    * password: root
* **IMPORTANT** You must put this project somewhere under you Windows User folder (e.g. C:\Users\mike\containers\docker-lemp) as `docker-compose` only has access to your User folder in Windows
