---
title: 'Workfront: la configuración de ZScaler puede reducir el rendimiento'
description: El servicio web de ZScaler utiliza http/1.1 de forma predeterminada, lo que puede reducir el rendimiento en Workfront.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront: la configuración de ZScaler puede reducir el rendimiento

>[!NOTE]
>
>Es un problema de ZScaler y Workfront no lo solucionará.

El servicio web de ZScaler usa `http/1.1` de forma predeterminada, lo que puede reducir el rendimiento en Workfront.

**Solución**

Configure el software ZScaler para que use `http/2`. Esto no se puede configurar en Workfront.

Puede encontrar información sobre `http/2` en la documentación de ZScaler.

_Notificado por primera vez el martes, 18 de noviembre de 2024._
