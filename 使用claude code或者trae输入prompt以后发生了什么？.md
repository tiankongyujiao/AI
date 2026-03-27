使用claude code或者trae输入prompt以后发生了什么？

比如我指定一个文件，让他帮我修改某个函数，claude code执行的过程中会提示：Read 3621 lines

读取的这个操作不是大模型做的，大模型本身没有读取文件的能力，读取文件的是 Agent（Claude Code / Trae / Cursor / OpenClaw），不是模型。Agent调用本地工具做的。

模型本身只能看到一段文本，是Agent组织好的prompt，Agent也会根据模型参数觉得是否把所有读取到的内容都作为prompt发给大模型。



