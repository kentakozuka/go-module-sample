
```sh
GO111MODULE=on go mod init
GO111MODULE=on go get github.com/kentakozuka/go-module-hello@v1.1.0
GO111MODULE=on go get github.com/kentakozuka/go-module-hello@v1.0.0
```


```sh
❯ cat go.mod
module github.com/kentakozuka/go-module-sample

require github.com/kentakozuka/go-module-hello v1.0.0 // indirect
```

```sh
GO111MODULE=on go run ./main.go
```
