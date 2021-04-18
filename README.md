# parent-docker

First install nginx and docker 

then create a folder "code" in ubuntu home directory

mkdir -p /home/ubuntu/code

cd /home/ubuntu/code

Then clone all 5 repositories

git clone https://github.com/dcherif/app1

git clone https://github.com/dcherif/app2

git clone https://github.com/dcherif/app3

git clone https://github.com/dcherif/app4

git clone https://github.com/dcherif/app5

Then we can check inside code folder app1 app2 app3 all are presents. 
If we want to keep this folder in different folder then we have to change the path in docker-compose file

then do "docker-compose up -d" .

It will start at port 81. Then you need to proxy pass in nginx to port 81
