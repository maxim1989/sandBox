https://docs.docker.com/compose/

### GOAL
Docker Compose is a tool for defining and running multi-container applications. It is the key to unlocking a streamlined and efficient development and deployment experience.

### PLUSES
1) Simplified control - allows you to define and manage multi-container applications in a single YAML file
2) Efficient collaboration - easy to share, facilitating collaboration among developers, operations teams, and other stakeholders
3) Rapid application development - Compose caches the configuration used to create a container. When you restart a service that has not changed, Compose re-uses the existing containers. Re-using containers means that you can make changes to your environment very quickly
4) Portability across environments - Compose supports variables in the Compose file. You can use these variables to customize your composition for different environments, or different users.
5) Extensive community and support

### Key commands
To start all the services defined in your compose.yaml file: ```docker compose up```. To stop and remove the running services: ```docker compose down```. If you want to monitor the output of your running containers and debug issues, you can view the logs with:```docker compose logs```. To lists all the services along with their current status:```docker compose ps```.


### 
docker image ls - images list
docker inspect <tag or id>

### run with watch
```docker compose watch``` or ```docker compose up --watch```
