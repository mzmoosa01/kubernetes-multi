# k8s-multi tutorial exercise

This is a tutorial project created to lear how to deploy a multi-containter application to kubernetes. It was created under the guidance of
[Steven Grider's Udemy course](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/?src=sac&kw=docker+kubernetes+complete)
This project also uses Travis CI to run automated tests and automatically deploy updates to amazon AWS.

# Getting started

You can test and get the application up and running by simply running docker-compose: 

``` docker-compose up ```
 
 or by using Docker run 

```
docker build -t <image-tag> -f Dockerfile.dev
and then
docker run <image-tag>
```
     
# Deployment 

Once code is committed to the master branch it will automatically be deployed to Amazon AWS via Travis CI. 
