---
title: Agregar un código de conducta a tu proyecto
intro: 'Adoptar un código de conducta para definir los estándares de la comunidad, señalizar un proyecto cordial e inclusivo, y delinear los procedimientos para manejar los abusos.'
redirect_from:
  - /articles/adding-a-code-of-conduct-to-your-project
  - /github/building-a-strong-community/adding-a-code-of-conduct-to-your-project
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Community
shortTitle: Add a code of conduct
ms.openlocfilehash: dcf1e589ae4f803017752f9e919aad304c570fbc
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: '145092360'
---
Un *código de conducta* define las normas para participar en una comunidad. Señala un entorno inclusivo que respeta todas las contribuciones. También describe los procedimientos para tratar problemas de tus proyectos entre los miembros de la comunidad. Para obtener más información sobre por qué un código de conducta define los estándares y las expectativas de participación en una comunidad, consulte la [Guía de código abierto](https://opensource.guide/code-of-conduct/).

Antes de adoptar un código de conducta para tu proyecto:

* Investiga códigos de conducta diferentes diseñados para proyectos de código abierto. Elije uno que refleje los estándares de tu comunidad.
* Considera cuidadosamente si estás dispuesto a hacerlo cumplir y puedes hacerlo.

Puedes agregar un código de conducta a tu proyecto si utilizas una plantilla o creando manualmente un código de conducta personalizado. Tu código de conducta estará disponible de cualquier forma, pero el "Código de conducta" solo se marcará como completo en el perfil comunitario de tu repositorio si utilizas una plantilla. Si utilizas un código de conducta que escriba otra persona u organización, asegúrate de utilizar los lineamientos de adjudicación de la fuente. Para obtener más información sobre los perfiles de la comunidad, consulte "[Acerca de los perfiles de la comunidad para repositorios públicos](//communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories)".

Puedes crear un código de conducta predeterminado para tu organización o cuenta personal. Para más información, vea "[Creación de un archivo de estado de la comunidad predeterminado](/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)".

## Agregar un código de conducta mediante una plantilla

{% data variables.product.product_name %} brinda plantillas para códigos de conducta comunes a fin de ayudarte a agregar rápidamente un código de conducta para tu proyecto.

{% data reusables.repositories.navigate-to-repo %} {% data reusables.files.add-file %}
3. En el campo de nombre del archivo, escriba *CODE_OF_CONDUCT.md*.
4. Haga clic en **Choose a code of conduct template**.
  ![Botón para elegir una plantilla de código de conducta](/assets/images/help/repository/code-of-conduct-tool.png)
5. En el lateral izquierdo de la página, selecciona un código de conducta para previsualizar y agregar a tu proyecto.
  ![Selección de una plantilla de código de conducta](/assets/images/help/repository/code-of-conduct-tool-picker.png)
6. En el lateral derecho de la página, completa los campos para llenar el código de conducta seleccionado con la información adecuada.
7. Haga clic en **Review and submit**.
  ![Revisar y enviar el código de conducta a un proyecto](/assets/images/help/repository/code-of-conduct-tool-review.png)
8. Revisa los contenidos del código de conducta que está en el área de texto.
{% data reusables.files.write_commit_message %} {% data reusables.files.choose_commit_branch %} {% data reusables.files.propose_new_file %}

## Agregar un código de conducta manualmente

Si el código de conducta que quieres utilizar no se encuentra disponible en las plantillas proporcionadas, puedes agregar manualmente un código de conducta.

{% data reusables.repositories.navigate-to-repo %} {% data reusables.files.add-file %}
3. En el campo de nombre, teclea el nombre y la extensión del archivo.
  ![Nombre de archivo del código de conducta nuevo](/assets/images/help/repository/new-code-of-conduct-file-name.png)
    - Para que el código de conducta se muestre como visible en el directorio raíz del repositorio, escriba *CODE_OF_CONDUCT* en el campo de nombre de archivo.
    - Para que el código de conducta sea visible en el directorio `docs` del repositorio, escriba *docs/CODE_OF_CONDUCT*.
    - Para que el código de conducta sea visible en el directorio `.github` del repositorio, escriba *.github/CODE_OF_CONDUCT*.
4. En el archivo nuevo, agrega tu código de conducta personalizado.
{% data reusables.files.write_commit_message %} {% data reusables.files.choose_commit_branch %} {% data reusables.files.propose_new_file %}
