---
description: EndNote 连接文件（Connection Files）的搜索属性（Search Attributes ）
---

# 搜索属性

Search Attributes 部分是连接文件的数据库搜索选项

* **Search Field Name：**该列是搜索名称，也就是在搜索面板中中最左侧 field 显示的名称  EndNote 使用通用名称作为搜索的名称，这样做是为了搜索不同在线资源和本地数据库时相对简单些  EndNote 预先设置的连接文件常使用在搜索 field 名后插入文本的方式描述搜索，这个插入文本不是搜索不同搜索 field 名的一部分。
* **Attributes：**该列是控制搜索属性的，用于搜索的索引，以及如何解析搜索词

### 什么是「attribute」

Z39.50 **search attribute**是用来定义一个搜索词的特征值。例如如果搜索「ebola virus」，会发送不同的属性到服务器，告诉在是查找「ebola virus」，并且匹配相应的文献

**搜索属性由Z39.50标准定义**

1. **Use：**搜索的索引\(如关键词\)
2. **Relation：**搜索词与索引的关系\(如等于，大于或者小于\)
3. **Position：**: 搜索词在 MARC record field中的位置 \(第一，最后，任何位置等等\)
4. **Structure：**搜索词的结构\(如单词或者短语\)
5. **Truncation：**搜索词截断选项\(如右截断，通配符或没有截断等等\)
6. **Completeness：**指明搜索词是否应该在MARC record对应field 搜索

其中**「Use」**属性是最重要的，指明搜索索引来查找搜索词。其他属性每个在线数据库不一样。这些选项常留空为服务器默认设置，但是如果输入相应的值会覆盖默认属性值

每个数据加都有自己的**「Use」**属性，可以咨询在线数据库配置信息决定该填何种值。EndNote 不会提供这些值，需要通过数据库服务器获得

### 编辑 Search Attributes 注意事项

当修改搜索属性时，在真正改变相应的值前首先要进行检测。可以通过[命令行语法搜索方法](Using_Z3950CmndLineSyntx.htm)输入新的属性值进行检测。这样可以在保存改变前检测新的属性值

