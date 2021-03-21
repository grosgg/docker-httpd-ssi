# docker-httpd-ssi
Apache server with SSI enabled

## Run
```
docker run -dit --name my-apache-ssi -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ grosgg/apache-ssi
```
