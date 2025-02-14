---
title: リポジトリへのトラフィックを表示する
intro: フルクローン (フェッチではない)、過去 14 日間の訪問者、参照サイト、トラフィックグラフの人気コンテンツなど、リポジトリへのプッシュアクセスを持つユーザは誰でもそのトラフィックを表示できます。
product: 'This repository insights graph is available in public repositories with {% data variables.product.prodname_free_user %} and {% data variables.product.prodname_free_team %} for organizations, and in public and private repositories with {% data variables.product.prodname_pro %}, {% data variables.product.prodname_team %}, and {% data variables.product.prodname_ghe_cloud %}.{% ifversion fpt %} For more information, see "[About repository graphs](/articles/about-repository-graphs)" and "[{% data variables.product.prodname_dotcom %}''s products](/articles/github-s-products)."{% endif %}'
redirect_from:
  - /articles/viewing-traffic-to-a-repository
  - /github/visualizing-repository-data-with-graphs/viewing-traffic-to-a-repository
  - /github/visualizing-repository-data-with-graphs/accessing-basic-repository-data/viewing-traffic-to-a-repository
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Repositories
shortTitle: View repository traffic
ms.openlocfilehash: 75b4900893a0874e42b076962d25babcb4c09233
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/05/2022
ms.locfileid: '145132007'
---
特定のパスが参照されていたリンクから、検索エンジンと {% data variables.product.product_name %} 自体を除く、参照元サイトに移動できます。 人気のあるコンテンツは、トラフィックを発生させた特定のコンテンツにリンクしています。

参照サイトと人気のあるコンテンツは、ビューと一意の訪問者によって並べ替えられます。 フルクローンと訪問者情報は 1 時間ごとに更新され、参照サイトと人気のあるコンテンツセクションは毎日更新されます。 現在地に関係なく、トラフィックグラフのすべてのデータは、UTC+0 タイムゾーンを使用します。

{% tip %}

**参考:** トラフィックグラフで特定の日にカーソルを合わせると、その日の正確なデータを表示できます。

{% endtip %}

![ツールチップを使用したリポジトリトラフィックグラフ](/assets/images/help/graphs/repo_traffic_graphs_tooltip_dotcom.png)

## トラフィックグラフにアクセスする

{% data reusables.repositories.navigate-to-repo %} {% data reusables.repositories.accessing-repository-graphs %}
3. 左側のサイドバーで、 **[トラフィック]** をクリックします。
![[トラフィック] タブ](/assets/images/help/graphs/traffic_tab.png)
