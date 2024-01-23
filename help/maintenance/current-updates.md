---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 67155ccf8996661fb9429c6174a7f5d0cf4a6d8a
workflow-type: tm+mt
source-wordcount: '1085'
ht-degree: 80%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2024 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado el problema enviado por usted.

Para ver las actualizaciones de mantenimiento anteriores a 2023, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones en enero de 2024

+++**Actualización de mantenimiento del viernes, 25 de enero de 2024**

### Actualización de mantenimiento el viernes, 25 de enero de 2024

#### Tableros

**Las tarjetas no se mueven a la columna adecuada cuando se cambia el estado**

Cuando el estado del objeto vinculado de una tarjeta conectada cambia directamente en el objeto, la tarjeta no se mueve a la columna adecuada. Si se cambia el estado del objeto en la tarjeta o se arrastra la tarjeta a la nueva columna, la tarjeta se comporta según lo esperado.

#### Notificaciones

**Marcar las notificaciones como vistas no persiste**

Cuando un usuario marca sus notificaciones como vistas y luego navega a una página diferente dentro de [!DNL Workfront]Sin embargo, el icono de notificaciones sigue mostrando el número de notificaciones no leídas que existían antes de que el usuario las marcara como vistas y las notificaciones siguen apareciendo cuando el usuario hace clic en el icono. Esto continúa si el usuario los marca como vistos y navega a otra página o vuelve a la página original.

+++

+++**Actualización de mantenimiento del viernes, 18 de enero de 2024**

### Actualización de mantenimiento el viernes, 18 de enero de 2024

#### Tableros

**No se puede adjuntar un documento a una tarjeta**

Cuando un usuario intenta adjuntar un documento a una tarjeta conectada, el usuario puede seleccionar el documento que desea adjuntar, pero el documento no aparece en el área del documento de la tarjeta y el documento no está adjunto al objeto al que está conectada la tarjeta.

Se ha informado de este problema en tarjetas conectadas a problemas.

**La tarjeta aparece en varios sprints**

Cuando un usuario está viendo un sprint en los tableros, las tarjetas que están en diferentes sprints aparecen en el tablero. Este problema es intermitente.

**La tarjeta no se cierra al usar la vista Tableros en un proyecto**

Cuando un usuario está viendo la vista Tableros en una lista de tareas de un proyecto y crea una tarjeta, esta no se cierra ni se guarda. Esto evita que el usuario vuelva al proyecto.

Para cerrar la tarjeta, el usuario debe editar la URL para quitar “tablero” y cualquier elemento a la derecha de “tablero”.

**Las tarjetas persisten al cambiar la iteración**

Cuando un usuario está viendo una iteración en un tablero y luego cambia la iteración, las tarjetas que se muestran para la nueva iteración son las tarjetas de una iteración que el usuario estaba viendo anteriormente.

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

#### Formularios personalizados

**No se pueden agregar ni eliminar por lotes formularios personalizados en tareas de plantilla**

Si un usuario intenta añadir o quitar de forma masiva un formulario personalizado en una tarea de plantilla, el formulario no se añade ni se quita, y el usuario ve el siguiente error:

[!UICONTROL Intentémoslo de nuevo. Parámetro no válido: valor &quot;XXXXXXXXXXXXXXXX&quot; de templateID]

Si el usuario encuentra la plantilla con el GUID especificado e intenta añadir o quitar formularios personalizados en el resto de las tareas de la plantilla, el error volverá a producirse con otro templateID.

Los formularios personalizados se pueden añadir o quitar en una sola tarea de plantilla. Este error solo se aplica a la adición o eliminación masiva.

#### Portafolios

**La terminología personalizada no se aplica a las páginas de grupo**

Cuando un usuario establece una terminología personalizada en el nivel de Portfolio, la terminología no se aplica a la página de nivel de grupo.

#### Configurar

**No se pueden ocultar los estados opcionales**

Cuando se intentan ocultar estados opcionales en un sistema y nivel de grupo, el estado no se oculta. Si el usuario ve el estado, la opción para ocultarlo no está habilitada, aunque el usuario sí la haya habilitado y haya guardado los cambios.

**Faltan estados de problemas predeterminados en algunos tipos de problemas de la instalación**

Cuando un usuario está viendo los estados de los problemas en la Configuración, ve que faltan los estados predeterminados para los problemas (Nuevo, En curso y Completado) en algunos tipos de problemas. Los estados predeterminados no tienen la opción de cambiar el tipo de problema, por lo que el usuario no puede volver a configurar los estados para mostrar para los tipos de problema afectados.

#### Equipos

**Problemas con la configuración de los estados de equipo para [!UICONTROL Listo] botón**

Se han notificado los siguientes problemas relacionados con los estados del botón [!UICONTROL Listo] al editar o crear un equipo:

* Es posible que falten algunos estados en el área del botón Listo de la ventana [!UICONTROL Nuevo equipo] o en el área [!UICONTROL Configuración del equipo] de un equipo existente.
* Si el usuario intenta guardar el equipo, es posible que aparezca el error “Debe seleccionar al menos un estado en cada categoría”.

#### Plantillas

**Error al adjuntar una plantilla al proyecto**

Cuando un usuario intenta adjuntar una plantilla a un proyecto, recibe el siguiente error:

“¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo”.

Esto ocurre cuando el usuario no tiene permiso de visualización en un formulario personalizado adjunto a la plantilla.

#### Actualizaciones

**Los comentarios no se transfieren entre la experiencia antigua y la nueva**

Un comentario hecho en la experiencia de comentarios heredada puede no ser visible en la nueva experiencia de comentarios. También puede ocurrir lo contrario.

+++

+++**Actualización de mantenimiento del jueves, 11 de enero de 2023**

### Actualización de mantenimiento el 11 de enero de 2023

#### Tableros

**Las tarjetas completadas no se cargan correctamente en los paneles dinámicos**

Anteriormente, la única manera de incluir el trabajo completado en un tablero dinámico era cargar las tarjetas como tarjetas archivadas. De lo contrario, las tarjetas completadas no se cargaban en el tablero. Esto causaba problemas para localizarlas.

Ahora, al crear un tablero dinámico, las tarjetas completadas se cargan de forma predeterminada como tarjetas archivadas, pero puede seleccionar No archivar tarjetas completadas para cargar todas las tarjetas completadas en el tablero como tarjetas visibles en la columna Completado.

+++

## Actualizaciones de mantenimiento anteriores

La información sobre actualizaciones de mantenimiento anteriores está disponible aquí:

* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2023](2023-updates.md)
* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2022](2022-updates.md)
* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2021](2021-updates.md)
