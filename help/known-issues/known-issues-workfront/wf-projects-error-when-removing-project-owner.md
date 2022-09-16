---
title: '''Proyectos: Error al quitar el propietario del proyecto del encabezado"'
description: Cuando un usuario intenta quitar un propietario de proyecto del encabezado de un proyecto, este no se elimina y aparece un mensaje de error.
hidefromtoc: true
exl-id: 3a995df4-5d6a-44e4-a644-997931c044bf
source-git-commit: 7570b2a560505d66e0e83656c9a601226998c11c
workflow-type: tm+mt
source-wordcount: '97'
ht-degree: 0%

---

# Proyectos: Error al quitar la variable [!UICONTROL Propietario del proyecto] desde el encabezado

>[!NOTE]
>
>Este problema se corrigió el 9 de septiembre de 2022.

Cuando un usuario intenta eliminar un [!UICONTROL Propietario del proyecto] desde el encabezado de un proyecto, la variable [!UICONTROL Propietario del proyecto] no se elimina y el usuario ve el siguiente mensaje de error:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Solución alternativa**

Elimine el[!UICONTROL  Propietario del proyecto] del [!UICONTROL Detalles] .

_Informe por primera vez el 9 de agosto de 2022._
