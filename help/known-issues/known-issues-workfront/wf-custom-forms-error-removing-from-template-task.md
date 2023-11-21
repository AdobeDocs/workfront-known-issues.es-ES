---
title: "Formularios personalizados: no se pueden agregar ni eliminar por lotes formularios personalizados en tareas de plantilla"
description: "Si un usuario intenta agregar o quitar de forma masiva un formulario personalizado en una tarea de plantilla, el formulario no se agrega ni se quita y el usuario ve un error."
hidefromtoc: true
feature: Custom Forms
source-git-commit: 41df80641db82b225753338d8564e12b90566c40
workflow-type: tm+mt
source-wordcount: '153'
ht-degree: 5%

---


# Formularios personalizados: no se pueden agregar ni eliminar por lotes formularios personalizados en tareas de plantilla

Si un usuario intenta agregar o quitar de forma masiva un formulario personalizado en una tarea de plantilla, el formulario no se agrega ni se quita y el usuario ve el siguiente error:

[!UICONTROL Intentémoslo de nuevo. Parámetro no válido: valor &quot;XXXXXXXXXXXXXXXX&quot; de templateID]

Si el usuario encuentra la plantilla con el GUID especificado e intenta agregar o quitar formularios personalizados en el resto de las tareas de la plantilla, el error volverá a producirse con otro templateID.

Los formularios personalizados se pueden agregar o quitar en una sola tarea de plantilla. Este error solo se aplica a la adición o eliminación masiva.

_Notificado por primera vez el 10 de noviembre de 2023._
