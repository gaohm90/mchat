# 命令行的方式运行Chatgpt   基于GPT3.5接口
# 1.使用方法

### 1-1配置api key

+ 首次使用的时候需要配置 key 
```bash

chatgpt -key [Your Chatgpt Key]

```

### 1-2 询问方式
```bash
chatgpt -a 如何成为一个牛x的程序员
````

### 1-3 结果输出到文件中
	建议依.md结尾 （chatgpt返回的格式是 Markdown的，输出到Markdown中效果比较好）

```bash
chatgpt -a 生成Python入门的学习方法 -o py.md
```

# 安装方式
+ 下载对应平台的可执行文件
+ 将可执行文件放置到 $PATH 对应的目录中

Mac ：

下载对应平台可执行文件(chatgpt)

```bash

sodu mv chatgpt  /usr/local/bin/
 
```

Windows：

1.将下载文件（chatgpt.ext）放到  D:/chat/bin 目录(没有需要手动建一下这两个目录)中
2.将对应目录添加到Path中去

Linux：

下载对应平台可执行文件(chatgpt)

```bash

sodu mv chatgpt  /usr/local/bin/

```
