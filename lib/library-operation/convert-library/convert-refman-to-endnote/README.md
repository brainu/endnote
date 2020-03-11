---
description: Reference Manager 数据库转换为 EndNote 数据库
---

# Reference Manager

EndNote 可以轻松的把 Reference Manager 数据库转换为 EndNote 数据库。在转换过程中，还能保证 Reference Manager 数据库信息完整性

**注：**本功能只适用于Reference Manager 11 和 Reference Manager 12 版本

虽然 Reference Manager 文献类型和 EndNote 的文献类型已尽力匹配，Reference Manager 的字段也是与 EndNote 的字段尽力匹配，但是在转换时还是可能需要做一些调整。在转换前需要在 Reference Manager 数据库中把文献类型作一些修改。

## 转换方法：

1. 在 EndNote 菜单中选择 File &gt;&gt; Open &gt;&gt; Open Library，打开新的对话框
2. 对话框底部选择 Reference Manager Databases \(\*.RMD\) 文件类型
3. 找到 Reference Manager 的数据库保存位置，选中 Reference Manager 数据库，然后选择打开，此时会出现「Convert Reference Manager Database」对话框。
4. 此时可以

* 选择 Convert 进行转换。此选项允许 EndNote 自动转换 Reference Manager 文献类型和字段为 EndNote 的文献类型和字段。同时还可以转换 Reference Manager 的所有附件，保存位置为 Reference Manager 数据库原来的保存位置
* 选择 Customize 可以进行自定义转换，自定义 Reference Manager 的每个文件类型为 EndNote 的文献类型。该选项对于曾在 Reference Manager 自定义过文献类型时很有用。对话框上部显示 Reference Manager 文献类型匹配 EndNote 文献类型情况。详细可参阅[Reference Manager 文献类型和字段与 EndNote 的匹配关系](Convert_RefMan_RefTypes.htm)。
* 选择 Reset to Default Map 按钮可以不保存改变，恢复默认匹配设置
* 确定保存改变

5. 如果不再进行修改选择 Convert 按钮

6. 此时出现 Save Converted Library as 对话框，保存为 EndNote 数据库文件。默认是文件名与原 Reference Manager 文件名一样

转换完成后，EndNote会提示「Convert Reference Manager Database」，选择 Yes 会把附件转换为相对链接，选择 No 会把附件转换为绝对链接。

**注：**EndNote 数据库都包含一个 .ENL 文件和相应的 .DATA 文件夹。转换完成后每个数据库都可以单独移动，拷贝，重命名或者删除，进行这些操作时要对 .ENL 文件和相应的 .DATA 文件夹同时操作。

**注：** Cancel 按钮可以放弃转换，Reference Manager 数据库也就不能转换为 EndNote 数据库。

## 附件转换

转换数据库时，EndNote 会查找每个文献的附件的绝对路径，如果 EndNote 找到了文件的绝对路径，附件就会成功添加到 EndNote 文献中。如果 EndNote 没有找到文献的绝对路径，可以浏览附件进行添加。

1. 在「Attachment Not Found」对话框中选择 File 按钮
2. 找到文献附件的保存位置
3. 选择 OK 继续转换，如果没有选择文件 OK 按钮灰色不可用。

转换完成后，EndNote 显示「Convert Reference Manager Database」对话框，如果想转换附件为相对链接选择 Yes，转换为绝对路径选择 No

**注：** 在「Attachment Not Found dialog」对话框时，不能编辑文件路径

**警告：** 如果找不到附件，选择 Skip 或 Skip All 按钮。这将关闭「Attachment Not Found dialog」对话框，此时即使附件不在路径中，EndNote 也会在附件中添加 Reference Manager 数据库所提供的附件路径链接。

### 路径转换

转换完成后，EndNote 会打开转换完的数据库。文献的所有附件会在 EndNote 的附件中。移动鼠标到文件可以显示文件的绝对路径

EndNote 可以轻松为每个文献的附件改变绝对链接为相对链接

1. 选中包含附件的文献，可以通过附件排序快速查看包含附件的所有文献。
2. 依次选择菜单 References &gt;&gt; File Attachments &gt;&gt; Convert to Relative Links
3. 确定即可

附件路径就会转换为相对链接。参阅[附件绝对路径和相对路径的选择](../05EditRef/SelctngRltvPthAbsPthforFileAtt.htm)了解更多有关附件路径知识。

