<p align="center"><img width="250" height="250" src="https://github.com/jgphilpott/docker-images/blob/master/icon.jpeg"></p>

# Intro

A [Docker Image](https://docs.docker.com/glossary/#image) is a layered collection of software packages used to create a [Docker Container](https://docs.docker.com/glossary/#container). Only software packages installed on an image will be available for use inside the corresponding container.

# Contents

### [Flask Series](https://hub.docker.com/r/jgphilpott/flask-pack)

A collection of software packages commonly used in Flask applications.

 - [Flask Pack Mini](https://github.com/jgphilpott/docker-images/tree/master/flask-series/flask-pack-mini) - The lightweight version.
 - [Flask Pack Base](https://github.com/jgphilpott/docker-images/tree/master/flask-series/flask-pack-base) - The standard version.
 - [Flask Pack Plus](https://github.com/jgphilpott/docker-images/tree/master/flask-series/flask-pack-plus) - The heavy duty version.

### [Pi Series](https://hub.docker.com/r/jgphilpott/pi-pack)

A collection of software packages commonly used in Raspberry Pi projects.

 - [Pi Pack Mini](https://github.com/jgphilpott/docker-images/tree/master/pi-series/pi-pack-mini) - The lightweight version.
 - [Pi Pack Base](https://github.com/jgphilpott/docker-images/tree/master/pi-series/pi-pack-base) - The standard version.
 - [Pi Pack Plus](https://github.com/jgphilpott/docker-images/tree/master/pi-series/pi-pack-plus) - The heavy duty version.

# Publishing

If you need any help publishing your docker images to [Docker Hub](https://hub.docker.com) read [this](https://docs.docker.com/docker-hub/repos) or see the steps below. For publishing docker images to [GitHub](https://github.com) read [this](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-docker-registry).

### Step 1 - Login

`docker login`

### Step 2 - Build Image

`docker build . -t <IMAGE_NAME>`

### Step 3 - Tag Image

`docker tag <IMAGE_ID> <USERNAME>/<REPOSITORY>:<TAG>`

### Step 4 - Push Image

`docker push <USERNAME>/<REPOSITORY>:<TAG>`
