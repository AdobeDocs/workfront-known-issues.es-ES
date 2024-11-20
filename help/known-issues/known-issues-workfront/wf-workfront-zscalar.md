---
title: "Workfront: La configuración de ZScalar puede reducir el rendimiento"
description: '"El servicio web de ZScalar utiliza http/1.1 de forma predeterminada, lo que puede reducir el rendimiento en Workfront".'
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---


# Workfront: La configuración de ZScalar puede reducir el rendimiento

>[!NOTE]
>
>Este es un problema con ZScalar y Workfront no lo solucionará.

El servicio web de ZScalar usa `http/1.1` de forma predeterminada, lo que puede reducir el rendimiento en Workfront.

**Solución alternativa**

Configure el software de ZScalar para que use `http/2`. Esto no se puede configurar en Workfront.

Puede encontrar información sobre `http/2` en la documentación de ZScalar.

_Notificado por primera vez el martes, 18 de noviembre de 2024._
