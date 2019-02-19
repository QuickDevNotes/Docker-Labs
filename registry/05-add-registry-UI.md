# Adding a User Interface to our Registry 

In this lab session we will learn about how we can set a clean user interface for our Registry.

- Run the following command to add a frontend to registry
```
docker run \
  -d \
  -e ENV_DOCKER_REGISTRY_HOST=YOUR-REGISTRY-HOST \
  -e ENV_DOCKER_REGISTRY_PORT=5000 \
  -p 8080:80 \
  konradkleine/docker-registry-frontend:v2
```
- Open a browser and go to **http://REGISTRY-HOST-IP:8080/**
- Provide login username and password for the registry that we had configured for [basic authentication]()

