---
description: 创建 EndNote 可导入制表符格式
---

# 制表符格式

Tab-delimited 导入选项可以导入每个文献间用段落符号 \(¶\) 分隔，文献内不同部分使用制表符分隔的文本文件

### 导出数据前准备

**作者姓名**

从数据库导出文献前，推荐作者之间使用分号\(;\)或者两个斜杠\(//\)进行分隔，例如：

HowSci, P.//Harrison, G.//Lennon, J.

如果做不到，可以导出或者导入后手动修改

**文献类型**

如果可能，应该保证每个文献都有一个部分是表明文献类型的，推荐使用 EndNote 的文献类型，这样 EndNote 才能辨识。如果仅有一种文献类型，此项到是不重要，导入设置可以指明所有文献默认导入为期刊类文献

### 导入前数据准备

打开文件，增加两行内容，告诉 EndNote 该文件的默认文献类型和如何解析数据

**第一行：默认文献类型**

第一行必须定义整个文件的文献类型，格式是一个星号后紧跟一个 EndNote 的文献类型，之后是一个段落符号 \(¶\)，例如：

\*Journal Article &lt;¶&gt;

整个文件应该如下样式

| \*Journal Article | &lt;¶ &gt; |  |  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Author | &lt;tab&gt; | Year | &lt;tab&gt; | Title | &lt;tab&gt; | Journal | &lt;tab&gt; | Volume | &lt;¶&gt; |
| Jones, J//Sho, S | &lt;tab&gt; | 1994 | &lt;tab&gt; | Easy Food | &lt;tab&gt; | J. of Eating | &lt;tab&gt; | 1 | &lt;¶&gt; |
| Woo, W //Lee, L | &lt;tab&gt; | 1995 | &lt;tab&gt; | Rain Hats | &lt;tab&gt; | J. of Clothing | &lt;tab&gt; | 2 | &lt;¶&gt; |
| Carlos, C\\Luis, L | &lt;tab&gt; | 1991 | &lt;tab&gt; | Cell Phone | &lt;tab&gt; | J. of Phones | &lt;tab&gt; | 3 | &lt;¶&gt; |

**第一行：自定义文献类型**

如果是自定义文献类型，需要检查 EndNote 的文献类型设置，依次打开菜单 Edit &gt;&gt; Preferences &gt;&gt; Reference Types &gt;&gt; Modify Reference Types

使用自定义文献类型的数据文件应该如下样式：

| \*My Reference Type | &lt;¶&gt; |  |  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Author | &lt;tab&gt; | Year | &lt;tab&gt; | Title | &lt;tab&gt; | Journal | &lt;tab&gt; | Volume | &lt;¶&gt; |
| Jones, J//Shoe, S | &lt;tab&gt; | 1994 | &lt;tab&gt; | Easy Food | &lt;tab&gt; | J. of Eating | &lt;tab&gt; | 1 | &lt;¶&gt; |
| Woo, W //Lee, L | &lt;tab&gt; | 1995 | &lt;tab&gt; | Rain Hats | &lt;tab&gt; | J. of Clothing | &lt;tab&gt; | 2 | &lt;¶&gt; |
| Carlos, C\\Luis, L | &lt;tab&gt; | 1991 | &lt;tab&gt; | Cell Phone | &lt;tab&gt; | J. of Phones | &lt;tab&gt; | 3 | &lt;¶&gt; |

**第一行：多种文献类型**

如果导出时不能根据文献类型导出多个文献，可在文件中指定每个文献类型。此时首先要在第一行列举出[通用](../Appendices/RefTypes_A_An.htm) 文献类型的字段，以「Reference Type」字段开始，来定义文献的类型，例如：

| Reference Type | &lt;tab&gt; | Author | &lt;tab&gt; | Year | &lt;tab&gt; | Title | &lt;tab&gt; | Secondary Title | &lt;tab&gt; | Volume | &lt;¶&gt; |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Journal Article | &lt;tab&gt; | Jones, J//Shoe, S | &lt;tab&gt; | 1994 | &lt;tab&gt; | Easy Food | &lt;tab&gt; | J. of Eating | &lt;tab&gt; | 1 | &lt;¶&gt; |
| Book Section | &lt;tab&gt; | Woo, W //Lee, L | &lt;tab&gt; | 1995 | &lt;tab&gt; | Rain Hats | &lt;tab&gt; | J. of Clothing | &lt;tab&gt; | 2 | &lt;¶&gt; |
| Report | &lt;tab&gt; | Carlos, C\\Luis, L | &lt;tab&gt; | 1991 | &lt;tab&gt; | Cell Phone | &lt;tab&gt; | J. of Phones | &lt;tab&gt; | 3 | &lt;¶&gt; |

**第二行：EndNote 的字段名称**

第二行必须精确匹配 EndNote 的字段，例如：

| \*Journal Article | &lt;¶&gt; |  |  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Author | &lt;tab&gt; | Year | &lt; tab&gt; | Title | &lt;tab&gt; | Journal | &lt;tab&gt; | Volume | &lt;¶&gt; |
| Jones, J//Shoe, S | &lt;tab&gt; | 1994 | &lt;tab&gt; | Easy Food | &lt;tab&gt; | J. of Eating | &lt;tab&gt; | 1 | &lt;¶&gt; |
| Woo, W //Lee, L | &lt;tab&gt; | 1995 | &lt;tab&gt; | Rain Hats | &lt;tab&gt; | J. of Clothing | &lt;tab&gt; | 2 | &lt;¶&gt; |
| Carlos, C\\Luis, L | &lt;tab&gt; | 1991 | &lt;tab&gt; | Cell Phone | &lt;tab&gt; | J. of Phones | &lt;tab&gt; | 3 | &lt;¶&gt; |

**注：**不同字段间使用制表符进行分隔，最后一个字段后要跟一个段落符号

**还需要考虑的问题**

* 可以导入 ANSI，ASCII，UTF-8 编码的文件，这意味着导入中数据文件是纯文本文件
* 所有字段和文献类型名称必须与 EndNote 中相同，参阅[文献类型列表](../reference-types/list-of-reference-types/)了解文献类型和字段
* 多个作者间要用\(;\)或双斜杠\(//\)进行分隔
* 域内不能包含制表符或者段落符号
* 导入过程中会删除前后空格
* 导入时不能大小写转换
* 保留字段「Unused」可用于不想导入的数据

#### 导入时出现错误

以上工作完成后，就可以导入了，依次打开菜单 File &gt;&gt; Import &gt;&gt; File \(见[导入文献一般过程](general-importing-instructions.md)\)，注意导入选项选择「Tab-Delimited」

如果 EndNote 不能导入数据或者数据内的某个部分，会提示错误，以下是常见3个错误

* **Bad Default Reference Type：** 第一行没有指定对文献类型
* **Bad Field Name：** 第二行的字段不是EndNote的有效字段
* **Missing Reference Type Information：**没有指定默认文献类型和字段

如果出现上述错误，打开数据文件作出相应的修改，然后再次导入。可能这个过程要反复多次

