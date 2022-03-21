# This is a simple golang GRPC example.

# Usage

1.Install protoc by yourself.

2.ProtoBuffer Definition: inside `myproto`

3.`make gen-proto` to generate go file from pb file

  ``` 
  --go_out=       生成 *.pb.go， 是序列化和反序列化的代码
   --go-grpc_out=      生成 *_grpc.pb.go，是GRPC通讯的代码
   ```
   

4. `make run-server`

5. `make run-client`

#工具链版本

```
#protoc --version
libprotoc 3.19.4
#go version
go version go1.17.5 darwin/amd64
```
