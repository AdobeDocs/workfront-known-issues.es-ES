---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 44c6b3f903d88dff46077f5805da31f9ec3c0923
workflow-type: tm+mt
source-wordcount: '2093'
ht-degree: 96%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2024 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado el problema enviado por usted.

Para ver las actualizaciones de mantenimiento anteriores a 2023, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones en marzo de 2024

+++**Actualización de mantenimiento del viernes, 07 de marzo de 2024**

### Actualización de mantenimiento el 7 de marzo de 2024

#### Tableros

**Error 400 al añadir una tarea a un tablero**

Cuando se intenta visualizar un proyecto y se intenta añadir una tarea a un tablero, la tarea no se añade y aparece el siguiente error:

Error: &quot;400: undefined /boards-service/graphql&quot;

#### Inicio

**Error al editar en línea una tarea en el widget Mi tarea**

Cuando un usuario intenta editar en línea una tarea en el widget Mis tareas, ve el siguiente error:

&quot;Se produjo un error y se está tratando de resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador.”


#### Distribuidor de cargas de trabajo

**Las horas planificadas no se actualizan en el Distribuidor de cargas de trabajo**

Cuando se actualizan las horas planificadas de un proyecto, no se actualizan en el Distribuidor de cargas de trabajo. Esto puede producirse aunque el cambio se refleje con precisión en el proyecto.

+++

++**Actualización de mantenimiento de Workfront Fusion del 7 de marzo de 2024

**El módulo Workfront Proof > Watch Proof agota el tiempo de espera**

Los escenarios que utilizan el módulo Prueba de Workfront > Ver prueba pueden desactivarse debido al tiempo de espera del módulo Ver prueba.

+++

## Actualizaciones en febrero de 2024

+++**Actualización de mantenimiento del viernes, 29 de febrero de 2024**

### Actualización de mantenimiento del viernes, 29 de febrero de 2024

#### Actualizaciones

**Actualizaciones: La pantalla se queda en blanco al responder a un usuario de otra compañía**

Cuando un usuario intenta responder a un comentario de un usuario de otra compañía, la pantalla se queda en blanco.

Esto se debe a que el usuario no tiene permiso para ver usuarios de otras compañías.

+++

+++**Actualización de mantenimiento del viernes, 22 de febrero de 2024**

### Actualización de mantenimiento del viernes, 22 de febrero de 2024

#### Inicio

**[!UICONTROL Inicio]: el [!UICONTROL espacio de trabajo] y los anclajes no se cargan**

Cuando un usuario inicia sesión, puede ocurrir lo siguiente:

* El nuevo [!UICONTROL Espacio de trabajo de inicio] del usuario no se carga y ven el error “[!UICONTROL No hemos podido cargar la información de su área de trabajo. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo]”.
* Los anclajes del usuario no se cargan y ven el error “[!UICONTROL Los anclajes no están disponibles debido a un error del sistema. Intente actualizar el explorador para solucionar el problema.]”

#### Usuarios

**El administrador del grupo no puede establecer ni cambiar el nivel de acceso de un usuario**

<!--no article-->

Cuando un administrador de grupos intenta cambiar el nivel de acceso de un usuario, puede producirse una de las siguientes situaciones:

* El campo de nivel de acceso está deshabilitado.
* El administrador del grupo no puede elegir un nivel de acceso inferior.

#### Distribuidor de cargas de trabajo

**Etiqueta para horas no laborables**

El distribuidor de cargas de trabajo y el calendario personal de días libres ahora muestran “[!UICONTROL Horas no laborables]” para el tiempo que un usuario se toma libre. Anteriormente, la pantalla mostraba &quot;[!UICONTROL Horas laborables]&quot; para el período no laborable.

+++

+++**Actualización de mantenimiento del viernes, 15 de febrero de 2024**

### Actualización de mantenimiento del viernes, 15 de febrero de 2024

#### Problemas

**Los campos de tiempo guardan un tiempo incorrecto al editar problemas por lotes**

Cuando un usuario edita problemas por lotes, selecciona una fecha y una hora para un campo de fecha y los guarda, la hora que se guarda en este campo del problema no es la hora que el usuario seleccionó. En su lugar, la hora parece convertirse a UTC cuando el usuario lo guarda.

#### Tareas

**Al usuario se le han desasignado una o varias tareas**

Es posible que se quite la asignación automática a un usuario de una tarea a la que está asignado. Esto puede ocurrir en una o más tareas. La anulación de la asignación no se muestra en el área Actualizaciones del sistema de las tareas, pero sí en la sección Actualización de fuentes del menú de configuración.

#### Actualizaciones

**La opción de imagen deshabilitada está disponible al editar un comentario**

Después de que un [!DNL Workfront] administrador ha desactivado la opción para añadir imágenes a los comentarios, esa opción no está disponible al crear un comentario. Sin embargo, si un usuario edita un comentario existente, la opción de imagen está disponible.

+++

+++**Actualización de mantenimiento del viernes, 08 de febrero de 2024**

### Actualización de mantenimiento del 8 de febrero de 2024

#### Tableros

**No se puede mover una tarjeta en una columna usando las opciones [!UICONTROL Mover]**

Cuando un usuario intenta mover una tarjeta en una columna utilizando las opciones “[!UICONTROL Parte superior de la columna]” o “[!UICONTROL Parte inferior de la columna]” en el menú de tres puntos, la tarjeta no se mueve.

**Las tarjetas persisten al cambiar la iteración**

Cuando un usuario está viendo una iteración en un tablero y luego cambia la iteración, las tarjetas que se muestran para la nueva iteración son las tarjetas de una iteración que el usuario estaba viendo anteriormente.

#### Informes

**La columna &quot;Sin valor&quot; no muestra resultados**

Cuando un informe de gráfico tiene una columna &quot;[!DNL No value]&quot;, la columna no muestra datos, aunque estos deban estar presentes.

#### Administración de recursos

**Administración de recursos: cálculos financieros incorrectos debido a problemas de función**

Los cálculos de horas y finanzas pueden ser incorrectos y mostrar un coste de 0 aunque las horas se registren en una función que tenga una tasa de coste.

Esto se debe a que las funciones están creando automáticamente tasas duplicadas sin fechas de inicio o finalización. Como no tienen fechas de inicio o finalización, se tratan como un valor de 0 cuando se ejecutan los cálculos financieros.

+++

+++**Actualización de mantenimiento del viernes, 01 de febrero de 2024**

### Actualización de mantenimiento del 1 de febrero de 2024

#### Inicio de sesión

**Los usuarios que utilizan SSO no son redirigidos a la ubicación original al iniciar sesión**

Cuando un usuario está en una página en [!DNL Workfront] e inicia sesión con SSO, cuando se completa el inicio de sesión, se le dirige a [!UICONTROL Inicio] en lugar de la página en la que se encontraban antes de iniciar sesión.

#### Plantillas

**Error al copiar las plantillas**

Cuando se intenta copiar una plantilla nueva o anterior, la plantilla no se copia y aparece el siguiente mensaje de error:

&quot;[!UICONTROL El ID no puede ser nulo]&quot;

+++

## Actualizaciones en enero de 2024

+++**Actualización de mantenimiento (Hot Fix) el miércoles, 30 de enero de 2024**

### Actualización de mantenimiento (Hot Fix) el 30 de enero de 2024

#### Informes

**El campo API externa no muestra todos los valores disponibles en listas e informes**

Anteriormente, los usuarios podían ver el valor seleccionado (y editar el valor) para un campo de búsqueda externo en listas e informes, pero no veían el menú desplegable con las opciones procedentes de la API.

Ahora, cuando se utiliza un campo personalizado de búsqueda externa en una lista o informe, está disponible la lista desplegable con todas las opciones de la API externa.

+++

+++**Actualización de mantenimiento del viernes, 25 de enero de 2024**

### Actualización de mantenimiento el viernes, 25 de enero de 2024

#### Tableros

**Tableros: las tarjetas no se mueven a la columna adecuada cuando se cambia el estado**

Cuando el estado del objeto vinculado de una tarjeta conectada cambia directamente en el objeto, la tarjeta no se mueve a la columna adecuada. Si se cambia el estado del objeto en la tarjeta o se arrastra la tarjeta a la nueva columna, la tarjeta se comporta según lo esperado.

#### Notificaciones

**el marcado de las notificaciones como vistas no persiste**

Cuando un usuario marca sus notificaciones como vistas y luego navega a una página diferente dentro de [!DNL Workfront], el icono de notificaciones sigue mostrando el número de notificaciones no leídas que existían antes de que el usuario las marcara como vistas, y las notificaciones siguen apareciendo en la lista cuando el usuario hace clic en el icono. Esto continúa si el usuario las marca como vistas y navega a otra página o vuelve a la página original.

#### Actualizaciones

**Problemas con el etiquetado en la experiencia de comentarios heredada**

Cuando se etiqueta a un usuario en un comentario en la experiencia de comentarios heredada, se producen los siguientes problemas:

* En el comentario solo está presente el nombre del usuario
* El nombre del usuario no está marcado con un símbolo @
* El nombre del usuario no es azul
* El nombre del usuario no es un vínculo al perfil de ese usuario

El usuario recibe una notificación por correo electrónico con respecto a la etiqueta, de acuerdo con lo previsto.

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

**Error en la sección [!UICONTROL Comentarios] de las tarjetas**

Cuando un usuario está viendo una tarjeta y se desplaza a la sección [!UICONTROL Comentarios], los comentarios no se muestran y aparece el siguiente error:

&quot;[!UICONTROL Se ha producido un error. Vuelva a intentarlo más tarde.]&quot;

**Problemas al ver el estado de las subtareas**

Se ha informado de los siguientes problemas relacionados con la visualización del estado de las subtareas en una tarjeta en los paneles:

* El estado se muestra como &quot;Seleccionar estado&quot; incluso cuando la tarea ya tiene un estado. Este estado se puede ver al ver la tarea directamente.
* Si el usuario intenta seleccionar un estado, la pantalla se queda en blanco y debe actualizarse.

**“[!UICONTROL No tiene acceso]” al ver comentarios en una tarjeta**

Cuando un usuario intenta ver los comentarios de una tarjeta que no está conectada a un objeto de [!DNL Workfront], verá el siguiente mensaje:

“[!UICONTROL No tiene acceso para ver comentarios sobre este objeto]”

Esto puede ocurrir incluso cuando el usuario podía ver los comentarios en la tarjeta anteriormente.

#### Formularios personalizados

**No se pueden añadir ni quitar de forma masiva formularios personalizados en tareas de la plantilla**

Si un usuario intenta añadir o quitar de forma masiva un formulario personalizado en una tarea de plantilla, el formulario no se añade ni se quita, y el usuario ve el siguiente error:

[!UICONTROL Intentémoslo de nuevo. Parámetro no válido: valor &quot;XXXXXXXXXXXXXXXX&quot; de templateID]

Si el usuario encuentra la plantilla con el GUID especificado e intenta añadir o quitar formularios personalizados en el resto de las tareas de la plantilla, el error volverá a producirse con otro templateID.

Los formularios personalizados se pueden añadir o quitar en una sola tarea de plantilla. Este error solo se aplica a la adición o eliminación masiva.

#### Portafolios

**La terminología personalizada no se aplica a la página de grupo**

Cuando un usuario establece terminología personalizada en el nivel de portafolio, la terminología no se aplica a la página de nivel de grupo.

#### Configurar

**No se pueden ocultar los estados opcionales**

Cuando se intentan ocultar estados opcionales en un sistema y nivel de grupo, el estado no se oculta. Si el usuario ve el estado, la opción para ocultarlo no está habilitada, aunque el usuario sí la haya habilitado y haya guardado los cambios.

**Faltan los estados de problemas predeterminados en algunos tipos de problemas en la Configuración**

Cuando un usuario está viendo los estados de los problemas en la Configuración, ve que faltan los estados predeterminados para los problemas (Nuevo, En curso y Completado) en algunos tipos de problemas. Los estados predeterminados no tienen la opción de cambiar el tipo de problema, por lo que el usuario no puede volver a configurar los estados para mostrar para los tipos de problema afectados.

#### Equipos

**Problemas al configurar los estados de equipo para el botón [!UICONTROL Listo]**

Se han notificado los siguientes problemas relacionados con los estados del botón [!UICONTROL Listo] al editar o crear un equipo:

* Es posible que falten algunos estados en el área del botón Listo de la ventana [!UICONTROL Nuevo equipo] o en el área [!UICONTROL Configuración del equipo] de un equipo existente.
* Si el usuario intenta guardar el equipo, es posible que aparezca el error “Debe seleccionar al menos un estado en cada categoría”.

#### Plantillas

**Error al adjuntar plantilla a proyecto**

Cuando un usuario intenta adjuntar una plantilla a un proyecto, recibe el siguiente error:

“¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo”.

Esto ocurre cuando el usuario no tiene permiso de visualización en un formulario personalizado adjunto a la plantilla.

#### Actualizaciones

**Los comentarios no se transfieren entre la experiencia anterior y la nueva**

Es posible que un comentario realizado en la experiencia de comentarios anterior no sea visible en la nueva experiencia de comentarios. También puede ocurrir lo contrario.

+++

+++**Actualización de mantenimiento del viernes, 11 de enero de 2024**

### Actualización de mantenimiento el viernes, 11 de enero de 2024

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
