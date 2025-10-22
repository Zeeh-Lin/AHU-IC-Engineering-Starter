## 一、任务目标

本章节旨在帮助你亲身体验 **Git 与 GitHub 的基本协作流程**。
 通过完成以下任务，你将学会如何在工程项目中保存、分享和管理你的代码与文档。

------

## 二、前置准备

在开始前，请确保你已经完成以下准备工作：

1. 安装 [Git](https://git-scm.com/downloads)；
2. 注册一个 [GitHub](https://github.com/) 账号；
3. 了解 Markdown 的基本语法。

然后，将本仓库克隆到本地：

```bash
git clone https://github.com/Zeeh-Lin/AHU-IC-Engineering-Starter.git
```

> [!note]
>
> 你可能会想 *“什么鬼？这串代码是什么？运行在哪里？”*
>
> 产生这种想法是正常的，因为：
>
> 1. 作为大一新生，你可能压根没接触过类似的东西，你甚至可能没用过电脑
> 2. 文章的作者写得很烂，他忘记了给你们充分的提示。（始终记得，文章的作者只是一名普通本科生。他写出来的东西错误百出）
>
> 那么，你该怎么办呢？ **想想在上一份文本中，你学到了什么。**

如果你有上面的疑惑，试着看看[这个](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

> [!note]
>
> 又一个问题！*“怎么都是洋文？！”*
>
> 对于这个问题，有很多种解释。然而，解释这个问题不是我想关注的重点。我只想让你知道：作为EECS领域的学生，你不得不逼着自己读一些英文文档。我知道这很困难，因为我的英语也很烂。但是阅读英文文档是你躲不开的磨砺。

## 三、任务 1：理解版本控制的意义

**任务要求：**
 阅读以下资料，试着用你自己的话解释：
 “为什么工程师必须掌握版本控制工具？”

推荐资料：

- [Pro Git 电子书 · 第一章：起步](https://git-scm.com/book/zh/v2)
- [廖雪峰的 Git 教程 · 简介部分](https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496)

**提交内容：**
 在仓库中新建一个 Markdown 文件（如 `git-thoughts.md`），写下你的理解与收获。

------

## 四、任务 2：创建属于你的分支

**任务要求：**
 在本地新建一个分支，分支名可使用你的姓名或昵称，如 `lin-zihan`、`my-journey` 等。

推荐资料：

- [Learn Git Branching（互动学习网站）](https://learngitbranching.js.org/?locale=zh_CN)

**提交内容：**
 在你的分支中新建一个文件夹，例如 `students/<你的名字>`，并在其中创建一个介绍自己的 Markdown 文件（如 `intro.md`）。

------

## 五、任务 3：推送到远程仓库

**任务要求：**
 将你的分支推送到 GitHub 远程仓库。

推荐资料：

- [Pro Git · 第二章：Git 基础 - 远程仓库的使用](https://git-scm.com/book/zh/v2/Git-基础-远程仓库的使用)

**提交内容：**
 推送完成后，确认你能在 GitHub 仓库的分支列表中看到你的分支。

------

## 六、任务 4：发起 Pull Request

**任务要求：**
 在 GitHub 上发起一个 Pull Request（PR），向主分支提出合并请求。
 即使不会被合并，也请完整体验创建、描述、提交的全过程。

推荐资料：

- [GitHub 官方教程：创建 Pull Request](https://docs.github.com/zh/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

**思考问题：**

- 为什么在团队协作中，Pull Request 是最重要的一环？
- 你在提交 PR 时是否表达清楚了你的更改内容和动机？

------

## 七、任务 5：总结你的思考

**任务要求：**
 思考以下问题：

1. 在完成本教程的过程中，你遇到了哪些困难？
2. 你是如何解决这些问题的？
3. 通过学习 Git 与 GitHub，你对“工程师的工作方式”有了怎样的新认识？

你可以选择在群聊中分享你的答案，帮助更多同学共同成长。

------

## 八、任务 6：进一步探索（选做）

如果你希望更深入地学习 Git，可继续完成以下扩展任务：

1. 学习 `.gitignore` 文件的作用。
2. 了解 GitHub 的 Issues 与 Discussions 功能。
3. 尝试在他人的仓库中贡献内容（Fork → Clone → 修改 → Pull Request）。
4. 学习如何编写规范的提交信息（commit message）。

推荐阅读：

- [Commit message 和 Change log 编写指南 - 阮一峰](https://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html)
- [GitHub Docs：协作基础](https://docs.github.com/zh/get-started/quickstart)
