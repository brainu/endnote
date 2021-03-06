---
description: EndNote 附件的相对路径和绝对路径，即附件是存储于数据库文件夹内还是只是存储一个文件链接
---

# 附件的相对路径和绝对路径

当为文献插入附件时，可以选择是保存为相对路径还是绝对路径

### 路径选择方法

当插入附件时，在插入的对话框中会有如下选项「Copy this file to the default file attachments folder and create a relative link」，此时可以选择相对路径

**相对路径**

当上述对话框选中时，附件就保存为相对路径。此时 EndNote 把附件复制到数据库的 DATA 文件夹中。选择相对路径的好处在于易于管理和分享，[科研动力](http://www.howsci.com)强烈建议使用这种方法保存附件。即使在附件原来的位置进行删除或者编辑，也不会影响 EndNote 数据库的完整性。

**绝对路径**

如果在上述选项不选择，那附件就保存为相对链接，文件还是保存在原来的位置，不会复制到数据库中。如果在原来的位置删除附件，那么EndNote就不到附件了。而且如果是分享，还需要把附件一起拷贝，让同事在硬盘上建立相同的文件夹，把文件保存相同的位置才可以。真是蛋疼啊，因此[科研动力](http://www.howsci.com)强烈建议还是用相对路径保存附件最好。

### 如何了解附件保存的路径形式

我们打开一个文献，想了解附件保存的形式是相对路径还是绝对路径，可以在 File Attachments 区把鼠标放置在附件图标上

* 如果附件路径显示为完整的路径和文件名，那么就是绝对链接
* 如果仅显示文件名，那么就是相对链接，附件在 DATA 文件夹

还可以通过预览附件确定路径类型，使用一个可以显示附件的引文格式，如「Show All Fields」，在分页窗口中的预览「Preview」面板中查看，如果附件显示的是完整路径，如「C:\Documents and Settings\All Users\Documents\howsci.pdf」，那么就是绝对路径，如果仅显示文件名，如「internal-pdf://2841908372/howsci.pdf」，那么就是相对路径。

### 默认路径设置

既然希望把附件统一设置为某一路径，可以设置默认路径，这样每次遇到「Copy this file to the default file attachments folder and create a relative link」选项时就不用再次选择了。详见[URLs & Links 设置](../18Prefs/URLSandLinksPrefs.htm)

即使选择了默认路径，正如上述，在添加附件的时候还是可以自定义附件路径的

### 转换绝对路径为相对路径

如果是使用 EndNot e的早期版本，如 EndNote X 以前的版本，附件的路径都是保存为相对路径。此时可以转变相对路径为绝对路径。[科研动力](http://www.howsci.com)强烈建议转换。这样好处太多了

**转变方法如下**

1. 开始前最好备份数据库，因为此项操作不可逆
2. 选中需要转换的文献
3. 依次打开菜单 References &gt;&gt; File Attachments &gt;&gt; Convert to Relative Links

选中的文献附件路径就会自动改变，附件也会复制到 DATA 文件夹内

### 再次插入相同的附件

如果在文献中插入相同的附件，再次添加附件的路径决定于此次插入时的路径选项

**相对路径：**相对路径会替换以前的链接，并重新生成相对路径和重命名附件

**绝对路径：**因为插入的绝对路径可能不一样，因为可能每次查看附件路径的时候，附件的路径也会有多个

