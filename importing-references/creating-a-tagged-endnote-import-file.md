---
description: 创建 EndNote 可导入的标签文件
---

# 可导入的标签文件

EndNote 导入标签格式的数据基于 Refer/BibIX 格式，该格式每个字段\(即 Journal，Volume 或 Title 等等\)前面都有一个特定的标签：百分号\(%\)紧跟一个字母，数字或者特殊字符，每个文献间以空白行进行分隔

`%0 Book`

`%A Geoffrey Chaucer`

`%D  1957`

`%T The Works of Geoffrey Chaucer`

`%E F.`

`%I Houghton`

`%C Boston`

`%N 2nd`

`%0 Journal Article`

`%A Herbert H. Clark`

`%D 1982`

`%T Hearers and Speech Acts`

`%B Language`

`%V 58`

`%P 332-373`

`%0 Thesis`

`%A Cantucci, Elena`

`%T Permian strata in South-East Asia`

`%D 1990`

`%I  University of California, Berkeley`

`%9 Dissertation`

### EndNote导入格式中的作者姓名

* 作者姓名使用「%A」标签，每个作者前都要有该标签，每个作者占一行

      `%A Jones, Mary  
      %A Simon, Jeff`

* 作者姓名也可以如下：

      `Geoffrey Chauceror`

* 姓名缩写或者全称都可以

### 定义文献类型

文献类型使用「%0」\(此处是数字0\)和文献类型名称

默认文献类型如下表所示，如果是自定义文件类型，数据文件也应当使用相应的新名称

| %0 Generic   | %0 Government Document |
| :--- | :--- |
| %0 Aggregated Database | %0  Grant |
| %0 Ancient Text | %0 Hearing |
| %0 Artwork | %0 Journal Article |
| %0 Audiovisual Material  | %0 Legal Rule or Regulation |
| %0 Bill | %0 Magazine Article |
| %0 Blog | %0 Manuscript |
| %0 Book | %0 Map |
| %0 Book Section | %0 Music |
| %0 Case | %0 Newspaper Article |
| %0 Catalog | %0 Online Database |
| %0 Chart or Table | %0 Online Multimedia |
| %0 Classical Work | %0  Pamphlet |
| %0 Computer Program  | %0 Patent |
| %0 Conference Paper | %0 Personal Communication |
| %0 Conference Proceedings | %0 Report |
| %0 Dictionary | %0 Serial Publication |
| %0 Edited Book | %0 Standard |
| %0 Electronic Article | %0  Statute |
| %0 Electronic Book | %0 Thesis |
| %0 Encyclopedia | %0 Unpublished Work |
| %0 Equation | %0 Web Page |
| %0 Figure | %0 Unused 1 |
| %0 Film or Broadcast | %0 Unused 2 |
|  | %0 Unused 3 |

### 标签和相应的字段

下表是标签和相应字段对照表，字段名是通用文献类的字段名，其他文献的字段名可能对应 Notes 字段

**注：**不能导入 Figure 字段 

| **Tag** | **EndNote Generic Field Name** |
| :--- | :--- |
| %A | Author |
| %B | Secondary Title \(of a Book or Conference Name\) |
| %C | Place Published |
| %D | Year |
| %E | Editor /Secondary Author |
| %F | Label |
| %G | Language |
| %H | Translated Author |
| %I | Publisher |
| %J | Journal Name |
| %K | Keywords |
| %L | Call Number |
| %M | Accession Number |
| %N | Number \(Issue\) |
| %O | Alternate Title |
| %P | Pages |
| %Q | Translated Title |
| %R | DOI |
| %S | Tertiary Title |
| %T | Title |
| %U | URL |
| %V | Volume |
| %W | Database Provider |
| %X | Abstract |
| %Y | Tertiary Author / Translator |
| %Z | Notes |
| %0 | Reference Type |
| %1 | Custom 1 |
| %2 | Custom 2 |
| %3 | Custom 3 |
| %4 | Custom 4 |
| %6 | Number of Volumes |
| %7 | Edition |
| %8 | Date |
| %9 | Type of Work |
| %? | Subsidiary Author |
| %@ | ISBN/ISSN |
| %! | Short Title |
| %\# | Custom 5 |
| %$ | Custom 6 |
| %\] | Custom 7 |
| %& | Section |
| %\( | Original Publication |
| %\) | Reprint Edition |
| %\* | Reviewed Item |
| %+ | Author Address |
| %^ | Caption |
| %&gt; | File Attachments |
| %&lt; | Research Notes |
| %\[ | Access Date |
| %= | Custom 8 |
| %~ | Name of Database |

