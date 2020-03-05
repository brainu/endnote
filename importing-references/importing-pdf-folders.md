---
description: EndNote 导入 PDF 文件夹方法
---

# 导入 PDF 文件夹

**只能导入文件夹中的 PDF 文件**，其他文件不能使用这个方法导入。PDF 文件要有完整的 DOI 信息，这样 EndNote 才会根据 DOI 信息检索 http://www.crossref.org/，完善文献的相应数据。如果 PDF 没有 DOI 信息，导入的 PDF 创建的新文献数据不全

### 导入文件夹方法

1. 打开一个 EndNote 数据库
2. 依次打开菜单 File &gt;&gt; Import &gt;&gt;  Import Folder
3. 选择 Choose 按钮选择需要导入的文件夹
4. 选中文件夹后选择「确定」
5. 如果文件夹有子文件夹也需导入，选中「Include files in subfolders」，如果想把导入的文件夹中的文献新建一个群组，选中「Creat a Group Set for this import」
6. Import Option: PDF
7. Duplicates

   * **Import All：**导入所有PDF文件
   * **Discard Duplicates：**不导入重复文献
   * **Import into Duplicates Library：**重复文献导入到一个新的数据库，一般是与前数据名称后加区别符，如当前数据库是 Howsc.enl，重复文件就会导入到 Howsci-Dupl.enl 数据库中

   重复文件的判断方法可见[重复文献设置](../18Prefs/Duplicates.htm)，EndNote 默认是作者，发表年代，题目和文献类型一样即认为是重复文献

8. Text Translation：No Translation
9. Import

导入完成后，导入的文献归于 Imported References 组，如果导入的文献有出入，可以通过菜单 Tools &gt;&gt; [Change/Move/Copy Fields](../05EditRef/Change_Fields.htm)命令修改

