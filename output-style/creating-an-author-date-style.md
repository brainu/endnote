---
description: EndNote 创建新格式实例：建立作者日期型输出格式
---

# 创建作者日期型格式

一个新的格式仅需要含有 Citation 和 Bibliography 两个部分即可产生任何文章的引文和参考文献格式，Citation 主要是格式化论文中的引文的，而Bibliography主要是格式化文末的参考文献格式的。一般把 Generic 作为默认模板，用户要做的是在为所使用的标准文献类型增加额外的模板。如果为任何文献类型定定义了特定的模板，这些文献类型会根据自定义的模板而不是 Generic 格式。

### 建立格式方法

1. 依次打开菜单Edit &gt;&gt; Output Style &gt;&gt; New Style
2. 选择 Citations 下面 Templates 面板以格式化文中的输出格式。现在我们要制作的输出格式是作者年代格式，它们之间以逗号分隔，以括号括起来，如 \(howsci,2015\)
3. 把鼠标放置于 Citation 下的 Template，输入一个半括号，选择 Insert Field，选择插入 Author，然后输入逗号，然后再次在 Insert Field 选择 Year，再输入一个半括号，把作者和年代括起来，最后的格式 \(Author,Year\) 。下面要定义一个通用的格式作为引文类型没有默认模板时的格式。我们知道书籍的格式是这样的：Jones,VR,所有我们可建立一个通用的格式，以适应这种格式。
4. 选择 Bibliography 下的 Templates，然后在右侧选择 Generic 部分
5. 从 Insert Field 选择 Author \(虽然可以输入 Author，但是最好还是选择插入，因为这样做是安全保障不会出错\)，然后输入一个句号和一个空格，然后继续插入相应的区域和标点，直到与期刊要求一样的格式，最后样式如下\(下面的·代表实际输入的一个空格\)：

Author.·\(Year\).·Title.·Place·Published,·Publisher.

1. 如果题目必须斜体，选择 Title，然后依次打开 Edit &gt;&gt; Style &gt;&gt; Italic，也可以在上面的工具栏直接选择 I，也能把题目变成斜体
2. 保存格式为一个新的格式，保存时输入名称，如 howsci style

### 测试格式

打开数据库，在数据库下方选择预览文献 \(Preview\)，然后我们刚制作好的格式，就会看到[EndNote](http://www.howsci.com/tag/endnote/) 如何格式化文献的，这时候可能看到书籍的格式是挺好的，但是期刊的格式不能显示足够的信息。因此需要回到编辑格式窗口，为期刊添加一些格式。

### 期刊格式

打开 Bibliography 下的 Templates，在右侧面板中的 Reference Type列表中选择 Journal Article，这是为格式化期刊参考文献的模板，插入相应的区域，如下所述

Author·\(Year\)

保存文献格式，继续上一步的预览

### 完成格式制作

不断的测试杂志的参考文献要求，然后根据[编辑格式](Modifying_Style_Templates.htm)的方法不断的调整格式，直到符合杂志的要求。

仔细的检查每个部分要求，甚至是标点符号和空格等细致的要求，可以参阅[格式选项额外信息](Additional_StylFrmttngOpts.htm)。

**注：**[科研动力](http://www.howsci.com)认为最简单的方法是找一个相近的格式编辑一下即可，比这简单多了，详见[EndNote修改输出格式的方法](http://www.howsci.com/endnote-revise-the-output-style.html)

