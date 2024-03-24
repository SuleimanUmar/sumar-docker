# Welcome to Docker

This is a personal Docker project repository.

### Quick Start

Run the following command:
```
docker run -d -p 8088:80 --name welcome-to-docker docker/welcome-to-docker
```
Then visit `http://localhost:8088` in your browser.


Build and run:
```
docker build -t welcome-to-docker . 
docker run -d -p 8088:3000 --name welcome-to-docker welcome-to-docker
```
Visit `http://localhost:8088` in your browser.

This README serves as a guide for personal experimentation and learning.