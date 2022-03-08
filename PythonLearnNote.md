# Python学习笔记

## 1. Python 简介

### 1.1 什么是Python

Python是一门跨平台的编程语言，可以在各种平台上运行。

### 1.2 Python的关键字和标识符

#### 1.2.1 关键字

关键字是Python保留字，不能用来作为变量名，函数名，以及其他任何标识符。这些关键字被用来定义Python的语法和结构。

在Python中，关键字是大小写敏感的。

在Python3.7中，共有33个关键字，后续版本关键字的数量可能会有变化。

所有关键字都是小写的，除了`True`，`False`，`None`以外。

以下是Python3.7的关键字：

`False`，`await`，`else`，`import`，`pass`，`None`，`break`，`except`，`in`，`raise`，`True`，`class`，`finally`，`except`，`is`，`return`，`and`，`continue`，`for`，`lambda`，`try`，`as`，`def`，`from`，`nonlocal`，`while`，`assert`，`del`，`global`，`not`，`with`，`async`，`elif`，`if`，`or`，`yield`

#### 1.2.2 标识符

标识符是给类、函数、变量等实体的名称，有助于区分不同的实体。

##### 标识符命名规则

- 大小写字母、数字和下划线的组合；
- 不能以数字开头；
- 不能用关键字作为表示符；
- 不能用特殊字符作为标识符；
- 标识符可以是任意长度的。

##### 切记

- 标识符大小写敏感；
- 应该用有意义的名称作为标识符；
- 应该用下划线来分割单词。

### 1.3 Python语句、缩进和注释

#### 1.3.1 语句

Python解释器能够执行的指令成为语句，如`a = 1`就是一条语句。

#### 1.3.2 多行语句

多行语句可以使用换行符`\`来扩展，大中小括号也可以实现多行语句，而不需要换行符。

#### 1.3.3 缩进

大多数编程语言都是用大括号来定义代码块，而Python就不一样，用缩进就OK了。

代码块（循环、函数等）以缩进开始，以第一个未缩进的行结束。尽量保持缩进一致。如：

```Python
for i in range(0, 10):
    print(i)
    if i == 5:
        break
```

#### 1.3.4 注释

Python的单行注释用`#`，多行注释用`"""`。如：

```python
# THis is a comment
# This is another comment

"""
This is a 
multi-line comment
"""
```

#### 1.3.4 文档字符串

文档字符串，简单来说就是一些说明性的东西，出现在函数、方法、类或者模块定义之后的地方。如：

```python
def function(num):
    """ This is a docstrings in function"""
    return num
```

### 1.4 Python变量

#### 1.4.1 变量

变量就是变量，不知道咋说，就是一个标识符，用来表示某个内存的数据，可以修改。如`number = 10`。

#### 1.4.2 给变量赋值

就是用`=`给某个变量赋予某个值。如`name = hmj`，`email = xxx@outlook.com`。

#### 1.4.2 常量

常量就是一种一旦赋予初始值之后就无法改变的量，常量一般用大写表示，下划线分割单词，一般单独放在某个文件中，要用的时候就导入即可。
