---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: b74a577bc652f822b4ff9d835952f9b8145ae6dc
workflow-type: tm+mt
source-wordcount: '530'
ht-degree: 58%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2024 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado el problema enviado por usted.

Para ver las actualizaciones de mantenimiento anteriores a 2023, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones en enero de 2024

+++**Actualización de mantenimiento del sábado, 12 de enero de 2024**

### Actualización de mantenimiento el 12 de enero de 2024

#### Tableros

**No se puede adjuntar un documento a una tarjeta**

Cuando un usuario intenta adjuntar un documento a una tarjeta conectada, el usuario puede seleccionar el documento que desea adjuntar, pero el documento no aparece en el área del documento de la tarjeta y el documento no está adjunto al objeto al que está conectada la tarjeta.

Se ha informado de este problema en tarjetas conectadas a problemas.

**La tarjeta aparece en varios sprints**

Cuando un usuario está viendo un sprint en los tableros, las tarjetas que están en diferentes sprints aparecen en el tablero. Este problema es intermitente.

**La tarjeta no se cierra al usar la vista Tableros en un proyecto**

Cuando un usuario está viendo la vista Tableros en una lista de tareas de un proyecto y crea una tarjeta, esta no se cierra ni se guarda. Esto evita que el usuario vuelva al proyecto.

Para cerrar la tarjeta, el usuario debe editar la URL para eliminar &quot;tablero&quot; y cualquier elemento a la derecha de &quot;tablero&quot;.

**Las tarjetas persisten al cambiar la iteración**

Cuando un usuario está viendo una iteración en un panel y luego cambia la iteración, las tarjetas que se muestran para la nueva iteración son las tarjetas de una iteración que el usuario estaba viendo anteriormente.

**Error en [!UICONTROL Comentarios] sección de tarjetas**

Cuando un usuario está viendo una tarjeta y se desplaza a la sección [!UICONTROL Comentarios], los comentarios no se muestran y aparece el siguiente error:

&quot;[!UICONTROL Se ha producido un error. Vuelva a intentarlo más tarde.]&quot;

**Problemas al ver el estado de las subtareas**

Se ha informado de los siguientes problemas relacionados con la visualización del estado de las subtareas en una tarjeta en los paneles:

* El estado se muestra como &quot;Seleccionar estado&quot; incluso cuando la tarea ya tiene un estado. Este estado se puede ver al ver la tarea directamente.
* Si el usuario intenta seleccionar un estado, la pantalla se queda en blanco y debe actualizarse.

**&quot;[!UICONTROL No tiene acceso]&quot; al ver comentarios en una tarjeta**

Cuando un usuario intenta ver los comentarios de una tarjeta que no está conectada a un objeto de [!DNL Workfront], verá el siguiente mensaje:

“[!UICONTROL No tiene acceso para ver comentarios sobre este objeto]”

Esto puede ocurrir incluso cuando el usuario podía ver los comentarios en la tarjeta anteriormente.

+++

+++**Actualización de mantenimiento del jueves, 11 de enero de 2023**

### Actualización de mantenimiento el 11 de enero de 2023

#### Tableros

**Las tarjetas completadas no se cargan correctamente en los paneles dinámicos**

Anteriormente, la única manera de incluir el trabajo completado en un tablero dinámico era cargar las tarjetas como tarjetas archivadas. De lo contrario, las tarjetas completadas no se cargaban en el tablero. Esto causaba problemas para localizar las tarjetas.

Ahora, al crear un tablero dinámico, las tarjetas completadas se cargan de forma predeterminada como tarjetas archivadas, pero puede seleccionar No archivar tarjetas completadas para cargar todas las tarjetas completadas en el tablero como tarjetas visibles en la columna Completado.

+++

## Actualizaciones de mantenimiento anteriores

La información sobre actualizaciones de mantenimiento anteriores está disponible aquí:

* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2023](2023-updates.md)
* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2022](2022-updates.md)
* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2021](2021-updates.md)
