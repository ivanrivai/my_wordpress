# my_wordpress


> We use the Latest Wordpress and Mysql version.

## How to Use
- Simply run `docker-compose up -d`
- Visit `http://localhost`
- For technology stacks, see `docker-compose.yml`
- For scaling purposes, we can use built in function in docker-compose, `docker-compose up --scale wordpress=2 -d`
- Notice that in `docker-compose.yml`, in wordpress services, it is defined a ranged ports so that when we want to scale, docker can allocate to the defined ports
## Stack Version
To test new stack version (php, wordpress), open `docker-compose.yml` and adjust it accordingly. 
<br></br>
To destroy all containers, run `docker-compose down`