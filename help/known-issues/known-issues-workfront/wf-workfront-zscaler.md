---
title: "Workfront: La configuración de ZScaler puede causar un rendimiento reducido"
description: El servicio web de ZScaler utiliza http/1.1 de forma predeterminada, lo que puede reducir el rendimiento en Workfront.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---

# Workfront: La configuración de ZScaler puede reducir el rendimiento

>[!NOTE]
>
>Este es un problema con ZScaler y Workfront no lo solucionará.

El servicio web de ZScaler usa `http/1.1` de forma predeterminada, lo que puede reducir el rendimiento en Workfront.

**Solución alternativa**

Configure el software ZScaler para que use `http/2`. Esto no se puede configurar en Workfront.

Puede encontrar información sobre `http/2` en la documentación de ZScaler.

_Notificado por primera vez el martes, 18 de noviembre de 2024._
