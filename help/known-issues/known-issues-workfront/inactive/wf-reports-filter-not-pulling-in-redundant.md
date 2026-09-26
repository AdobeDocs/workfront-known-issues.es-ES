---
title: 'Informes: el filtro de informes no devuelve los resultados esperados'
description: Es posible que un filtro de un informe no devuelva todos los resultados esperados. Hay una solución disponible.
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 100%
---
# Informes: el filtro de informes no devuelve los resultados esperados

>[!NOTE]
>
>Este problema se ha cerrado.

Es posible que un filtro de un informe no devuelva todos los resultados esperados.

Esto puede ocurrir cuando el filtro está configurado para devolver resultados con determinados criterios, e incluye una regla OR que devuelve resultados que son un subconjunto de esos mismos criterios.

**Solución**

Asegúrese de que los bloques OR del filtro no incluyan criterios de evaluación idénticos.

_Notificado por primera vez el martes, 11 de marzo de 2024._
