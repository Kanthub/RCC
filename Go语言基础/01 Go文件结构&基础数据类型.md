```go
// 包声明
package main

// 引入包
import "fmt"

// 变量

// 整数和浮点数
var a uint8
var b int8
var c float32 =10.0

// 自动识别（:=）为float64
d :=10.0

// 复数
var e complex64 = 1 + 1.0i
// 自动推导为complex128
e1 := 1 + 1.0i
e2 := complex(1, 1.0)

// byte rune string
// byte = uint8, 字符串string可以直接转换为[]byte(byte 切片)
// []byte也可以直接转换成string
// rune = int32
// string 也可以直接转换成[]rune

var s string = "Go语言"
var bytes []byte = []byte(s)
var runes []rune = []rune(s)

fmt.Println("string length: ", len(s))
fmt.Println("bytes length: ", len(bytes))
fmt.Println("runes length: ", len(runes))

// 输出结果为 8 8 4， 因为string和[]byte是按照字节去定义，[]rune按照字符定义
// 一个汉字一般占3个字节，一个字母1个字节，所以前两个输出是8，最后一个输出是4

// 函数
//语句和表达式
//注释
```
