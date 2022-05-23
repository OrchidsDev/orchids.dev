# Overview


## init
```shell
# dir
mkdir api
mkdir app
mkdir cmd
mkdir internal
mkdir ui
mkdir config
mkdir migration
mkdir dist
mkdir deploy
mkdir template
mkdir web
mkdir doc

mkdir internal/date
mkdir internal/db
mkdir internal/dir
mkdir internal/file
mkdir internal/log
mkdir internal/queue
mkdir internal/uuid
mkdir internal/yaml
mkdir internal/toml
mkdir internal/redis
mkdir internal/git
mkdir internal/grpc
mkdir internal/http
mkdir internal/rabbit
mkdir internal/store

# go
go get -u github.com/go-redis/redis/v8
go get -u github.com/go-git/go-git/v5
go get -u google.golang.org/grpc
go get -u google.golang.org/protobuf
go get gopkg.in/yaml.v3
go get github.com/casbin/casbin/v2

# doc
cd doc

cd ..

# web
cd web
npm init
cd ..

```

## Dependencies
+ [Redis client for Go](https://github.com/go-redis/redis)
+ [go-git](https://github.com/go-git/go-git)
+ [Go support for Protocol Buffers](https://pkg.go.dev/google.golang.org/protobuf)
+ [gRPC-Go](https://pkg.go.dev/google.golang.org/grpc)
+ [YAML support for the Go language](https://github.com/go-yaml/yaml)
+ [Fiber is an Express inspired web framework](https://github.com/gofiber/fiber)
+ [Casbin](https://github.com/casbin/casbin)
+ [Gorilla WebSocket](https://github.com/gorilla/websocket)
+ [Gin Web Framework](https://github.com/gin-gonic/gin)
