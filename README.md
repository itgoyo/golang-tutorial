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