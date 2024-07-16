---
title: '“Informes: error 500 al exportar un informe”'
description: Cuando un usuario intenta exportar una prueba, el informe no se exporta y aparece el siguiente error. Hay una solución disponible.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# Informes: error 500 al exportar un informe

>[!NOTE]
>
>Este problema se corrigió el sábado, 05 de abril de 2024.

Cuando un usuario intenta exportar un informe, el informe no se exporta y el usuario ve el siguiente mensaje de error:

500: No se puede invocar &quot;com.attask.biz.Parameter.getDisplayType()&quot; porque &quot;parameter&quot; es nulo /attask/api-internal/report/export

Esto ocurre cuando el informe hace referencia a un campo de moneda personalizado de nivel de proyecto.

**Solución alternativa**

Quite la columna que hace referencia al campo de moneda personalizado y vuelva a exportar el informe.

_Notificado por primera vez el viernes, 04 de abril de 2024._
