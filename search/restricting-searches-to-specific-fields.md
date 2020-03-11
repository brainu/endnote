---
description: EndNote 特定栏目的搜索
---

# 栏目搜索

在搜索面板使用字段列表可以搜索指定的栏目，可以选择 Any Field 搜索文献的任何部分。如查找发表于2013年的文献，限制条件为年栏目 \( Year field \) ，这样就可以避免包括摘要，题目或者其他部分含有2013的文献

栏目列表中的栏目名是 EndNote 的[通用](../Appendices/RefTypes_A_An.htm)名称，如作者在不同有文献类型中可能代表记者，编辑，艺术家或者其他各种作者。

[EndNote](http://www.howsci.com/tag/endnote/) 可导入数百种来源的文献，每种来源使用它们各自的字段名称。一旦转换成EndNote的栏目后，搜索信息时使用 EndNote 的通用栏目名，而不是原来提供者的自定义字段名。例如从[ PubMed ](http://www.howsci.com/medline-embase-pubmed-pmc-ovid-difference-and-relation.html)得到的 PubMed 号一般转换成 EndNote 的 Accession Number，在 EndNote 中搜索[ PMID 号](http://www.howsci.com/pmid-pmcid.html)，要搜索 Accession Number 栏目。

### 搜索特定字段和 PDF 文件

可以在选中的文献中搜索的有的字段和 PDF 文件

1. 在字段列表中选择 Any Field + PDF with Notes
2. 选择一个比较列表
3. 输入搜索词，可以输入一个词或者多个词
4. 选择 Search 按键或者回车进行搜索

当选择 PDF 选项或者 Any Field+PDF 选项时，会应用下面的规则：

* [EndNote](http://www.howsci.com/tag/endnote/) 默认忽略大小写，如搜索 **howsci** ，EndNote 同样会搜索Howsci
* 如果输入的一个句子，EndNote 会在所有字段或者 PDF 文件一起查找所有单词。如搜索 **howsci website** ，EndNote 会在所有栏目或者 PDF 文件中查找包含 howsci websit 的文献。
* 当搜索特定字段，如 PDF 或者 Any Field + PDF with Notes，EndNote 把搜索引号\( " " \)作为字符。例如检索式 **"howsci website"**，EndNote 会在文献，PDF 文件或者笔记中查找找包含 "howsci website" 的文献。EndNote 会忽略 howsci website 的文献，因为它们不含有引号。

**注：**当使用这些选项时，匹配大小写 \( Match Case \) 和匹配单词 \( Match Word \) 会自动起作用，详见[搜索面板](../lib/the_search_pane.md)

### 一个单词搜索规则

当在任何字段中使用条件运算符 Contains 搜索一个单词时，EndNote 会自动左右截断单词，如搜索 howsci，EndNote 会匹配 Howsci, howsci, howsci website, how, sci, "howsci"等等。

