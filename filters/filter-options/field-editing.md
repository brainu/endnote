---
description: EndNote 滤件选项的栏目编辑，该文同样适用于滤件和连接文件 (Import Filters and Connection Files)
---

# 栏目编辑

依次打开菜单 Edit &gt;&gt; Import Filters 或 Connection Files &gt;&gt; Open Filter Manager 或 Open Connection Manager，选择一个然后编辑

### Change UPPERCASE text to

数据文件中如果是全部大写字母，EndNote 可以转换为句首大写 \(Sentence\)，单词首字母大写 \(Headline\)，小写 \(Lowercase\)或者不转换 \(Do NOT Lowercase\)

如为了使题目小写，在该项上面的「Field Editing for」中选择「Title」，然后在此处选择小写「Lowercase」。「Field Editing for」中的字段是通用栏目名

**注：**文献类型和它们相应的通用名称，可参阅[通用文献类型](../14RefTypes/The_Generic_Type.htm)

例如，数据文件中的题目这全部大写：「COMPOST AS A HUMAN NUTRIENT AND HORMONE CARRIER」，在导入进想变成首字母大写

 Compost as a Human Nutrient and Hormone Carrier

或者是句首字母大写

 Compost as a human nutrient and hormone carrier

上述两个转换可在「Field Editing for」中选择「Title」，然后在「Change UPPERCASE text to」中分别选择「Headline」或「Sentence」。如果不想转换大小写，就要选择不转换「Do NOT Lowercase」

可以在任何字段中使用应用转换小写，只要在这个栏目中所有文字是大写。如果该栏目中的文本是混合情况，有大写也有小写，EndNoe 导入时是混合状态

Author, Editor, Translator 等栏目的处理方法不同于其他字段。导入作者时，这些栏目自动转换为首字母大写。由于这三个栏目的特殊性，因此上述三个栏目在「Field Editing for」没有这三个栏目选项

### Enter text to be omitted

有些数据行有多余的字符，如星号\(\*\)或破折号\(-\)，导入时候我又不想要这些符号。例如下面的数据行期刊名称中含有破折号，每个关键词前还有星号：

 SO-   American-journal-of-preventive-medicine; 12\(9\)

 DE-   \*COMPUTER SYSTEMS DESIGN; \*DISPLAY DEVICES; \*INTERFACES

为了防止这些多余的符号也导入到 EndNote 数据库中，可以在「Enter text to be omitted」输入需要忽略的字符，然后回车。可以输入多个，但是一次只能输入一个

* 从「Field Editing for」列表中选择相应的栏目名称，该处的栏目名称是通用名称，可以参阅[文献类型列表](../Appendices/List_of_Reference_Types.htm)查阅文献类型栏目的通用字段名称。比如上例中的期刊名称中有破折号，通过[查询](../Appendices/RefTypes_J-L.htm)发现期刊 Journal 对应的通用名称是 Secondary Title，因此在「Field Editing for」选择「Secondary Title」
* 然后在「Enter text to be omitted」中输入破折号\(-\)，回车即可。相应的第二行数据关键词也是如此操作

因为「Enter text to be omitted」列表中采用的是通用名称，因此在通用字段中选择忽略的字符，会影响多种文献类型。比如通用文献类型的 Secondary Title 对于的期刊是 Journal ，同进对于书籍又是 Series Title。因此如果此处选择忽略破折号，虽然本意只是针对期刊，但是如果书籍 Series Title 如果有破折号同样也会忽略

每个需要忽略的字符要一行一个，也就是一次输入一次回车然后再输入一个。例如假设想忽略下划线\(\_\)和斜杠\(/\)，第一次输入"\_"\(不包括引号，下同\)，然后回车，然后再输入"/"，然后回车。不能同时输入"\_/"，因为这样EndNote就会忽略"\_/"，而不是分开的形式了。最多每个字段可以忽略254个字符

从忽略列表中移除某个字符，选中字体然后选择上方的「Remove」即可。一次移除多个字符可以配合使用Shift或Ctrl键

**注：**添加的忽略字符越多，EndNote 导入数据花费的时间越长。这也好理解，你让 EndNote 招人的时候，还要区分三六九等，又要脱裤子检查又要清除不良分子的，这事肯定费时间。因为为了避免导入的时候时间太长，可能需要在导入的时候不忽略某些字符，先导进来再说。导进来之后再用[查找替换](../05EditRef/Change_Text.htm)命令替换掉不需要的字符也不失一种方法

