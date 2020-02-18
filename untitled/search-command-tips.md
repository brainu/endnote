---
description: EndNote 搜索注意事项
---

# 搜索注意事项

在 EndNote 进行搜索时，下面几点可能有用

**取消搜索**

搜索时按 Esc 可取消搜索

**匹配部分词**

如果没有选择匹配单词选项 \(Match Words\)，[EndNote](http://www.howsci.com/tag/endnote/) 搜索文本时会匹配部分单词\(左右截断\)，因此可以搜索词根并找到相关的术语。这是 EndNote 的一个很好的策略，选择适当的比较运算符，如「Field begins with 」或者「Word begins with」可以搜索以某些词开头的单词或者句子。

**变音符号**

搜索特殊的变音符号，选择匹配 \(Match Case\) 选项，可以准确的匹配诸如 é，ü，和 î 等这些变音符号。因此搜索「résumé」不会查找「resume」。如果想搜索所有字母的变化，不要选择匹配选项。详见[特殊符号的输入](../05EditRef/entering_SpecialChars.htm)了解有关变音符号更多信息。

**查找制表符和回车符**

使用「Option」选项可以在搜索式中插入「Tab」或「Carriage Return」

**搜索数字**

搜索数字时，[EndNote](http://www.howsci.com/tag/endnote/) 会把数字作为字符串查找，如在「Any Field」搜索包含「0025」的文本，EndNote 会匹配查找「00025」和「0025」，但是不会查找25。

但是上述原则不适用于文献编号\(Record Numbers\)，文献编号是 EndNote 分配的，开头不能包含0。当在所有字段中搜索数字时，EndNote 会所有文本中严格匹配数字，但是如果开头是0，在与编号比较前会把0去掉。只有准确的编号的记录返回。因此搜索「0025」会匹配编号「25」，不会匹配编号「250」。

**多个打开数据库搜索**

搜索命令只能一次搜索一个数据库，如果是多个数据库同时打开，需要把搜索的数据库调到前台再使用搜索面板。

**作者**

栏目列表的栏目名称是 [EndNote](http://www.howsci.com/tag/endnote/) 的「通用」栏目名称，这意味着不同文献类型的作者可能代表记者，编辑，艺术家或者其他作者。如果想搜索姓名缩写，要确保第一个和第二个缩写之间要有一个空格。如「Howsci, J P」，如果没有空格，[EndNote](http://www.howsci.com/tag/endnote/) 会认为JP是个名。

可以使用匹配单词选项来限制搜索，如搜索「Howsci, J P」，选中「Match Words」，会查找作者字段中含有「Howsci, J P」，如果没有选择匹配单词，会同时查找诸如「Howsci-Wilkins, Jeremiah」的作者。

**发表年代字段**

当搜索发表年代字段时，搜索 1994 只会查找 1994 年发表的文献，但是搜索 94 会查找 20 世纪 40 年代和 1994 的文献

**空字段的查找**

[EndNote](http://www.howsci.com/tag/endnote/) 可以搜索没有内容的字段，从字段列表中选择需要的字段名，选择比较运算符，并将搜索项留空，点击搜索，EndNote 会查找选择字段没有内容的文献。

**搜索附件**

可以通过附件的名字搜索附件，搜索 File Attachments Is \[文件名\]。搜索所有含有附件的文献，输入以下两行搜索式：

|  | Record Number | Is greater than or equal to | 1 |
| :--- | :--- | :--- | :--- |
| NOT | File Attachments | Is | \[blank\] |

上面的第一行是确保搜索所有文献，第二行是查找附件字段不为空的文献。

**注：**另外一个查看文献有无附件的简便方法是根据标题栏的附件进行排序，有附件的文献排在最前。

**清理搜索结果**

搜索完成后，可能会想从结果中排除一些文献。选择这些文献然后选择「Hide Selected References」隐藏文献，最后的的文献就是自己想要的结果。通过这比改进搜索式要容易的多。

**查看搜索结果相反的文献**

假设搜索 Brainu 或者 Howsci 为作者的所有文献，搜索后现在看到的都是这两位的文献。现在又想看看除了这两位作者以外的文献，此时可以不用再次搜索，只需要：

1. 选择文献列表
2. 依次打开菜单 Edit &gt;&gt; Select All \( Ctrl+A \) 选择 Howsci 和 Brainu 为作者的所有文献
3. 依次打开菜单 References &gt;&gt; Show All References \( Ctrl+Shift+M\)
4. 依次打开菜单 References &gt;&gt; Hide Selected References

现在剩下的文献就是作者不是 Brainu 和 Howsci 的文献

**搜索面板设置和恢复默认设置**

选择 Options 按钮，然后选择 Set Default 保存当前搜索条件为默认搜索条件，下次再搜索时搜索条件自动设置为这次的搜索条件，不用每次再输入搜索条件了，但是不保存搜索词。

单击 Options 按钮，选择 Restore Default 可以恢复默认设置。

