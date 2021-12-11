docker commands:
----------------

1) docker --version
2) docker version --> will show all the client/server version options
3) docker ps  or docker container ls --> any containers are running
4) docker pull ubuntu --> downloading ubuntu from docker hub which is centralized repository for all the images
5) docker images
6) docker pull centos  and docker pull nginx
7) docker run -p 5000:5000 appname --> container port to host port 
8) docker runn -p 5000:5000 -d appname --> detached mode : means down show the logs run in background( will show only dockerappid)
9) docker logs (dockerappid)
10) docker logs -f (dockerappid) --> tailer logs
11) docker container ls -a --> both running and stopped containers
12) docker container stop (dockerappid)


