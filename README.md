Find the Docker image for the TodoApp application at [shcherbanvasyl499/todoapp](https://hub.docker.com/r/shcherbanvasyl499/todoapp)

import docker

# Build the Docker image
docker build -t todoapp:1.0.0 .
# Open web browser on your machine 
# Run the Docker container using the following command:
docker run -p 8080:8080 --name todoapp todoapp:1.0.0

# Open web browser on your machine 
http://localhost:8080


