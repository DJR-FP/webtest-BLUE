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

webtest.dc1.fullproxylabs.com

red.dc1.fullproxylabs.com

blue.dc1.fullproxylabs.com

green.dc1.fullproxylabs.com



docker run -h blueboy -d -p 8582:80 donamato/blue

docker run -h redrum -d -p 8581:80 donamato/red

docker run -h GreenGoat -d -p 8583:80 donamato/green

docker run -h test-SSL -d -p 8181:443 donamato/ssl01:latest





