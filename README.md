# MFADocker

This is a Multi-Factor-Authentication Web App based on flask which uses AWS RDS mysql db. 
The App runs on a docker container. 

Run below commands to create the docker image and then run the dokcer container(it will work after you have installed docker engine in your system): 
sudo docker build -t mfa .
sudo docker run -p 5000:5000 mfa
