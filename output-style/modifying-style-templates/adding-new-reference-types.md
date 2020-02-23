---
description: EndNote 输出格式增加新文献类型
---

# 增加文献类型

虽然通用文献类型可以满足大部分需要，但是还是建议给文中出现的参考文献所有类型给定义了，这样格式化起来更准确一些，尤其是引用一些特殊类型的文献

比如当一个[输出格式](http://www.howsci.com/tag/output-styles/)没有包含特定的文献类型时，如 Report，[EndNote](http://www.howsci.com/tag/endnote/)会使用通用模板格式化这种文献类型。但是通用模板并不一定适用于全部文献类型，因此最好是增加一个文献类型的模板，这样可以更好的对参考文献格式化。

### 增加文献类型

1. 依次打开菜单Edit &gt;&gt; Output Styles &gt;&gt; Open Style Manager
2. 选择需要编辑的输出格式然后编辑
3. 在格式编辑窗口选择 Bibliography &gt;&gt; Templates
4. 在 Reference Types 选择需要添加的文献类型，如果是已选中的文献类型前面会有√号

这样新的文献类型就添加进来了，接下来的工作就是为这个文献类型添加模板格式

### 为新引用类型模板的格式增加内容

定义新引用类型模板的[格式](http://www.howsci.com/tag/output-styles/)的过程就是不断插入所需栏目和标点符号的过程，例如我们需要报告的这种文献类型的格式为：\(Author,Title,Report Number,Year,Institution,and City\)，最后在论文中报告的参考文献格式为

Brain,www dot howsci dot com,1.1,2015，Howsci:China

我们可以插入相应的栏目和输入标点符号，使用窗口上面的 Insert Field 逐步插入栏目名，插入栏目名后输入标点符号或者空格，然后重复上述步骤，直到最后完成。

最后的效果是介样的

**`Report`**

`Author,·Title,·Report·Number.·Year,·Institution:·City.`

