---
title: 'Usuarios: el distintivo de aprobación pendiente se muestra en los usuarios nuevos'
description: Los nuevos usuarios de Workfront pueden mostrarse en la lista de usuarios con un distintivo de aprobación pendiente. El distintivo persiste durante más de unos minutos y sigue presente cuando se actualiza la página.
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%

---

# Usuarios: el distintivo “Aprobación pendiente” se muestra en los usuarios nuevos

>[!NOTE]
>
>Este problema puede darse en organizaciones que hayan migrado a Adobe Admin Console.

Los nuevos usuarios de Workfront pueden aparecer en la lista de usuarios con el distintivo “Aprobación pendiente”. El distintivo persiste durante más de unos minutos y sigue presente cuando se actualiza la página.

Este problema se agrava cuando los usuarios se cargan en lotes grandes, como desde una hoja de cálculo o un Kick-Start de Workfront.

El comportamiento esperado es que el distintivo desaparezca pasados unos minutos y no esté presente cuando se actualice la página.

## Soluciones alternativas

Esto ocurre cuando los usuarios añadidos a Workfront no se sincronizan con Adobe Admin Console.

Recomendamos las siguientes soluciones alternativas:

### Resolver usuarios individuales

Puede resolver usuarios individuales en la lista Usuarios.

1. Seleccione el usuario o usuarios en la lista Usuarios.
1. Haga clic en el menú de tres puntos del encabezado de la lista.
1. Seleccione **Aprobar**.
1. Espere unos minutos y actualice la página.

### Resolver usuarios añadidos en un lote grande

Para resolver los usuarios que se añadieron en un lote grande, puede añadir el lote de usuarios directamente a Adobe Admin Console.

Para obtener instrucciones, consulte [Administrar varios usuarios | Carga masiva de CSV](https://helpx.adobe.com/enterprise/using/bulk-upload-users.html) en la documentación de Adobe.


_Informado por primera vez el 8 de mayo de 2025._
