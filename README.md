---
aliases:
  - "[readme, 读我]"
cssclasses: 
tags:
  - note
  - readme
title: README
linter-yaml-title: README
date created: 2024-07-21T20:56:00
date modified: 2024-07-21T22:41:00
---
# README
---

# Obsidian PARA

[Medium 视图](https://b-yarbrough.medium.com/obsidian-and-para-are-the-perfect-pairing-together-you-can-remember-connect-and-create-7a87c8882de5)

Obsidian 和 PARA 是完美的组合。一起，您可以记忆、连接和创造。这是一个通用的组织系统，旨在使您的知识变得可访问和有行动力。

使用 Obsidian 和 PARA，您将所有信息存储在 plaintext 文件中，而整个层次结构只有四个类别宽（项目、领域、资源、档案），且不超过四级深（Obsidian > vault > 文件夹 > 备忘录）。

您可以从这里下载 Obsidian PARA starter kit [here](https://github.com/byarbrough/obsidian-para/archive/refs/heads/main.zip) 或使用 Git。

## PARA 是什么

> [P.A.R.A.](https://fortelabs.co/blog/para/) 的缩写是项目（Projects）— 领域（Areas）— 资源（Resources）— 档案（Archives），这四个顶级类别包含了您可能在工作和生活中遇到的所有类型信息。它是 Tiago Forte 设计的通用组织系统。

每个四个 PARA 文件夹都是可操作的。项目文件夹包含具有指定时间表的明确目标，而档案文件夹可能会长期不活动。

从不超过每个文件夹下只有一个子文件夹！这样，您就不会迷失在层次结构中，而是可以轻松地访问所有信息。

![P.A.R.A. 组件定义](https://i0.wp.com/cdn-images-1.medium.com/max/800/1*i6I0M5kaZUOwIfq5q5W4mQ.jpeg)

**项目** 是“目标的系列任务，具有截止日期。”

示例包括：完成应用程序 mockup；开发项目计划；执行商业发展活动；写博客文章；最终确定产品规格；出席会议

**领域责任** 是“长期维持标准的活动范围。”

示例包括：健康；财务；职业发展；旅行；嗜好；朋友；公寓；汽车；生产力；直属报告；产品开发；写作

**资源** 是“持续关心的话题或主题.”

示例包括：习惯形成；项目管理；超人主义；咖啡；音乐；园艺；在线营销；SEO；室内设计；建筑；笔记记录

**档案** 包括“来自其他三个类别的无效项。”

示例包括：已经完成或变为无效的项目；您不再维持的领域责任；您不再感兴趣的资源。

### 逐步总结

PARA旨在使您能够**记忆**、**连接**和**创造**。

![P.A.R.A. 中信息流动](https://i0.wp.com/cdn-images-1.medium.com/max/800/1*qng-pJJUdoENmYs_3HiISg.jpeg)

您应该能够捕捉值得保存的想法，随机连接这些想法与其他想法，并使用您的精心整理、层次化知识库来创造您喜欢且有价值的内容。

通过[逐步总结](https://fortelabs.co/blog/progressive-summarization-a-practical-technique-for-designing-discoverable-notes)，您可以实现这一点。这是一种策略，回答了问题：“如何使我现在消费的内容变得容易发现我的未来自我？”

逐步总结的核心是，每当您与笔记交互时，您都会将其压缩一些。随着压缩，它会失去一些原始上下文，但您有机会将其连接到其他和新想法。

更多信息，请见 Forte 的[Building a Second Brain Course](https://fortelabs.co/blog/basboverview/) 和 [Progressive Summarization](https://fortelabs.co/blog/progressive-summarization-a-practical-technique-for-designing-discoverable-notes) 文章。

## 为什么选择 Obsidian

> [Obsidian](https://obsidian.md/) 是一个基于本地文件夹的 Markdown 文件知识库。

它支持 Windows、macOS、Linux、Android 和 iPhone。

![Obsidian 界面截图](https://obsidian.md/images/screenshot.png)

以下是 Obsidian 的关键特性，为什么选择它：

1. **标签和链接都是首等级**。人类大脑非线性：我们跳跃于想法之间，时刻如此。图形视图允许您探索链接。
2. **轻松搜索**。您可以立即搜索所有文件以找到短语或关键词。
3. **不需要担心被锁定**。文件是 plain Markdown，存储在本地。因此，如果您决定使用不同的编辑器，您不需要担心无法从专有格式中导出它们。
4. **美观和简单**。编辑器是简单的，但功能强大，让您更多空间思考，少一些干扰。并且，可以根据您的需求自定义插件，以适合您。
5. **跨设备同步**。无缝同步所有计算机和移动设备。文件加密，只有您可以阅读它们。

## 使用本仓库的步骤

首先，[下载本仓库](https://github.com/byarbrough/obsidian-para/archive/refs/heads/main.zip)并将其提取到您想要存储 vault 的位置。

考虑将文件夹置于自动备份的位置，如 iCloud 或 GoogleDrive。

如果使用 `git`，则更改 `remote` 到您的仓库，然后使用 [obsidian-git](https://github.com/denolehov/obsidian-git) 插件（不支持 Snaps，遗憾的是）。如果这句话对您来说是 gibberish，那么 simply delete the `.git/` hidden folder。

### Obsidian 设置

[安装 Obsidian](https://obsidian.md/)。

打开 Obsidian 并选择“Open folder as vault”。

![Open folder as vault](images/obsidian-folder-as-vault.png)

打开这个文件夹。

vault 的设置保存在隐藏的文件夹 `.obsidian/` 中。当前，多个核心插件已启用。所有社区插件和主题都禁用。你可以在设置中更改这项。

如果您使用 Obsidian 在多个设备上，请务必购买并设置 [Obsidian Sync](https://obsidian.md/sync)。

#### 模板

`templates/` 目录包含可用于标准化文件头的模板。

要插入模板，创建一个新文件，命名它，然后按下 `Ctrl + p`。然后开始键入“templates”。

![Insert template command pallet](images/obsidian-insert-template.png)

查看 [Templates help](https://help.obsidian.md/Plugins/Templates) 获取更多信息。

### 迁移到 PARA

1. 在 `4. Archives` 文件夹中创建一个日期文件夹，然后将所有现有文件夹移动到该文件夹中，保持原来的目录结构（记住它并不是删除）
2. 在 `1. Projects` 文件夹中创建每个当前项目的文件夹（记住只有一级子文件夹）
3. 为每个项目设置目标。如果您无法立即想到目标，那么考虑是否该项目应该在 `2. Areas` 中
4. 如果您已经知道一些 `2. Areas`，可以创建对应的文件夹，但尽量不要有太多空文件夹
5. 不要在 `3. Resources` 文件夹中创建任何文件夹。等到您读取或发现东西时再创建子文件夹并添加笔记。

每次您进入 `4. Archives` 将“老”笔记或文件移动到正确的位置。这将突出最常用的笔记，并留下未使用的内容直到它被实际使用（或不）。

一旦您完成了文件夹结构，您就可以将其复制到所有其他系统中；这就是 P.A.R.A. 发挥作用的地方。您想要在计算机本地文件、notes、Dropbox/Google Drive/iCloud 等所有地方都有相同的文件夹结构。这样，您就可以轻松快速地找到需要的信息，无论是在工作还是在同一个领域中。因此，系统化您的_taxonomy_ 到所有应用程序中，这将使您更容易找到需要的信息。

#### 设置提示

- 如果一笔记（或文件）可以放入两个不同的文件夹中，那么就将其放入您最可能需要它的地方，因为文件夹基于可执行性，并且它将被移动到您使用它时。
- 您也可以在 2 个不同根目录下创建相同的文件夹。例如，`2. Areas/Health` 和 `3. Resources/Health`，前者是 **_your_** 健康笔记，而后者是 **general** 健康相关笔记。
- 记住，您不需要将所有当前笔记和文件移动到新文件夹中；将它们都移到 Archive 中，然后在使用它们时移动它们。
- 您也不需要在本地文件和云服务中创建每个文件夹；创建子文件夹是您需要它们时的做法，但您需要在 notes 中有一个完整的设置，以便其他地方作为主要参考。
