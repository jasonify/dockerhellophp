

Build docker
```
docker build -t hello-php .
```


Run on port 80:

```
docker run -p 80:80 hello-php
```


NOTE: must run build if modify unless doing this (with full path)

docker run -p 80:80 -v  ~/playground/dockers/myphp/src:/var/www/html/  hello-php

