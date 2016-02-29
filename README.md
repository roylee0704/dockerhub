## Introduction

A repository of my docker files. 

### Note

Before you build docker file, make sure you at the root folder that contains `Dockerfile`file.

i.e:
`cd my_mongodb`

## To Build
`sudo docker build -t roylee/my_mongodb .`

## To Run
`sudo docker run -name my_mongodb -it roylee/my_mongodb`

### Interactive bash 
`sudo docker run -name my_mongodb -it roylee/my_mongodb /bin/bash`
