---
title: 'Formularios personalizados: Los formularios personalizados de objetos cruzados requieren el acceso de Administrar o Editar para editar los campos'
description: Cuando un usuario crea un formulario con objetos cruzados que solo permiten el acceso de Administrar o Editar y, a continuación, quita ese tipo de objeto, el formulario personalizado sigue precisando el acceso de Administrar o Editar para editar los campos. No hay indicación visual de que los campos requieran el acceso de Administrar o Editar y no hay forma de restablecer el formulario.
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 92%
---
# Formularios personalizados: los formularios personalizados de objetos cruzados requieren el acceso de [!UICONTROL Administrar] o [!UICONTROL Editar] para editar los campos

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>Este problema se ha cerrado

Cuando un usuario crea un formulario con objetos cruzados que solo permiten el acceso de [!UICONTROL Administrar] o [!UICONTROL Editar] y, a continuación, quita ese tipo de objeto, el formulario personalizado sigue precisando el acceso de [!UICONTROL Administrar] o [!UICONTROL Editar] para editar los campos. No hay indicación visual de que los campos requieran el acceso de Administrar o Editar y no hay forma de restablecer el formulario.

**Solución**

1. Agregue un salto de sección al formulario con valores predeterminados con los que se rellena.
2. Mueva el salto de sección al principio del formulario.
3. Guarde el formulario.
4. Elimine el salto de sección que acaba de añadir y vuelva a guardar el formulario.

_Notificado por primera vez el jueves, 09 de noviembre de 2022._
