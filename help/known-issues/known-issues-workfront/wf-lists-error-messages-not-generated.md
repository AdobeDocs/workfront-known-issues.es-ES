---
title: "Listas: Los errores de edición en línea por usuario no causan mensajes de error"
description: '"Cuando un usuario está editando en línea un objeto y produce un error que debería crear un mensaje de error, no aparece ningún mensaje de error. El error en sí no se guarda en Workfront, por lo que los datos no se ven afectados, pero la falta de un mensaje de error puede causar confusión".'
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 2%

---


# Listas: Los errores de edición en línea por usuario no causan mensajes de error

Cuando un usuario está editando en línea un objeto y produce un error que debería crear un mensaje de error, no aparece ningún mensaje de error. El error en sí no se guarda en Workfront, por lo que los datos no se ven afectados, pero la falta de un mensaje de error puede causar confusión.

Esto se ha informado en las siguientes situaciones:

* Predecesores: Se crea un bucle predecesor, como la asignación de una tarea a sí misma
* Fechas: Se establece una fecha imposible, como una fecha de finalización anterior a la fecha de inicio o posterior a la fecha de finalización del proyecto

_Notificado por primera vez el 26 de octubre de 2022._

