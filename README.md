# cson
CShape KeyValue Syntax for Object Notation

## 什么是CSON？
CSON是一个纯文本的可读的Key-Value形式的数据结构标记方式，就和JSON，XML作用一样。CSON被设计成和JSON百分之一百兼容，且可简单的相互转换。

## 为什么设计CSON?
JSON是一个十分完美的数据结构标记方式，但是仍然存在一些不足。例如JSON序列化和反序列化性能无法满足一些系统的苛刻要求；还有例如JSON在广泛应用的Key-Value储存系统如radis，需要增加无用的Key数据，获取值必须要整体读取JSON文本等等。

## 为什么使用CSON?
CSON提供了一种比较便利的方式，来提高JSON的性能扩展JSON的使用范围，例如日志这种顺序系统，CSON比JSON有更好的性能，更佳的分析效率，更节省的储存空间。

## Example 1
一个简单的例子，对比CSON和JSON形式

#### CSON

```
id, 1
name, A green door
price, 12.50
tags:0, home
tags:1, green
```

#### JSON

```json
{
    "id": "1",
    "name": "A green door",
    "price": "12.50",
    "tags": [ "home", "green" ]
}
```

---
