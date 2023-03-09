# 内容
makefile 内容的核心是一系列的规则，这些规则告知make程序要做的事，以及作这件事所依赖的条件。

# 格式

```
target:dependency
	command
```

target ：通常是要产生的文件的名称，目标的例子是可执行文件或目标文件；目标也可以是一个执行的动作名称，如clean

dependency：用来输入从而产生目标的文件，一个目标经常有几个依赖

command：命令行定义了规则的动作（如何根据依赖文件来更新目标文件）。命令行必须以tab键开始。

# 工作流程

# 变量

## 定义

变量名：= 值
```
dumpimage-makimage-objs := dumpimage.o
```
## 使用

```
$(dumpimage-makimage-objs)
```
## 追加内容

```C++
C_SRCC:=
C_SRCC+=test.c test2.c //将test.c test2.c添加到变量中
``` 

