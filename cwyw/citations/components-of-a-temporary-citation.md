---
description: EndNote 临时引文的组成部分
---

# 临时引文组成

临时引文\(未格式化的引文\)一般包含作者的姓，年代和文献在数据库的编号，这些信息以大括号进行括起来。但是临时引文还可以有其他很多种格式

临时引文必须以符号开始和结束，其他部分可以变化

可以输入这样的临时引文：

`{dinosaur extinction}`

或者也可以这样输入\(注意逗号的位置非常重要\)：

`{Prefix \Author, Year #Record Number Suffix}`

`{Prefix \Author, Year, Any Text, Suffix}`

下面的临时引文的每个组成部分的简要信息

**作者的姓：**任何一个作者的姓，并不一定非要是第一位作者。作者后要有一个逗号，这样限制 EndNote 查找作者字段内的信息

      `{Howsci, 2015}`

**发表年代：**发表年代要与文献内的信息精确一致，前面要有逗号。甚至可以省略作者的姓

      `{, 2001}`

**文献编号：**文献编号是其在 EndNote 数据库的编号，每个文献的编号是独一无二的，编号前须有一个井号

      `{Howsci, 2015 #84}`

**其他文本：**任何有助于识别文献的文本都可以出现在临时引文中，为了更好的识别文献，因此文本内容最好越独特越好。可在编号位置或者第二个逗号后输入的文本

`{greenhouse}`

`{Howsci, 2015,}`

`{Howsci, ,}`

上面第3个例子没有年代，因此必须在两个逗号间输入一个空格，否则 EndNote 匹配了不信息

**前缀：**可在格式化引文前添加前缀，前缀和文献间要有反斜杠分隔

`{see \Howsci, 2015 #84}`

**后缀：**后缀一般跟在编号后，或者前面要有第3个逗号

`{Smith, 1995 #98 p.293}`

`{Smith, 1995, dinosaur, p.293}`

**作者\(年代\)：** 格式化引文为 Author \(Year\) 格式，@作者-年代格式

`{Howsci, 2015 #95@@author-year} 或 {Howsci, 2015 #95@ p. 237@author-year}`

**不显示引文**引文在文中不显示，仅在文末参考文献中显示时，要输入@@hidden，第一个@是放置页码的位置，也就是编号后

`{Howsci, 2015 #98@@hidden}`

**注：**如果有的临时引文输入起来很麻烦，更简单的方法是格式化后[编辑引文](Editing_Citations.htm)

