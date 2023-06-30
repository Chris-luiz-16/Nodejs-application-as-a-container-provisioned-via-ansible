# Nodejs-application-as-a-container-provisioned-via-ansible

This repo is used to showcase the deployment of nodejs based application as a container to a test server. Here we use 2 ec2-instance, one to build the docker the container and push to the docker and the other is to run a container pulled from docker hub. Make sure you enter the private IP of the ec2-instance in hosts file and also endter docker account crediantials in passwd.vars as well
