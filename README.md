#README
## gs-rest-service

#grab the file from github

git clone https://github.com/Mancang-ops/gs-rest-service.git

#Build docker image

docker build -t java_rest .

#run docker image

docker run -d -p host_port:8090 java_rest
