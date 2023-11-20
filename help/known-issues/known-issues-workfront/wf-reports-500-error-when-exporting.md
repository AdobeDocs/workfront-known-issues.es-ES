---
title: "Informes: Error 500 al exportar un informe"
description: "Cuando un usuario intenta exportar un informe, la exportación falla con un error 500."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# Informes: Error 500 al exportar un informe

Cuando un usuario intenta exportar un informe, la exportación falla con el siguiente error:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Se ha informado de este problema en informes que utilizan un `valueexpression` para hacer referencia al `lastNote` texto de nota.

_Informado por primera vez el 8 de noviembre de 2023._
