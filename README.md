# Introduction to gRPC

## What is RPC?

RPC stands for Remote Procedure Call.

## What gPRC?

# Try

```bash
❯ go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.27.1

❯ protoc -I. -Iinclude --go_out=module=github.com/k3forx/grpc-tutorial:. deepthought.proto
include: warning: directory does not exist.

❯ tree go/deepthought
go/deepthought
└── deepthought.pb.go
```
