# hello-world-php-docker

Containerlized PHP hello-world.

## Setup

Clone it.

```cd hello-world-php-docker```

Build image ```docker build -t hello-world-php .```

Run container ```docker run -p 80:80 -v /YOUR/DIR/hello-world-php-docker/src:/var/www/html/ hello-world-php```

Browse on localhost:80
