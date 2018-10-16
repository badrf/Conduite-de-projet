# TD6

Ce TD a pour objectif de :

* Utilisez le Docker


## Step 1: install docker and test

https://labs.play-with-docker.com/

    docker --version

    docker run hello-world

## Step 2: build a image

0) clone https://github.com/caohanyang/Conduite-de-projet

1) add your name in the html part of "app.py"

2) open "Dockerfile" and fullfill the missing lines

3) build the image with your own name

    docker build -t [yourName] .

4) show your image

    docker image ls

5) run the image in port 4000

    docker run ? ?

6) open browser and check

   http://localhost:4000


## Step 3: share a image
   
1) sign up and login

    docker login

2) tag the previous image

    docker tag [yourName] [username]/[repository]:[tag]

3) push the image

    docker push [username]/[repository]:[tag]


## Step 4: pull and run other's images

    docker run ? caohanyang/td6:1.1
