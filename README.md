# cson
CShape Syntax for Object Notation

## 什么是CSON？
CSON是一个纯文本的可读的Key-Value形式的数据结构标记方式，就和JSON，XML作用一样。CSON被设计和JSON百分之一百兼容，且可简单的相互转换。

## 为什么使用CSON?


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
