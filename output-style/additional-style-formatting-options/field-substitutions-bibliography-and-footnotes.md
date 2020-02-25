---
description: EndNote 输出格式编辑之内容参考文献（Bibliography ）和脚注（Footnotes ）的内容替换
---

# 参考文献和脚注的内容替换

参考文献（Bibliography ）和脚注（Footnotes ） 下的 Field Substitutions 面板可以替换文献的部分栏目内容为空时替换为相应的内容

* DOI
* PMCID
* Volume and Pages

最下方还有 If tge editor and translator are the same individual,use: 选项，该选项应用于编者和译者相同时的书籍。

这些选项的值是默认的，选中前面的选项，就会出现 EndNote 设置的默认值。例如选择 If the DOI field is empty,use 选项，如果文献有DOI信息就显示DOI信息，如果没有就显示链接。但是也可以通过 Insert Field 列表插入想替换的内容

替换方法

1. 依次打开菜单 Edit &gt;&gt; Output Styles &gt;&gt; Open the Style Manager
2. 选择输出格式并编辑
3. 打开格式编辑窗口，选择 Bibliography 或 Footnotes 下的 Field Substitutions
4. 选择相应的选项，可以通过 Insert Field 插入需要的内容
5. 保存输出格式或者另存为新输出格式

**例子**

* 假设引用的文献有DOI信息，但是没有卷和页码信息。期刊的要求参考文献必须有DOI信息。输出格式告诉EndNote如果卷和页码栏目为空，就使用DOI信息，否则显示卷和页码信息
* 现在引用篇 PubMed 的文章，但是却没有 PMCID 号，只有 NIHMSID。一在期刊的参考文献要求 NIHMSID 应当替换。输出格式就告诉 EndNote 如果 PMCID 为空时，就使用 NIHMSID，否则显示 PMCID 信息。

