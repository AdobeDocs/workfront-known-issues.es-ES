---
title: "Listas: Los errores de edición en línea producidos por el usuario no causan mensajes de error"
description: "Cuando un usuario está editando en línea un objeto y produce un error que debería crear un mensaje de error, no aparece ningún mensaje de error. El error en sí no se guarda en Workfront, por lo que los datos no se ven afectados, pero la falta de un mensaje de error puede causar confusión."
hidefromtoc: true
source-git-commit: 2951a566384274e5f32544dd8be1872f3850af94
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 96%

---


# Listas: Los errores de edición en línea producidos por el usuario no causan mensajes de error

>[!NOTE]
>
>Este problema se corrigió el 1 de diciembre de 2022.

Cuando un usuario está editando en línea un objeto y produce un error que debería crear un mensaje de error, no aparece ningún mensaje de error. El error en sí no se guarda en Workfront, por lo que los datos no se ven afectados, pero la falta de un mensaje de error puede causar confusión.

Se ha informado de este problema para las siguientes situaciones:

* Predecesores: Se crea un bucle predecesor, como, por ejemplo, la asignación de una tarea a sí misma
* Fechas: Se establece una fecha imposible, como, por ejemplo, una fecha de finalización anterior a la fecha de inicio o posterior a la fecha de finalización del proyecto

_Notificado por primera vez el 26 de octubre de 2022._

