# Nodejs-application-as-a-container-provisioned-via-ansible

This repo is used to showcase the deployment of a nodejs-based application as a container to a test server. Here we use 2 ec2-instance, one to build the docker container and push it to the docker-hub and the other is to run a container pulled from the docker hub. Make sure you enter the private IP of the ec2-instance in the hosts file and also enter docker account credentials in passwd.vars as well.
<br />
I've used a simple hello world node-js Dockerfile from my [Github-node-js-repo](https://github.com/Chris-luiz-16/Simple-Nodejs-Hello-world-Docker-image-and-container-build) for demo purposes. You can use your own repo by changing the vars file nodejs.yml playbook


## Sample output
***
https://github.com/Chris-luiz-16/Nodejs-application-as-a-container-provisioned-via-ansible/assets/128575317/1cabed9d-d39b-40b0-a47b-d28acdc78917

