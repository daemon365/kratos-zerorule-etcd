# kratos-zerorule-etcd

## 使用方法

在 `go.mod` 中添加如下内容：
```go
replace github.com/go-kratos/kratos/contrib/registry/etcd/v2 => github.com/haiyux/kratos-zerorule-etcd v1.x.x
```

`v1.x.x` 为 https://github.com/haiyux/kratos-zerorule-etcd 的 [releases](https://github.com/haiyux/kratos-zerorule-etcd/releases) 版本


## 作用
- 用于解析go-zero注册到etcd的服务

## 缺点
1. 缺少version
2. 不支持register的meta信息传递

