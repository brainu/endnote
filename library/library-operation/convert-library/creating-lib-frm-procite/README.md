---
description: EndNote 导入 ProCite 数据库方法
---

# ProCite

EndNote 可以轻松导入 ProCite 数据库。虽然已尽最大努力把 ProCite 文献类型和 EndNote 文献类型相匹配，但是仍需要适当调整。有些 ProCite 字段，如 Connective Phrase 和 Author Role，EndNote 没有相应的匹配字段，因此这些字段的内容将拷贝到 Notes

**注：**ProCite 自定义文献类型导入时，不能转换为 EndNote 相应的自定义文献类型，只能作为通用文献类型进行处理。可以在导出前在 ProCite 进行调整，或者在导入过程中进行自定义导入

## 方法一

1. 在 EndNote 菜单中依次选择 File &gt;&gt; Open &gt;&gt; Open Library，打开对话框
2. 在对话框底部选择文件类型为 ProCite database \(\*pdt\)
3. 选择 ProCite 数据库文件，此时会出现提示信息，将会转换数据库
4. 此时可以

* 选择 Convert 自动导入
* 选择 Customize 自定义导入，自定义文献映射关系，设置好映射关系后选择 OK 保存映射关系设置

   5. 在「Save Converted Library as」对话框中输入数据库新的名字和保存位置，默认与原 ProCite 名字一样，然后保存

EndNote 会转换数据库，当转换完成时，EndNote 会打开新的数据库

## 方法二

1. 导出 ProCite 数据库为文本文件
2. ProCite 打开希望导出的数据库文件
3. 在ProCite 依次选择 File &gt;&gt; Print Bibliography
4. 选择新式为「 RIS-EndNote.pos」 \(可在ProCite Web 网站 http:// www.procite.com 下载这种格式支持\)。
5. 在「Print Bibliography」窗口选择 Configure，找到 Fields 标签
6. 检查所有可选字段
7. 选择 OK，然后保存为文本文件
8. 打开 EndNote，打开一个数据库或者新建一个数据库
9. 依次打开菜单 File &gt;&gt; Import
10. 选择刚导出的文件
11. 导入选项选择 ProCite \(RIS\) 导入格式
12. 导入

