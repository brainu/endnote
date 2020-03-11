---
description: EndNote 打开 EndNote 早期版本数据库
---

# 打开早期版本数据库

EndNote X7 可以直接打开 EndNote 8 及其以下的数据库

因为 EndNote 包括增加功能，可能会遇到下列情况。当然可能还有其他情况

### 打开一个数据库时 EndNote 出现崩溃

当接收到一个 EndNote X7 数据库备份时，没有相应的.DATA 文件夹

因此如果是从他处得到的 EndNote 数据库，必须包含相应的.DATA 文件夹

### 打开一个数据库却是空白

当接收到一个 EndNote X7 数据库备份时，没有相应的.DATA 文件夹

如果没有修改空白数据加\(如增加新文献\)，可以复制原始的.DATA文件夹，再打开数据库。如果没有原始的.DATA文件，删除 EndNote 8 或者 9 创建的.DATA 可能能用 EndNote X7 打开数据库，此时会重建相应的.DATA文件夹

如果修改过空白数据库，所有以前的文献信息都会丢失。必须重新载入原始的数据库，包含相应的.DATA文件夹

### 韩国排序顺序丢失

EndNote X 及其以后版本包含韩国排序选项，EndNote 8 或者 9 忽略韩国排序选项，会默认排序列表中的第一项\(系统设置或者英语\)

### 使用新的文献类型时 EndNote 打不开

新的文献类型会阻止 EndNote X6 及其以前的版本打开 EndNote X7 的数据库

### 现有文件链接不正常

EndNote 8 和 9 不支持附件文件的相对路径。当使用 EndNote X7 以相对路径插入一个附件时，使用 EndNote 8 或者 9 就会看到文件的路径，而不是文件

**注：**不要修改这个无功能的相对链接，或者删除该链接

如果是 EndNote X7 用户可以将数据库和 EndNote 8 或者 9 用户分享，推荐输入每个文件的相对链接路径和绝对路径各一次

1. 首先依次打开菜单References &gt;&gt; File Attachments &gt;&gt; Attach File 以相对路径连接文件两次，在对话框中确保选中「Copy this file to the default file attachments folder and create a relative link」
2. 再依次打开菜单依次打开菜单References &gt;&gt; File Attachments &gt;&gt; Attach File，此时不要选中「Copy this file to the default file attachments folder and create a relative link」

这样就把同一附件建立了一个相对连接和绝对连接

虽然可以插入的附件只是绝对连接，但是如果将数据库传递给使用 EndNote X7 同事时，不能同时传递附件

