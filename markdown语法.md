# 标题
**标题和符号间要有空格**

# h1
## h2
### h3
#### h4
#### h5
##### h6  

# 列表
1. 无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容
2. 有序列表使用数字并加上 . 号来表示


+ 加号1
+ 加号2
- 减号1
- 减号2
* 星号1
* 星号2
    + 二级1
    + 二级2

# 区块引用
- 在段落开头使用 > 符号 ，然后后面紧跟一个空格符号；
- 区块是可以嵌套的，一个 > 符号是最外层，两个 > 符号是第一层嵌套，以此类推：

> 第一层
>> 第二层
>>> 第三层
>>> - 区块中使用列表


- 列表中使用区块
    > 如果要在列表项目内放进区块，那么就需要在 > 前添加四个空格的缩进。


# 段落  
> 段落的换行是使用两个以上空格加上回车;
当然也可以在段落后面使用一个空行来表示重新开始一个段落。

# 斜体 粗体

*斜体文本,文字和符号间不能有空格*

_斜体文本_

**粗体文本**

__粗体文本__

***粗斜体文本***

___粗斜体文本___

# 代码

如果是文本中的一个函数或片段的代码可以用反引号把它包起来`console.log("hello md")`

**代码块使用```包裹或者代码区块使用 4 个空格或者一个制表符（Tab 键）**
```
//代码
```

    new Vue()

# 链接

    [链接名称](链接地址)
      或者
    <链接地址>

[我的主页](https://zccmynotebook.github.io/)

<https://zccmynotebook.github.io/>

# 高级链接
可以通过变量来设置一个链接，变量赋值在文档末尾进行；

这个链接用 1 作为网址变量 [Google][1]
这个链接用 runoob 作为网址变量 [Runoob][runoob]
然后在文档的结尾为变量赋值（网址）


[1]: http://www.google.com/
[runoob]: http://www.runoob.com/

# 图片
```
![alt 属性文本](图片地址)
![alt 属性文本](图片地址 "可选标题")
Markdown 还没有办法指定图片的高度与宽度，如果需要的话可以使用普通的 <img> 标签。

```


# 表格
使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。

省份 | 城市
 --- | -| 
| 北京 | 朝阳

 左对齐 | 右对齐 | 居中对齐 |
 :--- | -: | :--:|
:- 设置内容和标题栏居左对齐 |  -: 设置内容和标题栏居右对齐。| :-: 设置内容和标题栏居中对齐。 |
| 1 | 2|3|

# 分隔线  
- 可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。
- 也可以在星号或是减号中间插入空格。

***

* * *

---

- - - 

___

_ _ _

# 删除线

~~删除的文字，文字和符号间不能有空格~~

# 下划线
<u>可以通过HTML的u标签来实现</u>


不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。

目前支持的 HTML 元素有：<kbd> <b> <i> <em> <sup> <sub> <br>等。
