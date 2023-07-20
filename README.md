# docker-dev
docker for development
docker-compose up -d

control Linux & ubuntu are 3 docker container

Linux is AmazonLinux2 image

on control container run below command
$ ssh-keygen 
$ ssh-copy-id ubuntu  or Linux

now you can ssh ubuntu container using ssh without a password
$ ssh ubuntu
$ shh Linux
default username and password
user = root
password: password

to check ip 
$ ifconfig
end
