# NATS ACL Configuration Proxy

### Getting started

```sh
go get -u github.com/nats-io/nats-acl-config-proxy
```

### Usage

```sh
$ nats-acl-config-proxy -h
```

### Developing

```sh
# Build locally using Go modules
$ GO111MODULE=on go run cmd/nats-acl-config-proxy/main.go

[57919] 2019/02/08 13:17:12.713611 [INF] Starting nats-acl-config-proxy v0.0.1
[57919] 2019/02/08 13:17:12.713936 [INF] Listening on 0.0.0.0:4567

# To run the tests
$ go test ./... -v
```

### License

Unless otherwise noted, the NATS source files are distributed under the Apache Version 2.0 license found in the LICENSE file.
