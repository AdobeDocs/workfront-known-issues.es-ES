---
title: "Informes: error 500 al exportar un informe"
description: '"Cuando un usuario intenta exportar un informe, el informe no se exporta y el usuario ve un error. Hay una solución disponible”.'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 0dbb29f11088b5c963f7972f3ec9e64ee55d6263
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 23%

---


# Informes: error 500 al exportar un informe

Cuando un usuario intenta exportar un informe, el informe no se exporta y el usuario ve el siguiente error:

500: No se puede invocar &quot;com.attask.biz.Parameter.getDisplayType()&quot; porque &quot;parameter&quot; es nulo /attask/api-internal/report/export

Esto ocurre cuando el informe hace referencia a un campo de moneda personalizado de nivel de proyecto.

**Solución alternativa**

Elimine la columna que hace referencia al campo de moneda personalizado y vuelva a exportar el informe.

_Notificado por primera vez el viernes, 04 de abril de 2024._

