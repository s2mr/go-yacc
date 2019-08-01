# go-yacc

## Usage
足し算のみの構文解析に対応しています。

**Input**
```shell
goyacc  -o parser.go parser.go.y; go run parser.go "1+2"
```

**Output**
```
main.BinOpExpr{left:main.NumExpr{literal:"1"}, operator:43, right:main.NumExpr{literal:"2"}}
```
