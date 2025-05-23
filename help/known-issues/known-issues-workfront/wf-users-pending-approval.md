---
title: 'Usuarios: el distintivo de aprobación pendiente se muestra en los usuarios nuevos'
description: Los nuevos usuarios de Workfront pueden mostrarse en la lista de usuarios con un distintivo de aprobación pendiente. El distintivo persiste durante más de unos minutos y sigue presente cuando se actualiza la página.
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 1%

---


# Usuarios: El distintivo &quot;Aprobación pendiente&quot; se muestra en los usuarios nuevos

>[!NOTE]
>
>Este problema puede estar presente en las organizaciones que se han migrado a Adobe Admin Console.

Los nuevos usuarios de Workfront pueden aparecer en la lista de usuarios con el distintivo &quot;Aprobación pendiente&quot;. El distintivo persiste durante más de unos minutos y sigue presente cuando se actualiza la página.

Este problema se agrava cuando los usuarios se cargan en lotes grandes, como desde una hoja de cálculo o un Kick-Start de Workfront.

El comportamiento esperado es que el distintivo desaparezca pasados unos minutos y no esté presente cuando se actualice la página.

## Soluciones

Esto ocurre cuando los usuarios agregados a Workfront no se sincronizan con Adobe Admin Console.

Recomendamos las siguientes soluciones:

### Resolución de usuarios individuales

Puede resolver usuarios individuales en la lista Usuarios.

1. Seleccione el usuario o usuarios en la lista Usuarios.
1. Haga clic en el menú de tres puntos del encabezado de la lista.
1. Seleccione **Aprobar**.
1. Después de unos minutos, actualice la página.

### Resolver usuarios añadidos en un lote grande

Para resolver los usuarios que se agregaron en un lote grande, puede agregar el lote de usuarios directamente a Adobe Admin Console.

Para obtener instrucciones, consulte [Administrar varios usuarios | Carga masiva de CSV](https://helpx.adobe.com/enterprise/using/bulk-upload-users.html) en la documentación de Adobe.


_Informado por primera vez el viernes, 08 de mayo de 2025._
