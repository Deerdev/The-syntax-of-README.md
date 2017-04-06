The-syntax-of-write-the-.md-file
=================================

# how to write README.md file
[Writing on GitHub](https://help.github.com/articles/writing-on-github#task-lists)

[Markdown Basics](https://help.github.com/articles/markdown-basics)

[GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)
#标题的级数
##标题的级数2
###标题的级数3
####标题的级数4
#####标题的级数5

## 使用倾斜字体
*主要介绍 如何设置渐进，渐进填充*
## 加粗字体
**画了渐进填充的椭圆 和 渐进填充的直线**
## 加粗字体和倾斜字体混输
**画了渐进 _填充的椭圆_ 和 渐进填充的直线**

## 插入图片(url)

<img heigh="500px" width="500px" src ="http://ww4.sinaimg.cn/bmiddle/6c9594a0jw1egkqlcgb8bj218g18gwsw.jpg">

## 嵌入列表
- [ ] 画图
  - [ ] 椭圆
  - [ ] 线条
  - [x] 矩形

## 分点，条目
* Item1
* Item2
* Item3

- Item1
- Item2
- Item3

1. Item1
2. Item2
3. Item3

# 索引目录
## 目录

* [QPainter](#QPainter)
  * [矩形](#矩形)
  * [椭圆](#椭圆)
  * [线条](#线条)
  * [渐变](#渐变)


# QPainter

### 矩形
* 画一个矩形

### 椭圆
* 画一个椭圆

### 线条
* 画一个线条

### 渐变
* 使用渐变填充

#### 黑块
`[我是一个黑块]`

#### 代码行：
```
$sudo apt-get install vim-gnome
```

#### 代码块：
```C++
@Sweetfish
/*this is a test
#include <iostream>
using namespace std;

int main()
{
    cout << "hello world!" << endl;
    return 0;
}
```

#### 流程图（不支持）

```flow
st=>start: Start:>https://www.zybuluo.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```

##### [流程图语法](http://adrai.github.io/flowchart.js/)
#### 序列图(不支持)
##### 示例 1

```seq
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

##### 示例 2

```seq
Title: Here is a title
A->B: Normal line
B-->C: Dashed line
C->>D: Open arrow
D-->>A: Dashed open arrow
```

##### 更多语法参考：[序列图语法参考](http://bramp.github.io/js-sequence-diagrams/)
#### 表格

示例：

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机     | $1600 |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |

#### 定义型列表

名词 1
:   定义 1（左侧有一个可见的冒号和四个不可见的空格）

代码块 2
:   这是代码块的定义（左侧有一个可见的冒号和四个不可见的空格）

        代码块（左侧有八个不可见的空格）

#### 标签分类

在编辑区任意行的列首位置输入以下代码给文稿标签：

标签： 数学 英语 Markdown

或者

Tags： 数学 英语 Markdown

#### 删除线

使用 ~~ 表示删除线。

~~这是一段错误的文本。~~

#### 文字引用

使用 > 表示文字引用。

示例：

> 野火烧不尽，春风吹又生。

#### 行内代码块

使用 \`代码` 表示行内代码块。

示例：

让我们聊聊 `html`。

#### 代码块

使用 四个缩进空格 表示代码块。

示例：

    这是一个代码块，此行左侧有四个不可见的空格。


#### 注脚（不支持）

使用 [^keyword] 表示注脚。

这是一个注脚[^footnote]的样例。

这是第二个注脚[^footnote2]的样例。



[^footnote]: 这是一个 *注脚* 的 **文本**。

[^footnote2]: 这是另一个 *注脚* 的 **文本**。
