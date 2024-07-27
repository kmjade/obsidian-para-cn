---
aliases:
  - Obsidian PARA
cssclasses: 
tags:
  - note
  - readme
title: README
date created: 2024-07-21T20:56:00
date modified: 2024-07-23T23:51:00
para: PARA-Obsidian
---

# Obsidian PARA

---

Obsidian 和 PARA 组合。您可以记忆、连接和创造。这是一个通用的组织系统，旨在使您的知识变得可访问和有行动力。

使用 Obsidian 和 P.A.R.A.，您将所有信息存储在纯文本文件中，并且整个结构只有四个类别宽（项目、领域、资源和档案），且不超过三级深（Obsidian > 文件夹 >笔记）。

您可以从这里下载 [obsidian-para-cn](https://github.com/kmjade/obsidian-para-cn.git)。
## [[PARA 是什么]]

## [[PARA-定义]]
## [[为什么选择 Obsidian]]

## 使用本仓库的步骤

首先，[下载本仓库](https://github.com/kmjade/obsidian-para-cn/archive/refs/heads/main.zip)并将其提取到您想要存储 vault 的位置。

考虑将文件夹置于自动备份的位置，如 百度云盘。

如果使用 `git`，则更改 `remote` 到您的仓库，然后使用 [obsidian-git](https://github.com/denolehov/obsidian-git) 插件（不支持 Snaps，遗憾的是）。如果这句话对您来说是 gibberish，那么 simply delete the `.git/` hidden folder。
### [[Obsidian 设置]]

#### 模板

`4 Archive/40 templates/` 目录包含可用于标准化文件头的模板。

要插入模板，创建一个新文件，命名它，然后按下 `Ctrl + p`。然后开始键入“templates”。

![Insert template command pallet](obsidian-insert-template.png)

查看 [Templates help](https://help.obsidian.md/Plugins/Templates) 获取更多信息。

### 迁移到 PARA

1. 在 `4 Archives` 文件夹中创建一个日期文件夹，然后将所有现有文件夹移动到该文件夹中，保持原来的目录结构（记住它并不是删除）
2. 在 `1 Projects` 文件夹中创建每个当前项目的文件夹（记住只有一级子文件夹）
3. 为每个项目设置目标。如果您无法立即想到目标，那么考虑是否该项目应该在 `2 Areas` 中
4. 如果您已经知道一些 `2 Areas`，可以创建对应的文件夹，但尽量不要有太多空文件夹
5. 不要在 `3 Resources` 文件夹中创建任何文件夹。等到您读取或发现东西时再创建子文件夹并添加笔记。
6. 每次您进入 `4 Archives` 将“老”笔记或文件移动到正确的位置。这将突出最常用的笔记，并留下未使用的内容直到它被实际使用（或不）。

一旦您完成了文件夹结构，您就可以将其复制到所有其他系统中；这就是 P.A.R.A. 发挥作用的地方。您想要在计算机本地文件、notes、Dropbox/Google Drive/iCloud 等所有地方都有相同的文件夹结构。这样，您就可以轻松快速地找到需要的信息，无论是在工作还是在同一个领域中。因此，系统化您的_taxonomy_ 到所有应用程序中，这将使您更容易找到需要的信息。

#### 设置提示

- 如果一笔记（或文件）可以放入两个不同的文件夹中，那么就将其放入您最可能需要它的地方，因为文件夹基于可执行性，并且它将被移动到您使用它时。
- 您也可以在 2 个不同根目录下创建相同的文件夹。例如，`2 Areas/Health` 和 `3 Resources/Health`，前者是 **_your_** 健康笔记，而后者是 **general** 健康相关笔记。
- 记住，您不需要将所有当前笔记和文件移动到新文件夹中；将它们都移到 Archive 中，然后在使用它们时移动它们。
- 您也不需要在本地文件和云服务中创建每个文件夹；创建子文件夹是您需要它们时的做法，但您需要在 notes 中有一个完整的设置，以便其他地方作为主要参考。

## Linked（链接）
[Obsidian PARA](https://github.com/kmjade/obsidian-para-cn.git)

[Automating PARA in Obsidian](https://github.com/ren-relaxing/Automating-PARA-in-Obsidian)

