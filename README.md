# Start machine learning project

### Software :

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

creating conda environment :
```
conda create -p venv python==3.7 -y
```

activate virtual envirnment :
```
conda activate venv\
```
add files to git :
```
git add .
```
check status of git :
```
git status
```
check version maintened by git :
```
git log
```

to create version/commit all changed by git:
```
git commit -m "add comment"
```

To setup CICD pipeline we need 3 info :

1. Heroku email  - sachikapase6125@gmail.com
2. Heroku API_Key  - 0eb617c3-e12c-4b65-9803-f1459b5cb15d
3. Heroku App name  -  hello-world-api-key

Build docker image :
```
docler build -t <image_name>:<tagname> .
```
>Note: image name should be lowercase.

To list docker images :
```
docker iamges
```

Run docker image :
```
docker run -p 5000:5000 -e PORT=5000 d259a4ec2d27
```

To check the running container :
```
docker ps
```
To stop the docker app :
```
docker stop container id
```