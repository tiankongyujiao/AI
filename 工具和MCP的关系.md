在 Agent 里：

Tool只是：

给模型看的能力描述。

例如：
```
{
 "name":"read_file",
 "description":"Read file from project",
 "parameters":{
   "path":"string"
 }
}
```

这只是：

schema

不是代码。

真正代码在：

MCP server
或
本地工具实现

所以：

Tool是：

能力声明

不是：

能力实现

这是关键。
