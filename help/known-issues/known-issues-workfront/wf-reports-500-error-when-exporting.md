---
title: 'Informes: error 500 al exportar un informe'
description: Cuando un usuario intenta exportar un informe, la exportación falla con un error 500.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 100%

---

# Informes: error 500 al exportar un informe

>[!NOTE]
>
>Este problema se corrigió el 30 de noviembre de 2023.

Cuando un usuario intenta exportar un informe, la exportación falla con el siguiente error:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Se ha informado de este problema en informes que utilizan un `valueexpression` para hacer referencia a la nota de texto `lastNote`.

_Notificado por primera vez el 8 de noviembre de 2023._
