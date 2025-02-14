---
title: Acerca de webhooks
redirect_from:
  - /post-receive-hooks
  - /articles/post-receive-hooks
  - /articles/creating-webhooks
  - /articles/about-webhooks
  - /github/extending-github/about-webhooks
intro: Los webhooks ofrecen una manera de enviar las notificaciones a un servidor web externo siempre que ciertas acciones ocurran en un repositorio o una organización.
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
ms.openlocfilehash: 30232a560237d473f17ec01d6451cb25195521fc
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: '145112129'
---
{% tip %}

**Sugerencia:** {% data reusables.organizations.owners-and-admins-can %} administrar los webhooks de una organización. {% data reusables.organizations.new-org-permissions-more-info %}

{% endtip %}

Los webhooks se pueden disparar siempre que se realicen una variedad de acciones en un repositorio o una organización. Por ejemplo, puedes configurar tus webhooks para ejecutarse siemrpe que:

* Se suba a un repositorio.
* Se abra una solicitud de extracción.
* Se cree un sitio {% data variables.product.prodname_pages %}.
* Se agregue un nuevo miembro a un equipo.

Al utilizar la API de {% ifversion fpt or ghec %}{% data variables.product.prodname_dotcom %}{% else %}{% data variables.product.product_name %}{% endif %}, puedes hacer que estos webhooks actualicen un rastreador de propuesta externo, activen compilaciones de IC, actualicen una réplica de respaldo o incluso desplieguen en tu servidor de producción.

Para configurar un webhook nuevo, necesitarás acceso a un servidor externo y estar familiarizado con los procedimientos técnicos involucrados. Para obtener ayuda para crear un webhook, así como una lista completa de acciones con las que lo puede asociar, consulte "[Webhooks](/webhooks)".
