---
description: EndNote 滤件选项的文献类型，该文同样适用于滤件和连接文件 (Import Filters and Connection Files)
---

# 文献类型

### Default Reference Type

如果 EndNote 不能确认某个记录的文献类型，此处的文献类型默认设置就是告诉 EndNote 该使用哪个文献类型。例如假设有一个滤件，把 Journal Article 设为了默认文献类型，并且建立了一个模板。如果导入的数据文件中包含会议文献，但是又在导入滤件模板中没有定义会议文献，所以 EndNote 根据文献类型默认设置，也会把会议文献认为中 Journal Articles。同样，如果一个数据没有使用 Reference Type 标签，数据中的所有文献导入时根据此项设置都作为 Journal Article 处理。\(见 [文献类型标签](The_Reference_Type_Tag.htm)了解在模板中如何定义文献类型标签的更多信息\)。

**注：** 文献类型默认常在模板设置中文献列表中的黑体显示

### Identifiers

有些数据库公司，如 Ovid \(我晕，这里就没下文了，不怪我，只怪英文帮助到这就没了，那我只能根据理解来了\)，可能提供的数据库不止一个，因此下载的数据文件中每个数据库的格式可能又不一样\(真蛋疼\)，如果利用一个滤件模板导入的话，有的数据可能正确导入，有的文献却不能导入，此时就需要「Identifiers」设置了

虽然 EndNote 在导入此类数据时，有「Multi-Filter」选项，但是有时候还是需要自己设置一个滤件的

多个滤件，标签处设置一个数据库的标识。然后在此处「Identifiers」中输入每个数据库相应的标识

这样，根据「Identifiers」的设置，EndNote 知道遇到标签就该使用哪个滤件模板了

此处的「Identifiers」两个都要填写，第一个是数据公司，第二个是数据库名

例如EndNote读取下面这些数据：

> &lt;1&gt;
>
> VN     Ovid Technologies, Inc.
>
> DB     Ovid MEDLINE
>
> AU     Jacobson, R; Campbell, S
>
> PY     1999 etc.

Vendor Identification，输入标签「VN」和「Ovid Technologies」

Database Identification，输入标签「 DB」和「Ovid MEDLINE」"

