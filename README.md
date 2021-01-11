### Go环境

<details>
<summary>Go安装</summary>
官网：https://golang.org/doc/install，下载安装go
然后在`.zshrc`或者`.bashrc`里面配置环境变量

```
# Go
export PATH=$HOME/bin:/usr/local/go/bin:$PATH
```
</details>

<details>
<summary>运行Go文档，在线预览文档</summary>

```bash
# 如果你的 godoc 命令不存在，运行它安装
$ go get -v  golang.org/x/tools/cmd/godoc

$ godoc -http=:6060
# 运行上面一条命令，可访问文档http://localhost:6060/
```

</details>

<details>
<summary>go命令运行简单.go程序</summary>

我们可以简单的写一个基础的`hello world`代码然后另存为[hello.go](./example/hello.go)

```go
package main
import "fmt"
func main() {
   fmt.Println("Hello, World!")
}

```
然后运行`go run hello.go`,就可以在终端看到`Hello, World!`
</details>

<details>
<summary>通过go命令编译运行</summary>

GO程序的代码是可以直接编译成`exe文件` 或者 `二进制文件`直接运行，在[hello.go](./example/hello/hello.go)目录下运行下面命令，即可把go程序编译成二进制文件

```bash
go build hello.go
```

上面命令文件可以编译成一个`hello`可执行文件，然后直接在当前目录下 `./hello` 运行，可以输出`hello world!`。

</details>

