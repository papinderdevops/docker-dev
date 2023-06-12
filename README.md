# docker-dev
docker for development
docker-compose up -d

control & ubuntu are two docker container

on control container run below command
$ ssh-keygen 
$ ssh-copy-id ubuntu

now you can ssh ubuntu container using ssh without password
$ ssh ubuntu

default username and password
user = root
password: password

to check ip 
$ ifconfig
end
