---
description: EndNote 搜索的比较运算符
---

# 比较运算符

比较运算符 \( comparison operators \)用于搜索词与限定条件之间的关系，如一个搜索行一般是介个样子的：

| **Field** | **Comparison Operator** | **Search Term** |
| :--- | :--- | :--- |
| Title | Contains | Dinosaur |

上面的搜索式的意思是搜索题目\(限制域为题目 Title \)中含有\(比较运算符是含有 Contanis \) dinosaur \(搜索词\)的文献

比较运算符有以下几种：

* **Contains：**含有。所有文献中含有搜索词的文献。搜索词可以左右截断，如搜索 howsci，将会搜索 howsci, myhowsci, howsciweb 等词。如果想限制特定的词 howsci，需要在搜索对话框中选择上匹配词 \( Match Words \) 选项。

**注：**在线搜索数据库时只有「含有」比较符可用，下面的比较运算符只用于搜索 [EndNote](http://www.howsci.com/tag/endnote/) 本地数据库。有的比较运算符在有的域中不能同时使用

* **Is：**搜索准确匹配搜索词的文献

**注：**这个比较运算符在域限制条件为 Any Field + PDF with Notes 时无效

* **Is Less Than：**搜索词小于限制条件的文献
* **Is Less Than or Equal To：**检索词小于或者等于限制条件的文献
* **Is Greater Than：**搜索词大于限制条件的文献
* **Is Greater Than or Equal To：**搜索词大于或者等于限制条件的文献

**注：**所有「大于」和「小于」比较运算符是比较的数字或者字母排序。当域中同时有数字和字母时，默认是比较的数字。并且忽略搜索词的搜索式。

* **Field Begins With：**以搜索词开头的文献\(也称为右截断\)。搜索词可以是单词的一部分，完整单词或者几个单词。如果输入的是多个单词，记住空格和标点符号很重要，所以必须在搜索框中输入准确的搜索词。如果不想匹配单词的部分，选中匹配单词 \( Match Words \)选项。

**注：**该比较运算符在限制条件为 Any Field + PDF with Notes 时无效

* **Field Ends With：**以搜索词为结尾的文献\(也称为左截断\)。搜索词可以是单词的一部分，完整单词或者几个单词。如果输入的是多个单词，记住空格和标点符号很重要，所以必须在搜索框中输入准确的搜索词。如果不想匹配单词的部分，选中匹配单词 \( Match Words \)选项。

**注：**该比较运算符在限制条件为 Any Field + PDF with Notes 时无效

* **Word Begins With：**搜索域中所有单词以搜索词为开头的文献\(也称为右截断词\)。此时忽略空格和标点，这有助于查找以搜索词为词根的词，如查找 how，会同时查找 howsci, howsciweb, howsciwebsite等词，但不会查找 myhow 等词。

**注：**Field begins with, Field ends with, 和 Word begins with 这三个比较运算符把作者域的处理方法等同于其他域的处理方法，没有姓和名的之分，[EndNote](http://www.howsci.com/tag/endnote/) 只会在文本中查找满足条件的文献。**比较运算符使用实例**

| **Field** | Comparison Operator | Search Term | EndNote finds: |
| :--- | :--- | :--- | :--- |
| Year | Is greater than | 2000 | 2000年发表之后的文献 |
| Year | Is less than | 2000 | 2000年之前发表的文献 |
| Year | Is greater than or equal to | 1998 | 1998年及其之后发表的文献 |
| Title | Is less than | A | 标题中以数字开始的文献 |
| Author | Is less than or equal to | C | 所有作者姓以A，B或者数字开头的文献，诸如作者姓是 Carter的文献不在搜索结果内，因为 Ca 大于 C |
| Author | Is greater than or equal to | S | 作者姓以 S-Z 开头的文献 |
| Title | Contains | howsci | 题目中含有 howsci 的文献 |
| Title | Is | howsci | 题目中必须有 howsci 的文献 |
| Abstract | Is |  | 没有摘要的文献 |
| Title | Field begins with | howsci | 题目以 howsci 开头的文献，包括 howsciweb 和 howsciwebsite，但是不包括 myhowsci 的文献 |
| Abstract | Field ends with | howsci | 摘要中以 howsci 为结尾的所有文献，包括 endnote howsci，但是不包括 howsci web 或者 howsci website 的文献 |
| Any Field | Word begins with | howsci | 任何部分含有 howsci 或者以 howsci 开头的单词的所有文献，如 the best website of course on endnote is www dot howsci dot com 以及 howsci或 howsciwebsite 的文献，但是不包括 myhowsci 的文献 |

