---
title: 'Error: Problema en el certificado SSL, verificar que el certif. CA esté bien'
intro: 'Este error significa que el certificado raíz de tu CA está desactualizado. Si es necesario actualizar el certificado de raíz de tu CA, no podrás subir ni extraer desde los repositorios de {% data variables.product.product_name %}.'
redirect_from:
  - /articles/error-ssl-certificate-problem-verify-that-the-ca-cert-is-ok
  - /github/authenticating-to-github/error-ssl-certificate-problem-verify-that-the-ca-cert-is-ok
  - /github/authenticating-to-github/troubleshooting-ssh/error-ssl-certificate-problem-verify-that-the-ca-cert-is-ok
versions:
  fpt: '*'
  ghec: '*'
topics:
  - SSH
shortTitle: SSL certificate problem
ms.openlocfilehash: 26777edf5b312c8f45c5b1fb211b87648778cf13
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: '145091737'
---
Probablemente recibirás el siguiente error:

```shell
$ git push -u github.main
> fatal: 'github.main' does not appear to be a git repository
> fatal: The remote end hung up unexpectedly

$ git pull -u github
> error: SSL certificate problem, verify that the CA cert is OK. Details:
> error:14090086:SSL routines:SSL3_GET_SERVER_CERTIFICATE:certificate verify failed while accessing https://github.com/tqisjim/google-oauth.git/info/refs
> fatal: HTTP request failed
```

"CA" es la forma abreviada de "autoridad de certificado". Las autoridades de certificado son un grupo independiente responsable de manejar las conexiones seguras en la web. Estas autoridades establecen "certificados" digitales, que son una forma de asegurar que las conexiones entre dos máquinas (como tu computadora y GitHub.com) son válidas. Sin un certificado, el riesgo de seguridad entre dos máquinas es mayor.

Cuando recibes este error, probablemente significa que tu CA está desactualizado y requiere una actualización. Por lo general, al actualizar tu sistema operativo también se actualizar tu CA y se resuelve el problema.
