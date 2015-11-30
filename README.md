docker-nodejs-hello-world
====
This is a simple hello world web application using Node.js and Express framework built on Docker.

## Requirement
- Docker

## Usage
1. Build the Docker image: `docker build -t nodejs-hello-world .`
2. Run the Docker image: `docker run -d -p 80 --name helloworld nodejs-hello-world`
3. Check the port: `docker port helloworld`
4. Access the hello world web application: `curl http://localhost:<port>/`
  - if you are using Docker Toolbox: `open http://$(docker-machine ip default):<port>/`

## License
[MIT](https://github.com/asakaguchi/docker-nodejs-hello-world/blob/master/LICENSE)
