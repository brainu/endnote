---
description: 创建 EndNote 可导入的自定义标签格式
---

# 标签格式

如果需要导入大量的文献，可能要使用文字处理软件的查找和替换功能在数据的字段前插入分类标签，这样 EndNote 才能精确导入文献。为了添加标签，可能需要一个相应的滤件来解析标签\(建议使用[选择恰当的导入滤件](Choosing_th_CorrctImprtFltr.htm)的方法修改 EndNote 现有的导入滤件，而不是建立一个新的导入滤件\)

以下是转换数据文件为标签文件的基本步骤

**第一步：备份数据文件**

* 打开数据文件另存一个备份
* 删除除了文献数据之外的内容

**第二步：为栏目添加标签**

使用文字处理软件，如记事本打开数据文件，查找栏目之间的特殊字符，在每个栏目之前插入分类标签和段落符号。例如假设数据文件是如下样式：

\#S Jones, M.

\#S Billoski,

我们现在要把「\#S 」替换成标签，如下样式：

XX- Jones,

XX- Billoski,

保存文件为纯文本文件

**第三步：为非分隔符数据创建滤件**

打开 EndNote，[创建新滤件](../filters/edit-filters/creating-a-new-filter.md)\)，最终滤件样式如下

| Tag | Field |
| :--- | :--- |
| XX- | Author \(Year\) "Title" Journal. Vol. Volume no. Issue, |

每个字段名必须与文献中的一样，如果文献字段名没有，所有数据会在前面一个栏目中。例如上面的文献格式，Volume 栏目没有，滤件会把 Issue 数据放置在 Journal 栏目中

为了解决这种现象，文献每个循环都要按照一定的格式输入滤件中，开头经常是最长的一个

> XX- Author \(Year\) "Title" Journal. \|Vol. Volume\| no. Issue\|.
>
> XX- Author \(Year\) "Title" Journal. \|Vol. Volume\|.
>
> XX- Author \(Year\) "Title" Journal. \|\`DOI:\`DOI\|.

为了保证每行数据都能导入EndNote数据库中，可以在滤件打开「Source Parsing」选项下的「Import Source Into」选项，选择一个栏目名

**第四步：测试**

创建数据文件和导入滤件后，需要检测滤件是否设置正确。如果导入滤件能正确导入数据，可以使用这个滤件正式导入数据了。如果不能正确导入，需要编辑滤件进行修改再测试。修改时可能会用到[栏目编辑，移动复制栏目](../filters/filter-options/field-editing.md)和[查找和替换](../references/changing-text/find-and-replace.md)

