# HAProxy Multiple Config Files
This example shows how to use multiple configuration files for HAProxy.  
The code is to complement my Medium article [Split HAProxy config into multiple files](https://medium.com/@edgars.voroboks/3f321d9dfb34).

# Try it yourself
Prerequisites: [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/install/) installed.

```bash
git clone https://github.com/NullIsNot0/haproxy-multiple-configfiles.git
cd haproxy-multiple-configfiles

# If you have Docker Compose version 1.x, run this:
docker-compose up

# If you have Docker Compose version 2.x, run this:
docker compose up
```

Open [http://localhost:3000](http://localhost:3000) for site01.  
Open [http://localhost:3001](http://localhost:3001) for site02.  
Open [http://localhost:4001](http://localhost:4001) for HAProxy stats page.  
