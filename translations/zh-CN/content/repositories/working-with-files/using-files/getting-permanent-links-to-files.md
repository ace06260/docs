---
title: 创建文件的永久链接
intro: '在 {% data variables.product.product_location %} 上查看文件时，您可以按 "y" 键将 URL 更新为指向所查看文件精确版本的永久链接。'
redirect_from:
  - /articles/getting-a-permanent-link-to-a-file
  - /articles/how-do-i-get-a-permanent-link-from-file-view-to-permanent-blob-url
  - /articles/getting-permanent-links-to-files
  - /github/managing-files-in-a-repository/getting-permanent-links-to-files
  - /github/managing-files-in-a-repository/managing-files-on-github/getting-permanent-links-to-files
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Repositories
shortTitle: Permanent links to files
ms.openlocfilehash: 4e3d5ec282f7f7ba820094240698c88e298cdb69
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/05/2022
ms.locfileid: '145129232'
---
{% tip %}

提示：在 {% data variables.product.product_name %} 的任意页面上按“?”可查看所有可用的键盘快捷键。

{% endtip %}

## 文件视图显示分支上的最新版本

在 {% data variables.product.product_location %} 上查看文件时，通常会在分支头部看到当前版本。  例如：

* [https://github.com/github/codeql/blob/ main/README.md](https://github.com/github/codeql/blob/main/README.md)

引用 GitHub 的 `codeql` 存储库，并显示 `main` 分支中 `README.md` 文件的当前版本。

分支头部的文件版本可能会随着新的提交而改变，因此如果您复制常规的 URL，当以后有人查看时，文件内容可能会不同。

## 按 <kbd>Y</kbd> 永久链接到特定提交中的文件

要永久链接到所查看的特定版本的文件，请不要在 URL 中使用分支名称（即上面示例中的 `main` 部分），而是使用提交 ID。这将永久链接到与该提交中完全相同的文件版本。  例如：

* [https://github.com/github/codeql/blob/ b212af08a6cffbb434f3c8a2795a579e092792fd/README.md](https://github.com/github/codeql/blob/b212af08a6cffbb434f3c8a2795a579e092792fd/README.md)

将 `main` 替换为特定的提交 ID，文件内容将不会发生变化。

但是，手动查找提交 SHA 比较麻烦，因此可以采用便捷方式，通过键入 <kbd>y</kbd> 将 URL 自动更新为永久链接版本。  然后，您可以复制该 URL，以后访问它的任何人都将看到与您所见完全一致的内容。

{% tip %}

提示：可以将可解析为提交的任何标识符放在 URL 中，包括分支名称、特定提交 SHA 或标记！

{% endtip %}

## 创建指向代码段的永久链接

您可以创建指向特定版本的文件或拉取请求中特定代码行或行范围的永久链接。 有关详细信息，请参阅“[创建代码片段的永久链接](/articles/creating-a-permanent-link-to-a-code-snippet/)”。

## 延伸阅读

- [存档 GitHub 存储库](/articles/archiving-a-github-repository)
