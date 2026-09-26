---
title: 'Aprobaciones: la delegación de aprobaciones está fijada para un número incorrecto de días'
description: Cuando un usuario programa tiempo libre personal y delega sus aprobaciones para ese tiempo, la delegación puede incluir días anteriores o posteriores al tiempo libre programado.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# Aprobaciones: la delegación de aprobaciones está fijada para un número incorrecto de días

<!--Live for workaround-->

>[!NOTE]
>
>Este problema se ha cerrado porque no existe ningún error.

Cuando un usuario programa tiempo libre personal y delega sus aprobaciones para ese tiempo, la delegación puede incluir días anteriores o posteriores al tiempo libre programado.

**Solución**

Esta discrepancia se debe a una discrepancia entre la zona horaria del perfil de un usuario y la del horario asignado al usuario.

Se recomienda crear un horario único para cada zona horaria desde la que trabajen los usuarios, y asignar a cada uno el horario que coincida con la zona horaria de su perfil de usuario.

_Notificado por primera vez el viernes, 24 de marzo de 2022._
