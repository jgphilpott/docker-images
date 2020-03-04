<p align="center">
  <img width="200" height="200" src="https://github.com/jgphilpott/docker-images/blob/master/icon.jpeg">
</p>

# Intro

A [Docker Image](https://docs.docker.com/glossary/#image) is a layered collection of software packages used to create a [Docker Container](https://docs.docker.com/glossary/#container). Only software packages installed on an image will be available for use inside the corresponding container.

# Contents

### Flask Series

A collection of software packages commonly used in Flask applications.

 - [Flask Pack Mini](https://github.com/jgphilpott/docker-images/tree/master/flask-pack-mini#flask-pack-mini) - The lightweight version.
 - [Flask Pack](https://github.com/jgphilpott/docker-images/tree/master/flask-pack#flask-pack) - The standard version.
 - [Flask Pack Plus](https://github.com/jgphilpott/docker-images/tree/master/flask-pack-plus#flask-pack-plus) - The heavy duty version.

### Pi Series

A collection of software packages commonly used in Raspberry Pi projects.

 - [Pi Pack Mini](https://github.com/jgphilpott/docker-images/tree/master/pi-pack-mini#pi-pack-mini) - The lightweight version.
 - [Pi Pack](https://github.com/jgphilpott/docker-images/tree/master/pi-pack#pi-pack) - The standard version.
 - [Pi Pack Plus](https://github.com/jgphilpott/docker-images/tree/master/pi-pack-plus#pi-pack-plus) - The heavy duty version.

# Publishing

If you need any help publishing your docker images to the [GitHub Package Registry](https://github.com/features/packages) read [this](https://towardsdatascience.com/setting-up-github-package-registry-with-docker-and-golang-7a75a2533139) or see the steps below.

### Step 1 - Login

`sudo docker login docker.pkg.github.com --username <USERNAME> -p <GITHUB_TOKEN>`

### Step 2 - Build Image

`sudo docker build . -t <IMAGE_NAME>`

### Step 3 - Tag Image

`sudo docker tag <IMAGE_ID> docker.pkg.github.com/<USERNAME>/<REPOSITORY>/<IMAGE_NAME>:<VERSION>`

### Step 4 - Push Image

`sudo docker push docker.pkg.github.com/<USERNAME>/<REPOSITORY>/<IMAGE_NAME>:<VERSION>`
