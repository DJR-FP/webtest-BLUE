# webtest-BLUE

# 8582

docker pull donamato/blue:latest

docker run -d -p 8582:80 donamato/blue

--

docker ps -a

docker image ls


docker run -d -p 8581:80 donamato/red

docker run -d -p 8582:80 donamato/blue

docker run -d -p 8583:80 donamato/green

http://192.168.103.20:8581/

http://192.168.103.20:8582/

http://192.168.103.20:8583/







