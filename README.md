# docker-wordpress
You can automatically deploy a local docker wordpress site
using the following commands:

``` bash
# Download a wordpress docker-compose example
git clone https://github.com/ericsonrumuy7/docker-wordpress.git
cd docker-wordpress/static-port
docker-compose up -d
```

Visit your site at <http://localhost:8000>

if you want it to be scalable, use docker-compose.yaml in dynamic-port directory, so the service can be scale up. you may put LB to balance the traffic.