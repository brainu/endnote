---
description: Reference Manager 和 EndNote 文献类型和栏目匹配关系
---

# 匹配

使用 EndNote 转换 Reference Manager 数据库时，Reference Manager 文献类型与 EndNote 的文献类型的匹配关系如下表所示。当转换时这些默认设置可以更改，在面板的上方选择从 EndNote 列表中选择 EndNote 的文献类型。

## 文献类型匹配表

本表列举了 Reference Manager 和 EndNote 文献类型的匹配，下表是默认设置。

| 文献类型映射表 |  |
| :--- | :--- |
| Reference Manager | EndNote |
| Generic | Generic |
| Abstract | Journal Articles |
| Art Work | Artwork |
| Audiovisual Material | Audiovisual Material |
| Bill/Resolution | Bill |
| Book Chapter | Book Section |
| Book, Whole | Book |
| Case | Case |
| Catalog | Catalog |
| Computer Program | Computer Program |
| Conference Proceeding | Conference Proceedings |
| Data File | Dataset |
| Edited Book | Edited Book |
| Electronic Citation | Electronic Article |
| Grant | Grant |
| Hearing | Hearing |
| In Press | Journal Article |
| Internet Communication | Personal Communication |
| Journal \(Full\) | Journal Article |
| Journal | Journal Article |
| Magazine Article | Magazine Article |
| Map | Map |
| Motion Picture | Film or Broadcast |
| Music Score | Music |
| Newspaper | Newspaper Article |
| Online Source | Web Page |
| Pamphlet | Pamphlet |
| Patent | Patent |
| Personal Communication | Personal Communication |
| Report | Report |
| Serial \(Book,Monograph\) | Serial |
| Slide | Audiovisual Material |
| Sound Recording | Audiovisual Material |
| Statute | Statute |
| Thesis/Dissertation | Thesis |
| Unenacted Bill/Resolution | Bill |
| Unpublished Work | Unpublished Work |
| Video Recording | Film or Broadcast |

参阅[文献类型列表](../Appendices/List_of_Reference_Types.htm)了解EndNote的完整文献类型

## 栏目匹配关系

Reference Manager 栏目尽可能与 EndNote 匹配，当转换数据库时可以更改默认映射设置。在面板下方选择一个 EndNote 的栏目

有时 Reference Manager 的栏目可能出现破折号，主要出现在 Reference Manager 不存在此栏目，因此显示为虚线。

这些是数据库默认设置

| Field Mapping Table |  |
| :--- | :--- |
| Reference Manager Fields | EndNote Fields |
| Title, primary | Title |
| Authors, primary | Author |
| Dates primary | Date |
| Notes | Notes |
| Keywords | Keywords |
| Reprint | Notes |
| Start Section | Section |
| End Section | Section |
| Periodical | Secondary Title |
| --------- | Notes |
| Title/Code Num | Volume |
| ---------- | Notes |
| ---------- | Notes |
| ---------- | Notes |
| Code | Secondary Title |
| ---------- | Notes |
| User Def 1 | Notes |
| User Def 2 | Notes |
| User Def 3 | Notes |
| User Def 4 | Notes |
| User Def 5 | Notes |
| History | Original Publication |
| ---------- | Notes |
| Abstract | Abstract |
| ISSN/ISBN | Notes |
| Availability | Database Provider |
| Date | Access Date |
| ---------- | Notes |
| ---------- | Notes |
| UNIQUE ID \(DOI\) | DOI |
| Address | Author Address |
| Web/URL | URL |
| File Attachments | File Attachments |
| Link to Full-text | URL |
| Related Links | URL |
| Image\(s\) | Figure |

## 特殊栏目映射条件

EndNote 转换工具可以更改大多数文献类型和字段的匹配关系，但是有些特殊映射不能更改，包括：

* Reference Manager 的 REF ID 常映射为 EndNote 的 Label
* Reference Manager 的 End Page 映射为 EndNote 的 Pages 或 Section

**注：**如果栏目包含数据，EndNote 把 End Page 数据处理为页码区间，如 123-128

* Reference Manager 任何栏目都可映射到 EndNote：
* * 除了 Conference Proceeding, Electronic Citation, Grant, 和 Patent 之外的所有文献类型，发表时间映射为 EndNote 的发表时间
* Conference Proceeding 文献类型：Reference Manager 的 Pub Date \[Date, Primary\] 映射为 EndNote 的 Year Published \[Custom 2\]，任何年代信息都拷贝到 Year Published \[Custom 2\]，完全信息拷贝到 Notes。
* Electronic Citation 文献类型：Reference Manager 的 Last Updated \[Date, Primary\] 映射为 EndNote 的 EndNoteEpub Date \[Section\]，年代信息拷贝到 EndNote 的 Year。
* Grant 文献类型：Reference Manager 的 Pub Date \[Date, Primary\]映射到 EndNote 的 Year，任何年代信息和完整信息拷贝到 Notes。
* Online Source 文献类型：Reference Manager 的 Access Date \[Date Secondary\] 映射为 EndNote 的 Access Date \[Number\]，任何年代信息拷贝到 EndNote 的 Access Year \[Volume\]。
* Patent 文献类型：Reference Manager 的 Date Issued \[Date, Primary\]映射到 EndNote 的 Issue Date \[Custom 2\]，年代信息拷贝到 Year。
* Reference Manager 的Journal 文献类型：
* * 如果会议标题 Title \[Title, secondary\] 含有数据，文献不会根据一般的杂志转换规则，EndNote 会把这样的文献转换为会议论文。
* Thesis/Dissertation 文献类型
* * 如果 Periodical 包含数据，转换时也不会根据一般的 IThesis/Dissertation 规则，EndNote 会把这样的文献使用 Journal 规则进行转换。

