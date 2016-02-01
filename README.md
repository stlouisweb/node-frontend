# node-frontend
Docker Image with NodeJS, Express and React.

### Usage

1. Clone this repository
2. `docker build .`
3. `docker images` to get the id of the image you just created (optional tag the image when you [build it](https://docs.docker.com/engine/reference/commandline/build/))
4. 'docker run --name node-frontend -p 8080:8080 -d {image id}`
