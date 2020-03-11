---
description: EndNote 修复受损数据库方法
---

# 修复

有时 EndNote 数据库可能因为某种原因而损坏，常见原因分析可见科研动力的文章：[EndNote出现This library appears to be damaged怎么破](https://www.howsci.com/endnote-this-library-appears-to-be-damaged.html)

此时打开数据库或者插入文献等操作时会出现错误信息，其实预防这种情况最好的方法是事先备份，时刻记住备份数据库。参阅[备份 EndNote 文件](../Appendices/backing_up_your_EN_files.htm)。可惜有时候又没备份，EndNote数据库又出现了损坏，此时修复数据库了。

## 修复受损数据库方法

1. 关闭数据库
2. Tools &gt;&gt; Recover Library，此时会出现有关恢复数据库命令的介绍，选择确定。
3. 此时出现对话框，找到损坏数据库的保存位置，然后打开。
4. EndNote 会建立一个数据库备份，名字多是原有名字之后加上一个「-Saved」。例如我们修复名为「howsci」的一个数据库，经过修复后得到的数据库名称就为「howsci-Saved」，保存位置与受损数据库为同一位置。

修复完成后，可以打开这个新的数据库。

**注：** Recover Library 命令同样会建立一个新 DATA 文件夹，如果重命名，要记得同时命名 ENL 文件和 DATA 文件夹。

## 修复后数据库和原来数据库不同点

修复数据库的目的是恢复原来数据库可能多的文献，因此恢复的文献可能包含原来数据库已删除的了，但是还没有完全清空的文献。修复得到的数据库中文献比原来数据库可能要多，因此可能还需要手动删除一些文献。

EndNote 的修复功能不能恢复术语表，因此需要再次手动建立术语表

EndNote 也不能修复图表附件，但是可从原始 DATA 文件夹拷贝到新的 DATA 文件来

**推荐科研动力的文章**

* [EndNote正确恢复数据库方法](https://www.howsci.com/endnote-the-proper-process-for-recovering-library-files.html)
* [EndNote数据库高级恢复方法](https://www.howsci.com/endnote-the-proper-process-for-recovering-library-files.html)

