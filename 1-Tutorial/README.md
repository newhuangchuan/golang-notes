# Introduction

## Hello,world

```shell
## cat sources-code/helloworld.go
```

```go
package main

import "fmt"

func main(){
    fmt.Println("Hello, World!!")
}
```

Go 是一门编译型语言，Go 语言的工具链将源代码及其依赖转换成计算机的机器指令（译注：静态编译）。Go 语言提供的工具都通过一个单独的命令 `go` 调用，`go` 命令有一系列子命令。最简单的一个子命令就是 `run`。这个命令编译一个或多个以。`.go` 结尾的源文件，链接库文件，并运行最终生成的可执行文件。

`main` 包比较特殊。它定义了一个独立可执行的程序，而不是一个库。在 `main` 里的 `main` *函数*也很特殊，它是整个程序执行时的入口（译注：C 系语言差不多都这样）。`main` 函数所做的事情就是程序做的。当然了，`main` 函数一般调用其它包里的函数完成很多工作.

