# zoo-project
Docker file for Zoo-Project on centos 6.7

ZOO-Project is a WPS (Web Processing Service) open source project.

Links:

http://zoo-project.org/

https://hub.docker.com/r/yoms/zoo-project/


## Test launch
docker run -p 8888:80 zoo-project:latest
http://127.0.0.1:8888/cgi-bin/zoo_loader.cgi?request=GetCapabilities&service=WPS