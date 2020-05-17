# Go! Micro-service!

This project demonstrates this workflow:

- Establish micro-services by Go.
- Containerize services and use docker-compose as orchestration tool. 
- Generate K8S YAML settings and deploy to K8S server.

## RESTful API

- `go get -u github.com/labstack/echo/v4`

![Screenshot from Postman](https://user-images.githubusercontent.com/13026209/82154525-bf4a7400-9898-11ea-8db1-0d61f649a624.png)

## gRPC Server

- `go get -u google.golang.org/grpc`
- `script/install_protoc.sh`
- `go get -u github.com/golang/protobuf/protoc-gen-go`

![Screenshot from BloomRPC](https://user-images.githubusercontent.com/13026209/82154562-e9039b00-9898-11ea-8bef-f7ee476e39c2.png)
