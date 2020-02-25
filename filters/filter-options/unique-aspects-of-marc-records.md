---
description: EndNote 滤件编辑之MARC 记录特点
---

# MARC 记录特点

MARC records 不同于其他目录记录的特性有两个重要方面：

### 数字标签

MARC records 不同于非 MARC 目录格式是 MARC 依赖数字标签。数字标签常包含3位数字，然后是两个空格和两个及其以上数字。例如：

`245 10   $a When you realize you have too many  
kids: $b a guide / $c Hugh B`

`245 14   $a The angel with a dirty mouth /$c NickSteel ; illustrated by Melissa`

### 子域

MARC 标签不同于其他书目标签在于 MARC 有子域

MARC 中的每个数字标签包含子域的任何数字，子域常包含两个连续的字符，第一个字符是子域的分隔符，说明又一个子域开始。「$a」和「$x.」就是子域的例子。子域不必是连续的，正如上面的例子。

如果从 MARC 数据库导入书目记录中建立一个常规的滤件，那么必须预料到很多可能标签和子域组合

因为很难预料 MARC records 中的每个标签和子域可能的组合，EndNote 提供了一个为 MARC records 建立滤件的简单方法，在 MARC Records 面板左侧的两个部分是如何建立滤件，以及当 EndNote 导入 MARC records 到 EndNote 数据库时如何转换不同的规则的。

