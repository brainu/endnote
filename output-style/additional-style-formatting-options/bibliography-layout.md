---
description: EndNote 输出格式编辑时参考文献的布局 (Bibliography Layout)
---

# 参考文献样式

Bibliography 下方的 Layout 选项提供了每个参考文献前后插入的内容和缩进

### 每个参考文献前增加内容

在 Start each reference with 部分可以输入内容，所输入的内容都会在每个参考文献前出现\(在引文前如何增加前缀可以参阅[临时引文](../18Prefs/Temporary_Citations.htm)\)。

最常用的前缀是参考文献的编号，常用于数字型输出格式

**每个参考文献前添加编号**

1. 依次打开 Edit &gt;&gt; [Output Styles](http://www.howsci.com/tag/output-styles/) &gt;&gt; Style Manager
2. 选择需要编辑的输出格式，然后选择编辑
3. 打开格式编辑窗口，选择 Bibliography &gt;&gt; Layout
4. 光标放置于Start each reference with下方的输入框中，然后选择 Insert Field 列表
5. 选择 bibliography number，可以在 bibliography number 之后输入必需的标点符号，如句号和空格，或者再次选择 Insert Field 插入 Tab 制表符

参考文献的格式如下所示：

`1.   Argus, M.V. New paleontological excavation techniquesNature19, 234-237 (1993).`

**注：** 创建悬挂式缩进时，参阅下方悬挂缩进

**其他前缀**

Insert Field 还有其他一些前缀

有些[输出格式](http://www.howsci.com/tag/output-styles/)使用要求在为引文和参考文献中使用标签指定每个助记符编码的入口，常常是作者姓名和年代的最后两位数。当在数据库中导入文献或者建立文献时，可以把助记符代码\( mnemonic code \)输入到标签\(Label\)栏目中。当[EndNote](http://www.howsci.com/tag/endnote/)格式化参考文献时，可以把这些编码放置于每个参考文献前。

**Citation：**作为参考文献的前缀可以用引文标记参考文献

**Reference Type：**将在每个参考文献前插入文献类型，如期刊或者书籍

**Record Number：**将在每个参考文献前插入EndNote数据库编号，这个编号是[EndNote](http://www.howsci.com/tag/endnote/)在数据库中标记文献的，这个也可以用于引文。增加编号作为参考文献的前缀可以显示该文献在数据库中的编号。

### 每个参考文献后添加内容

End each reference with部分是在参考文献后添加内容的，引文中添加后缀的方法参阅：[引文后缀](../10Word/Citation_Suffixes.htm)。

可以添加的后缀有Label, Keywords, Abstract, Notes field, 或数据库编号。但是除此之外也可以添加任何文本或者标点符号。常用的后缀是下面：

**例子：参考文献添加注释**

如果想把注释添加到参考文献中，可以如下步骤：

1. 依次打开 Edit &gt;&gt; Output Styles &gt;&gt; Style Manager
2. 选择需要编辑的输出格式，然后选择编辑
3. 打开格式编辑窗口，选择 Bibliography &gt;&gt; Layout
4. 光标放置于 End each reference with 下方的输入框中，然后选择 Insert Field 列表中的 Notes

如果想把注释另起一行，从 Insert Field 先插入段落符号 \( ¶\)，再插入 Notes。如果想把注释作为缩进，像新一段开始，先插入Tab再插入 Notes

**在参考文献中增加或者删除空行**

另外一个比较常用的是参考文献之间增加或者删除一个空行，就需要在 End each reference with 插入或者删除段落标记段落符号 \( ¶\) 。

**悬挂缩进**

很多数字型参考文献[格式](http://www.howsci.com/tag/output-styles/)要求一个悬挂缩进，如下例子

1. Postma,
2. Nyamweru,

[EndNote](http://www.howsci.com/tag/endnote/)有一些悬挂缩进选项，一般每个参考文献一行，因此这其中的有些选项并不可以用。但是如果一个参考文献包含多个行，EndNote提供一些哪行的参考文献可以使用悬挂缩进。多行参考文献的例子包括每个参考文献后有摘要，或者像一些人文期刊要求作者是单独的一行。

悬挂缩进包括：None, All Paragraphs, First Paragraph Only, Second Paragraph Only, 以及 All Paragraphs but the First。下面是仅第二行悬挂缩进的例子。一个输出格式要求作者在左边，然后是年代另起一行，并且缩进。这个格式就会把第二行作为悬挂缩进处理，在年代之前和之后插入一个Tab键。在处理文件时，悬挂缩进间距应与第二制表符的结尾对齐。

制表符和缩进的间距是由文字处理软件所决定

**注：**如果是数字型参考文献，参考文献序号后插入的制表符与参考文献排在一行

**制表符**

制表符可由 Insert Field 插入，插入一个制表符在参考文献中就表现一个制表符，在格式编辑中制表符表现为一个左箭头→，制表符的宽度由文字处理软件决定

制表符常在参考文献序号后插入，这可以有助于每个参考文献在序号后能对齐，这尤其在参考文件整体悬挂缩进时更为重要。

