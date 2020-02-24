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

### 学習まとめサイト
-Go言語の初心者が見ると幸せになれる場所　#golang

https://qiita.com/tenntenn/items/0e33a4959250d1a55045
