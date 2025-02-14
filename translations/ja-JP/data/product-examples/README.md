---
ms.openlocfilehash: 51fbe18842922b1c8fad2535d2f67230413933c2
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/05/2022
ms.locfileid: "145068279"
---
# 製品ランディングの例

`product-landing` レイアウトを使用するページには、必要に応じて `Examples` セクションを含めることができます。 現在は、3種類の例をサポートしています。

1. コード例については、 https://docs.github.com/en/codespaces#code-examples を参照してください。

2. コミュニティの例については、 https://docs.github.com/en/discussions#community-examples を参照してください。

3. ユーザー例については、 https://docs.github.com/en/sponsors#community-examples を参照してください。

## しくみ

各製品のサンプル データは、`data/product-landing-examples`、**製品** の名前が付けられたサブディレクトリと、**サンプルの型** の名前が付けられた YML ファイルで定義されます (`data/product-examples/sponsors/user-examples.yml` や `data/product-examples/codespaces/code-examples.yml` など)。 現在は、製品ごとに1種類の例のみをサポートしています。

### バージョン管理

現時点では、バージョン付けはコードサンプルでのみサポートしています。 サンプル ブロックを **すべての** バージョンで利用できるようにする必要がある場合、特別なことをする必要はありません。 ただし、サンプル ブロックを一部のバージョンでのみ使用可能にする必要がある場合は、次のような `versions` prop を追加できます。

```
- title: Dependabot version update PR
  description: Example pull request generated by the Dependabot version updates configuration in the Super linter repository.
  href: /github/super-linter/pull/1398
  languages:
  tags:
    - Dependabot
    - Version updates
    - Pull requests
  versions:
    fpt: '*'
  ```

ここで、`versions` の構文は [frontmatter `versions` プロパティ](content/README.md) と同じで、semver 表記をサポートできます。

## 表示

製品のサンプル データは、`middleware/contextualizers/product-examples.js` の `context` オブジェクトに追加されます。

その後、データは `components/landing` によってレンダリングされます。

## スキーマの適用

TODO
