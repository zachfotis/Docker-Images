# Docker Images for various Projects

## Docker Compose Specifications

Check out the [Docker Compose](https://docs.docker.com/compose/compose-file/) documentation for more details.

- build: specifies the build configuration for creating container image from source

  ```yaml
  build: YOUR_PATH
  ```

- image: specifies the image to be used for creating container

  ```yaml
  image: YOUR_IMAGE
  ```

- container_name: specifies the name of the container

  ```yaml
  container_name: YOUR_CONTAINER_NAME
  ```

- ports: specifies the port mapping between host and container

  ```yaml
  ports:
    - 'HOST_PORT:CONTAINER_PORT'
  ```

- volumes: specifies the volume mapping between host and container

  ```yaml
  volumes:
    - 'HOST_PATH:CONTAINER_PATH'
  ```

- networks: specifies the network to be used for container

  ```yaml
  networks:
    - YOUR_NETWORK
  ```

- environment: specifies the environment variables to be used for container

  ```yaml
  USERNAME_VAR: YOUR_USERNAME
  ```

- depends_on: specifies the dependency between containers

  ```yaml
  depends_on:
    - YOUR_CONTAINER
  ```

- restart: specifies the restart policy for container

  ```yaml
  restart: always
  ```

- command: specifies the command to be executed when container starts

  ```yaml
  command: YOUR_COMMAND
  ```

- links: specifies the link between containers

  ```yaml
  links:
    - YOUR_CONTAINER
  ```

- labels: specifies the labels to be used for container

  ```yaml
  labels:
    - YOUR_LABEL
  ```
