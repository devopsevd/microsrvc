Read Me:
1) command for build.
#CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o microservice .

2) Add ca-certificates.crt to current folder: 
#cp /etc/ssl/certs/ca-certificates.crt .

3) Docker build
#docker build -t go_microservice .

4) Run container
#docker run -it --rm go_microservice
