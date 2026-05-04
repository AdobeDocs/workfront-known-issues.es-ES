---
title: 'Aprobaciones: la delegación de aprobaciones está fijada para un número incorrecto de días'
description: Cuando un usuario programa tiempo libre personal y delega sus aprobaciones para ese tiempo, la delegación puede incluir días anteriores o posteriores al tiempo libre programado.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
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
