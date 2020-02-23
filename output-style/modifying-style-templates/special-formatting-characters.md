---
description: EndNote 输出格式的特殊格式化符号
---

# 特殊格式化符号

[EndNote](http://www.howsci.com/tag/endnote/)有一些特殊格式化符号可以在[输出格式](http://www.howsci.com/tag/output-styles/)中更加灵活和精确的处理标点符号和内容。

### 连接相邻文本\(使用非中断空格\)

如果在[格式](http://www.howsci.com/tag/output-styles/)模板中输入Edition ed.并使用一个空格来分隔指标Edition和ed.的话，ed.根据规则4不管Edition有无内容都会出现在参考文献中。

为了避免这种情况，使ed.基于Edition内容而决定是否出现，这就需要非中断空格。可以把非中断空格想像为参考文献格式化的胶水。它连接两个或者多个指标在一起，从而让他们作为一个整个。因此任何文本或者标点符号都可以粘在一个指标上，其出现与否决定于粘贴的指标，如果这个指标是空的话，那么文本就不出现。

可以从Insert Field选择Link Adjacent Text插入作为非中断空格，还可以通过Ctrl+Alt+Space输入一个非中断空格。这个非中断空格在屏幕上像一个小钻石。 set限制解除 

非中断空格在参考文献中会转换成一个普通的空格。非中断空格一般用途包括\(下面的◊就表示一个非中断空格\)：

  `p^pp◊Pages`

  `Edition◊ed.`

  `vol◊Volume`

  `Editor◊Ed.^`

非中断空格还用于和竖线\(见下面\)一起使用来改变标点符号的依赖关系

`Volume|: ◊Issue|.`

上面的例子中的冒号用非中断空格连接于Issue，因此如果Issue没有内容的话冒号在参考文献中就不会出现

### 强制分隔-使用竖线

如果不想要文字或者标点符号依赖于之前或者之前的指标，可以使用竖线\(\|\)强制分隔文本的依赖关系。反斜线\(\\)也有竖线相同的作用，可以Insert Field列表中插入Forced Separation实现。

可以把竖线想像成**阻断**依赖关系，或者强制分隔两个独立指标\(竖线与非中断空格的作用正好相反\)。

例如[期刊](http://www.howsci.com/tag/journaltag/)的有些格式需要在volume和issue之间有两个句号，这样的格式可能如下 \(· 表示一个空格\):

**`Journal Article`**  
``

`Author.·"Title."·Journal·Volume.Issue·(Year):·Pages.`

但是当Issue没有内容时，参考文献的格式就会不正确了，如下所述：

Clark, H. and Carlson, T. "Hearers and Speech Acts." Language 58.\(1982\): 332-373.

注意分隔volume和issue的句号却出现在了年代前，这是因为根据规则\#2，句号依赖于前面的volume，虽然Issue没有内容但是句号也出现了。而分隔volume和年代之间的空格却没有了，因为根据规则\#3，空格依赖于前面的内容，而Issue没有出现，因此空格也就消失了。

[EndNote](http://www.howsci.com/tag/endnote/)有方法避免这个问题，竖线\(\|\)可用来阻断空格和标点符号的依赖关系。

如果在指标前插入竖线，空格的依赖关系就从 Volume转换成了Issue。在Issue前的空格前添加另一个竖线就会使空格不再依赖于Issue。使用竖线连接非中断空格，这些改变如下所述：

**Journal Article**  
Author.·"Title."·Journal Volume\|.Issue\|·\(Year\)\|:·Pages\|.

最后的格式化参考文献格式就是正确了，此时issue没有内容年代之前的空格也不会消失

Clark, H. and Carlson, T. "Hearers and Speech Acts." Language 58 \(1982\): 332-373.

另一个竖线的常见例子如下：

Publisher\|: ◊City

Pages\|. \(让最后一个空格变成独立的\)

### 参考文献中的指标名称

有时可能需要显示所输入的文本，例如可能想在编辑姓名后使用单词Editor

Jones, V.R., B.K. Marion, and R.L. Zeiss, The Theory of Foraging, in A History of Foraging Behavior, B.J. Bloggs, Editor. 1976, Smith and Barnes: New York.

正常情况下在编辑格式时输入的Editor用来解释书籍的栏目名，这甚至是栏目的名称是一个单词的一部分，如Editors或Issued。

为了强制EndNote把一个词认为是一个文本而不是模板下的栏目名，需要在Editor前后加上一个重音符\(\`Editor\`\)。重音符可以通过键盘左上角的\(~\)键输入。记得要用非中断空格连接文本\`Editor\`和Editor

**Book Section**  
Author,·Title\|.◊in◊Book·Title\|,◊Editor,◊\`Editor\`\|.·Year,·Publisher\|:◊City\|,·p.◊Pages.

### 单数/复数-分隔符\(脱字符 ^\)

可能需要使用脱字符\(^\) 来分隔单数和复数的编辑或者页码，例如有的格式把一个编辑后是Ed.而多个编辑后面是Eds.。同样如果文献是一面页码后面是p.，而多个页码后面要跟pp. \(真TMD的蛋疼啊！哪个杂志要是搞这样的参考文献格式，我只能说这个杂志的主编太心理阴暗了！\)。这个可以应用于通用栏目中相应的Author, Secondary Author, Tertiary Author, Subsidiary Author, Pages, 和 Cited Pages。

在[格式](http://www.howsci.com/tag/output-styles/)模板中，输入单个和多个标签可用脱字符\(从Insert Field列表中插入或者直接输入Shift+6\)。单数时采用脱字符前面的任何文本，但是不包括空格；复数时采用脱字符后面的文本。输入的文本如果有空格间隔，必须使用非中断空格，例如下在的例子

**Edited Book**  
Editor, ◊ed.^eds.·Title.·Number·of·Volumes◊vols\|.◊Vol.·Volume\|,Series Title\|.·City\|:◊Publisher\|, ◊Year\|.

或者像这样

**Journal Article**  
Author.·"Title,"·Journal Volume\|.·Issue\|\(Year\)\|:p.^pp.·Pages\|.

