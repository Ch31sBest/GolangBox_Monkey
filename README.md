# Pandora_Box

参考自猴书, 使用go语言编写的解释器


## 词法分析

1. 词法分析器

```go
package lexer

type Lexer struct {
	input        string // 输入的代码
	position     int  // 所输入的字符串中的当前位置(指向当前字符串)
	readPosition int  // 所输入的字符串中的当前读取位置(指向当前字符之后的前一个字符)
	ch           byte // 当前正在查看的位置
	// only support for the ascii char
}
```

2. REPL


