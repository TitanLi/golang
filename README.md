# golang

## Install
```shell
$ wget -q https://storage.googleapis.com/golang/getgo/installer_linux
$ chmod +x installer_linux
$ ./installer_linux
$ source ~/.bash_profile
$ go version
```

## Hello World
1. Create hello.go
> hello.go
```go
package main

import "fmt"

func main() {
	fmt.Printf("hello, world\n")
}
```
2. build
```shell
$ go build hello.go
```
3. exec
```shell
$ ./hello
```