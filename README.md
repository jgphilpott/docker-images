# Docker Images

If you need any help publishing your docker images to the GitHub Package Registry read [this](https://towardsdatascience.com/setting-up-github-package-registry-with-docker-and-golang-7a75a2533139) or see the steps below.

### Step 1 - Login

`sudo docker login docker.pkg.github.com --username <USERNAME> -p <GITHUB_TOKEN>`

### Step 2 - Build Image

`sudo docker build . -t <IMAGE_NAME>`

### Step 3 - Tag Image

`sudo docker tag <IMAGE_ID> docker.pkg.github.com/<USERNAME>/<REPOSITORY>/<IMAGE_NAME>:<VERSION>`

### Step 4 - Push Image

`sudo docker push docker.pkg.github.com/<USERNAME>/<REPOSITORY>/<IMAGE_NAME>:<VERSION>`
