# Docker-React
![Docker-React]

### [Live Site]  http://dockerreact-env.eba-zsfqauqq.us-east-2.elasticbeanstalk.com/

## Introduction
This is a code repository for the docker-react application. 

In this repo , we have flow from Git -> travis ci -> AWS . 

By the end of this tutorial, you will have a strong understanding of React's workflow and  deploye in the AWS.

Setup:
- run ```npm i && npm start```




### Build command 
docker build . -t nitinrai17/docker-react


### Run command 
docker run -p 3033:80 --name docker-react  nitinrai17/docker-react 

