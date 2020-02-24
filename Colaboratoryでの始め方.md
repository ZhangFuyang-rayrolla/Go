### 環境設定

```go
//Install
!apt-get install golang

//version check
!go version

%%writefile helloworld.go
package main

import "fmt"

func main() {
    fmt.Printf("Hello World\n")
}

!go run helloworld.go

```

