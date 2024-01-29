---
title: '“Formularios personalizados: no se pueden añadir ni quitar de forma masiva formularios personalizados en tareas de plantilla”'
description: Si un usuario intenta añadir o quitar de forma masiva un formulario personalizado en una tarea de plantilla, el formulario no se añade ni se quita y el usuario ve un error.
hidefromtoc: true
feature: Custom Forms
exl-id: e9014f67-2098-46e4-a301-6a742a0c2ddb
source-git-commit: d3d6529fea8f2d020f4920ee5b2bda723f348cc2
workflow-type: ht
source-wordcount: '159'
ht-degree: 100%

---

# Formularios personalizados: no se pueden añadir ni quitar de forma masiva formularios personalizados en tareas de plantilla

>[!NOTE]
>
>Este problema se corrigió el viernes, 18 de enero de 2024.

Si un usuario intenta añadir o quitar de forma masiva un formulario personalizado en una tarea de plantilla, el formulario no se añade ni se quita, y el usuario ve el siguiente error:

[!UICONTROL Intentémoslo de nuevo. Parámetro no válido: valor &quot;XXXXXXXXXXXXXXXX&quot; de templateID]

Si el usuario encuentra la plantilla con el GUID especificado e intenta añadir o quitar formularios personalizados en el resto de las tareas de la plantilla, el error volverá a producirse con otro templateID.

Los formularios personalizados se pueden añadir o quitar en una sola tarea de plantilla. Este error solo se aplica a la adición o eliminación masiva.

_Notificado por primera vez el 10 de noviembre de 2023._
