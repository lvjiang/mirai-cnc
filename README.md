# mirai-cnc
my mirai cnc



**编译linux**

```
go build -o mirai-cnc.exe ./*.go
```



**编译window**

```shell
CGO_ENABLED=0 GOOS=windows GOARCH=amd64 go build -o mirai-cnc.exe ./*.go
```

