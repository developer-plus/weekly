# developer-plus 周刊（第 7 期）：Facebook 标志的故事

记录每周值得分享的内容，周一发布。

本周刊开源（GitHub: [developer-plus/weekly](https://github.com/developer-plus/weekly)），欢迎提交 [issue](https://github.com/developer-plus/weekly/issues/new/choose)，投稿或推荐科技内容。

## 本周话题：Facebook 标志的故事

Facebook 总部大楼的标牌，背面是 Sun 公司的标志，那是这栋楼原来的主人。

脸书这样跟员工解释：“背面的那家科技公司是在我们之前出现的，它提醒我们，如果我们失败了，别人就会取代我们。”

<img src="https://oss.hongbusi.com/weekly/7-0.png">

<img src="https://oss.hongbusi.com/weekly/7-1.png">

原文链接：https://v1.benbarry.com/project/the-facebook-sign

## 文章

1、[前 10 个 JavaScript 错误](https://rollbar.com/blog/top-10-javascript-errors-from-1000-projects-and-how-to-avoid-them)

来自 1000 多个项目的前 10 个 JavaScript 错误（以及如何避免它们）。

## 软件

1、[KeyCastr](https://github.com/keycastr/keycastr)

KeyCasstr，一个开源的击键可视化工具。

<img src="https://oss.hongbusi.com/weekly/7-2.png">

2、[Obsidian](https://obsidian.md)

适用于本地 Markdown 文件的知识库。

<img src="https://oss.hongbusi.com/weekly/7-3.png">

3、[Logseq](https://logseq.com) (@likui628 投稿)

Logseq 是一个隐私优先的开源知识库，它在本地纯文本 Markdown 和 Org 模式文件之上工作。使用它来编写、组织和分享您的想法，保留您的待办事项清单，并建立您自己的数字花园。

<img src="https://oss.hongbusi.com/weekly/7-4.png">

## 工具

1、[tabnine - AI 代码补全](https://www.tabnine.com) (@masterX89 投稿)

和 GitHub Copilot 功能相似，均是提供 AI 代码补全能力。

GitHub Copilot 试用结束后，会以 $10/月 和 $100/年的方式收费，tabnine 可以成为很好的替代品。

与 Copilot 不同的是，tabnine 是以使用者的代码作为输入，你写的越多，它越懂你，并且提供本地运算。

缺点就是开发机如果性能不佳大概率带不动。

## 日常踩坑

1、Vue3 markRaw API 的使用 (@MMmaXingXing 投稿)

**问题背景：**

进行 Vue3.0 项目开发的时候遇见了一个类型错误提示需要用 `markRaw` 或者 `shallRef` 进行转换，针对这个问题进行了解决。

**解决方案：**

整体情况介绍以及解决方案整理成了下面的文章，详见：https://juejin.cn/post/7113022337028456461

**问题原因：**

复杂类型比如 component 等要在使用的时候注意不要被响应式转换，否则会对性能进行损耗。

**相关文档：**

https://v3.cn.vuejs.org/api/basic-reactivity.html#markraw

## 最后

developer-plus made with 💗. (完)
