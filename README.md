
```sh
GO111MODULE=on go mod init main
GO111MODULE=on go get github.com/kentakozuka/go-module-hello@v2.0.0
GO111MODULE=on go get github.com/kentakozuka/go-module-hello@v1.0.0
```


```sh
GO111MODULE=on go get github.com/kentakozuka/go-module-sample/new
GO111MODULE=on go get github.com/kentakozuka/go-module-sample/old
```

```sh
GO111MODULE=on go run ./main.go
```
