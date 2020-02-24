### 環境設定

```go
//Install
!apt-get install golang

//version check
!go version

// export all contents from file
%%writefile helloworld.go
package main

import "fmt"

func main() {
    fmt.Printf("Hello World\n")
}


// print helloworld
!go run helloworld.go

```

