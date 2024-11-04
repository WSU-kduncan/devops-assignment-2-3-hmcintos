# DevOps Assigment 2 - GitHub Actions & DockerHub

## Description of Workflow
A commit gets pushed to the repo

              |
              V
              
Then set up java and the correct OS 

              |
              V
              
Then we execute the gradle build

              |
              V
              
Then we copy the jarfile and change its name to app.jar

              |
              V
              
we copy all .jar files except for pkain in the name to the directory

              |
              V
              
We make the jar accesible to the next job 

              |
              V
              
We then build and push the docker image

## Link to DockerHub Repository
[https://hub.docker.com/r/hmcintosh1472/mcintosh-wopro-service/tags]

## Link to GitHub Actions Run Results Summary
[Link to **working** workflow run results]https://github.com/WSU-kduncan/devops-assignment-2-3-hmcintos/actions/runs/11655812409
