## Markdown基础语法总结

### 1. 标题设置(改变标题字体大小)
#### 在Markdwon中设置标题有两种方法:
##### 1. 通过在文字下方添加'-','='实现，分别表示一级标题和二级标题
##### 2. 通过在文字开头添加'#'实现，'#'的数量代表标题的级数，级数越大字体越小
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
### 2. 块注释
#### 通过在文字开头添加">"表示块注释。（当>和文字之间添加五个blank时，块注释的文字会有变化。）
>块注释 

### 3. 斜体
#### 将需要设置为斜体的文字或者字符首尾两端用一个' * ' 或者' _ '括起来
*斜体*
### 4. 粗体
#### 将需要设置为粗体的文字或者字符首尾两端用两个' * '或者' _ '括起来
**粗体**
### 5. 无序列表
#### 在文字开头添加 星号，+ , -实现无序列表。但是要注意在星号 , + , -和文字之间需要添加空格。（建议：一个文档中只是用一种无序列表的表示方式）
- 无序列表1
- 无序列表2
- 无序列表3
### 6. 有序列表
#### 在文字开头添加数字和英文句号，同理在句号和文字之间用一个空格隔开
1. 有序列表1
2. 有序列表2
3. 有序列表3
### 7. 网页链接
#### Markdown中有两种链接方式，分别为内联方式和引用方式
##### 1. 内联方式:
    this is an [website link](https://www.shuqingzheng.com)
##### 2. 引用方式
    I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3].
    [1]: http://google.com/        "Google"
    [2]: http://search.yahoo.com/  "Yahoo Search"
    [3]: http://search.msn.com/    "MSN Search"
this is an [website link](https://www.shuqingzheng.com)

I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3].
[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"

### 8. 图片的处理方式和链接的处理方式，只是在[ ]前加了一个！
    内联方式：![alt text](C:\Users\jeek\Pictures\Saved Pictures\九九.jpg "Title")
    引用方式：
    ![alt text][id]

     [id]: C:\Users\jeek\Pictures\Saved Pictures\九九.jpg "Title"

    problem:路径不能有空格？
![alt text](C:\Users\jeek\Pictures\Saved Pictures\九九.jpg "Title")
### 9. 代码块
    1. 对于简短的文字或者代码使用' `< code >` '(注意最外面的符号是用ESC下面的按键打出来的)
    2. 对于大量的文字或者多行代码使用四格空格键缩进或者一个Tab键

### 10. 脚注
    hello[^hello]

    [^hello]:hi
hello[^hello]

[^hello]:hi
### 11. 下划线
#### 在空白行下方使用三个' - '实现效果
---
