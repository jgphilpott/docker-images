<p align="center">
  <img width="250" height="250" src="https://github.com/jgphilpott/docker-images/blob/master/icon.jpeg">
</p>

# Intro

A [Docker Image](https://docs.docker.com/glossary/#image) is a layered collection of software packages used to create a [Docker Container](https://docs.docker.com/glossary/#container). Only software packages installed on an image will be available for use inside the corresponding container.

# Contents

### [Flask Series](https://hub.docker.com/r/jgphilpott/flask-pack)

A collection of software packages commonly used in Flask applications.

 - [Flask Pack Mini](https://github.com/jgphilpott/docker-images/tree/master/flask-pack-mini#flask-pack-mini) - The lightweight version.
 - [Flask Pack Base](https://github.com/jgphilpott/docker-images/tree/master/flask-pack-base#flask-pack-base) - The standard version.
 - [Flask Pack Plus](https://github.com/jgphilpott/docker-images/tree/master/flask-pack-plus#flask-pack-plus) - The heavy duty version.

### [Pi Series](https://hub.docker.com/r/jgphilpott/pi-pack)

A collection of software packages commonly used in Raspberry Pi projects.

 - [Pi Pack Mini](https://github.com/jgphilpott/docker-images/tree/master/pi-pack-mini#pi-pack-mini) - The lightweight version.
 - [Pi Pack Base](https://github.com/jgphilpott/docker-images/tree/master/pi-pack-base#pi-pack-base) - The standard version.
 - [Pi Pack Plus](https://github.com/jgphilpott/docker-images/tree/master/pi-pack-plus#pi-pack-plus) - The heavy duty version.

# Publishing

If you need any help publishing your docker images to [Docker Hub](https://hub.docker.com) read [this](https://docs.docker.com/docker-hub/repos) or see the steps below.

### Step 1 - Login

`sudo docker login`

### Step 2 - Build Image

`sudo docker build . -t <IMAGE_NAME>`

### Step 3 - Tag Image

`sudo docker tag <IMAGE_ID> <USERNAME>/<REPOSITORY>:<TAG>`

### Step 4 - Push Image

`sudo docker push <USERNAME>/<REPOSITORY>:<TAG>`
