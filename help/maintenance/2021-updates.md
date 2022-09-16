---
title: Actualizaciones de mantenimiento de Workfront para 2021
description: Historial de actualizaciones de mantenimiento de 2021 para [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
source-git-commit: 7fa90198186a7b0f392683d432a7da0424943da2
workflow-type: tm+mt
source-wordcount: '10019'
ht-degree: 3%

---

# 2021 [!DNL Workfront] Actualizaciones de mantenimiento

En 2021 se realizaron las siguientes actualizaciones de mantenimiento:

## Actualizaciones en diciembre de 2021

+++**Actualización de mantenimiento el 23 de diciembre de 2021**

**Nuevas tareas predeterminadas a una restricción de tareas incorrecta**

_Tareas_

Cuando un usuario crea una nueva tarea utilizando el[!UICONTROL Nueva tarea]&quot; y el [!UICONTROL Nuevo inicio predeterminado de tarea] La opción Fecha está configurada en &quot;[!UICONTROL Hoy],&quot; la restricción de tareas de la tarea creada se establece en &quot;[!UICONTROL Lo antes posible]&quot; en lugar de &quot;[!UICONTROL Iniciar no antes de].&quot; Esto también puede ocurrir al usar plantillas de proyecto.

**Abrir programación en [!UICONTROL Grupos] El área conduce a una página en blanco**

_Configurar_

Cuando un usuario está viendo grupos en la variable [!UICONTROL Configuración] e intenta abrir, editar o copiar una programación, la programación no se abre y el usuario ve una página en blanco.

**Los cambios no se muestran al reordenar la navegación izquierda**

_Exploración_

Cuando un usuario intenta reordenar el panel de navegación izquierdo arrastrando un elemento, éste vuelve a aparecer en su lugar anterior cuando el usuario lo suelta. Si el usuario actualiza la página, el panel izquierdo muestra el nuevo pedido.

**El vínculo para enviar un documento solicitado lleva a una página en blanco.**

_Documentos_

Cuando un usuario recibe una solicitud para enviar un documento y hace clic en el vínculo al objeto en el que se solicitó el documento, el vínculo lleva a una página en blanco. Esto puede ocurrir al hacer clic en un vínculo de un correo electrónico o en una notificación interna de la aplicación.

**[!UICONTROL Equilibrador de carga de trabajo] muestra 0 horas asignadas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario está viendo la variable [!UICONTROL Equilibrador de carga de trabajo] y tiene el &quot;[!UICONTROL Mostrar fechas proyectadas]&quot; activado, cualquier fecha del futuro mostrará 0 horas asignadas.

**Las pruebas desaparecen de forma intermitente de las carpetas**

_[!DNL Workfront Proof]_

Cuando un usuario que ha iniciado sesión [!DNL Workfront Proof] visualiza una carpeta, la carpeta aparece vacía. Si el usuario vuelve a realizar la comprobación más tarde, las pruebas son visibles.

+++

+++**Actualización de mantenimiento el 16 de diciembre de 2021**

**Al hacer clic en el anuncio en la lista de notificaciones, se abre una página en blanco**

_Notificaciones_

Cuando un usuario abre su lista de notificaciones desde el [!UICONTROL Notificaciones] , luego hace clic en un anuncio, se les redirige a una página en blanco y el anuncio no se muestra.

**El panel Resumen muestra &quot;[!UICONTROL Sin selección]&quot; cuando la tarea está seleccionada**

_Tareas_

Cuando un usuario abre un resumen del documento en la [!UICONTROL Documentos] de un proyecto, luego va a la lista de tareas, selecciona una tarea e intenta abrir el resumen de la tarea, no se muestra el resumen de la tarea y el usuario ve el siguiente mensaje:

[!UICONTROL No hay selección. Seleccione un documento de la lista para ver detalles.]

El mensaje menciona documentos aunque el usuario esté en la lista de tareas.

**[!UICONTROL Trabajo no asignado] no se carga**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario de la variable [!UICONTROL Equilibrador de carga de trabajo] crea un filtro utilizando la variable [!UICONTROL Asignación:ID de función] , el campo [!UICONTROL Trabajo no asignado] no se carga.

**Adjuntar plantilla con &quot;[!UICONTROL Personalizar y adjuntar]&quot; borra los valores de campo personalizados**

_Proyectos_

Si un usuario adjunta una plantilla a un proyecto mediante la opción[!UICONTROL Personalizar y adjuntar]&quot;, y el proyecto ya tiene un formulario personalizado adjunto, los valores de los campos personalizados no se transfieren y deben volver a introducirse manualmente. Esto ocurre incluso cuando la plantilla incluye el mismo formulario personalizado.

+++

+++**Actualización de mantenimiento (corrección) el 10 de diciembre de 2021**

**[!UICONTROL Whoops] error al adjuntar la plantilla al proyecto existente**

_Proyectos_

Cuando un usuario intenta adjuntar una plantilla a un proyecto existente, la plantilla no se adjunta y el usuario ve el siguiente error:

&quot;[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

+++

+++**Actualización de mantenimiento el 9 de diciembre de 2021**


**El panel de navegación izquierdo contraído se expande al cargar la página**

_Exploración_

Cuando un usuario ha configurado la navegación izquierda para que se contrae y, a continuación, ha actualizado una página, la navegación izquierda se expande en la página recargada. La navegación de la izquierda también se expande si el usuario abre una página en una pestaña nueva.

**[!UICONTROL Equilibrador de carga de trabajo] muestra 0 horas asignadas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario está viendo la variable [!UICONTROL Equilibrador de carga de trabajo] y tiene el &quot;[!UICONTROL Mostrar fechas proyectadas]&quot; activado, cualquier fecha del futuro mostrará 0 horas asignadas.

+++

+++**Actualización de mantenimiento el 8 de diciembre de 2021**

**La aprobación se restablece cuando se realiza una actualización**

_Rutas de aprobación_

Si un usuario decide sobre una aprobación mediante el encabezado del objeto y luego realiza inmediatamente una actualización del objeto, los iconos de aprobación vuelven a aparecer en el encabezado y la decisión de aprobación no se guarda.

**[!UICONTROL No se puede editar en línea una asignación en un informe]**

_Informes_

Cuando un usuario intenta editar una asignación en línea en un informe, el valor del campo no cambia y la edición no se guarda.


+++

+++**Actualización de mantenimiento el 2 de diciembre de 2021**

**Se agregó una barra diagonal al escribir la URL manualmente**

_Solicitudes_

Cuando un usuario rellena una solicitud y empieza a escribir manualmente en una dirección URL, se añade una barra diagonal adicional en algún momento cerca del principio de la dirección URL. El usuario no puede eliminar la barra diagonal.

**Las secciones personalizadas no se pueden quitar del panel de navegación izquierdo**

_Exploración_

Cuando un usuario intenta quitar una sección personalizada del panel de navegación izquierdo haciendo clic en la X situada junto a la sección, la sección no se elimina.

**Trabajo no asignado no se carga**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario de la variable [!UICONTROL Equilibrador de carga de trabajo] crea un filtro utilizando la variable [!UICONTROL Asignación:ID de función] , el campo [!UICONTROL Trabajo no asignado] no se carga.

**Páginas que no se cargan en determinados navegadores**

_[!DNL Workfront]_

Cuando un usuario está trabajando en [!DNL Workfront], las páginas no se cargan y el usuario ve el siguiente mensaje de error:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

Esto se ha notificado en

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Este error se produce de forma aleatoria y puede afectar a cualquier área de [!DNL Workfront].

+++


## Actualizaciones en noviembre de 2021

+++**Actualización de mantenimiento el 18 de noviembre de 2021**

**[!DNL Workfront]para [!DNL Jira] &quot;[!UICONTROL clientID o clientSecret no válidos]&quot; error al iniciar sesión**

_Integraciones de Workfront_

Los usuarios han cerrado la sesión de [!DNL Jira] para la integración de Workfront. Cuando un usuario intenta iniciar sesión en la [!DNL Workfront for Jira] no pueden iniciar sesión y ven el siguiente error:

&quot;[!UICONTROL clientID o clientSecret no válidos]&quot;

**El formulario personalizado adjunto a la solicitud no se actualiza cuando se selecciona un nuevo tema de cola**

_Solicitudes_

Cuando un usuario crea una solicitud y selecciona un tema de cola que adjunta automáticamente un formulario personalizado a la solicitud y selecciona otro tema de cola, el formulario personalizado del primer tema de cola permanece adjunto a la solicitud.

**Los iconos se muestran incorrectamente**

_[!DNL Workfront]_

Las imágenes de iconos se muestran incorrectamente. Esto se ha informado en muchas zonas de [!UICONTROL Workfront].

**Las tareas no se exportan al PDF cuando se selecciona la opción &quot;Otros tamaños&quot;.**

_Tareas_

Si un usuario intenta exportar una lista de tareas al PDF y selecciona el[!UICONTROL Otros tamaños]&quot;, pueden seleccionar un tamaño y hacer clic en [!UICONTROL Exportar], pero la lista no exporta. No hay ningún mensaje de error ni ninguna otra indicación de que la exportación no se haya realizado correctamente.

**El indicador de imagen no se muestra en las notificaciones por correo electrónico**

_Notificaciones_

Cuando un usuario agrega una imagen a una actualización y envía una notificación por correo electrónico al destinatario de la actualización, el correo electrónico no incluye un indicador de que haya una imagen en la actualización.

**Páginas que no se cargan en determinados navegadores**

_[!DNL Workfront]_

Cuando un usuario está trabajando en [!DNL Workfront], las páginas no se cargan y el usuario ve el siguiente mensaje de error:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

Esto se ha notificado en

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Este error se produce de forma aleatoria y puede afectar a cualquier área de Workfront.

+++

+++**Actualización de mantenimiento el 11 de noviembre de 2021**

**Problema con las integraciones de documentos, página en blanco en la ventana emergente de carga de documentos desde[!DNL Google Drive*]*

_Documentos_

Cuando un usuario intenta agregar un nuevo documento a [!DNL Workfront] from [!DNL Google Drive] mediante [!UICONTROL Agregar nuevo] >[!UICONTROL De [!DNL Google Drive]], la pantalla emergente de carga permanece en blanco.

**No se puede usar más de un filtro en el equilibrador de carga de trabajo**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta utilizar más de un filtro en la variable [!UICONTROL Equilibrador de carga de trabajo], verán los siguientes problemas:

* Si el usuario selecciona dos filtros, solo se aplica el filtro inferior.
* Si el usuario selecciona más de dos filtros, no se muestran resultados.

**&quot;[!UICONTROL Carpetas de proyecto]&quot; no se encuentra el encabezado del documento en el área de documentos del proyecto**

_Proyectos_

Cuando un usuario está en un proyecto y ve los documentos del mismo, aparece el encabezado &quot;[!UICONTROL Carpetas de proyecto]&quot; falta en la navegación izquierda. La flecha desplegable sigue ahí y el usuario puede seleccionar una carpeta.

**Las columnas de la placa Kanban son demasiado anchas y no se pueden ajustar**

_Agile_

Cuando un usuario ve un tablero kanban con varias columnas, las columnas son demasiado anchas y el usuario debe desplazarse para ver o mover las tarjetas a las columnas que se encuentran más a la derecha. Los anchos de columna no se pueden ajustar, por lo que el usuario no puede reducir el tamaño de las columnas para que todas estén visibles en la pantalla al mismo tiempo.

**Interfaz mejorada para crear un nuevo equipo**

_Equipos_

La creación de equipos es ahora más intuitiva con nuevas indicaciones visuales. Al seleccionar la variable [!UICONTROL Cambiar equipos] en cualquier página de equipo, la variable [!UICONTROL Crear nuevo equipo] tiene un icono para indicar &quot;[!UICONTROL new],&quot; y el vínculo está separado del resto de la lista, por lo que no parece un nombre de equipo. Esta interfaz es la misma para equipos ágiles y no ágiles.

+++

+++**Actualización de mantenimiento el 4 de noviembre de 2021**

**Nuevas tareas predeterminadas a una restricción de tareas incorrecta**

_Tareas_

Cuando un usuario crea una nueva tarea utilizando el[!UICONTROL Nueva tarea]&quot; y la opción Nueva fecha de inicio predeterminada de tarea está establecida en &quot;[!UICONTROL Hoy],&quot; la restricción de tareas de la tarea creada se establece en &quot;[!UICONTROL Lo antes posible]&quot; en lugar de &quot;[!UICONTROL Iniciar no antes de].&quot;

**Los campos no se muestran en las tarjetas de artículo Agile**

_Águila_

Cuando un usuario ve un guión gráfico Agile, las tarjetas solo muestran el [!UICONTROL Descripción] y [!UICONTROL Estado] campos. No se muestra ningún otro campo, incluidos los campos personalizados.

**Las tarjetas vuelven a la columna original antes de pasar a la nueva columna**

_Águila_

Cuando un usuario arrastra una tarjeta a una nueva columna del guión gráfico, puede ver la tarjeta que se está arrastrando. Sin embargo, cuando el usuario suelta la tarjeta en la nueva columna, la tarjeta aparece brevemente en la columna original antes de mostrarse en la nueva columna.

**Valores no disponibles para campos personalizados en filtro**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta crear un filtro utilizando un campo personalizado, el valor de ese campo personalizado no se muestra y no se puede introducir en el filtro.

**Páginas que no se cargan en [!DNL Firefox] explorador**

_[!DNL Workfront]_

Cuando un usuario está trabajando en [!DNL Workfront] usando un [!DNL Firefox] explorador, las páginas no se cargan y el usuario ve el siguiente mensaje de error:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

Este error se produce de forma aleatoria y puede afectar a cualquier área de [!DNL Workfront].

**Error relacionado con la fecha al crear un proyecto a partir de una plantilla.**

_Plantillas_

Si un usuario crea un proyecto a partir de una plantilla y establece el modo de programación como [!UICONTROL Fecha de inicio], luego selecciona una restricción de tarea, cuando el usuario intenta crear el proyecto, el proyecto no se crea y el usuario ve un mensaje de error basado en la restricción de tarea.

**[!UICONTROL Exportar diagrama de Gantt] el cuadro de diálogo no responde**

_Gráfico Gantt_

Si un usuario se encuentra en la nueva [!DNL Workfront] intentos de exportación de [!UICONTROL Diagrama de Gantt] y selecciona el[!UICONTROL Qué veo]&quot;, la opción [!UICONTROL Diagrama de Gantt] no exporta y el cuadro de diálogo no responde. El usuario no puede cerrar ni hacer clic fuera del cuadro de diálogo.

**Los iconos se muestran incorrectamente**

_[!DNL Workfront]_

Las imágenes de iconos se muestran incorrectamente. Esto se ha notificado en situaciones que incluyen, entre otras:

* Imágenes para roles o grupos de trabajo al compartir un objeto
* Iconos izquierdo y derecho en informes de calendario
* Ordenar iconos en columnas de informes

**Agregue casillas de verificación a Solicitudes en el [!UICONTROL Enviado] de la sección [!UICONTROL Solicitudes] area**

_Solicitudes_

Hemos agregado casillas de verificación a la izquierda de los nombres de solicitud en la sección [!UICONTROL Lista enviada] del [!UICONTROL Solicitudes] . Esto facilita la selección de una solicitud y la visualización de información adicional.

**Los trimestres personalizados ahora son compatibles con los filtros del equilibrador de carga de trabajo**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Los filtros de la variable [!UICONTROL Equilibrador de carga de trabajo] ahora admiten trimestres personalizados.

**Se ha actualizado el operador de filtro para el campo Duración de los filtros del equilibrador de carga de trabajo**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Hemos actualizado los operadores de filtro al filtrar la variable[!UICONTROL  Equilibrador de carga de trabajo] áreas por [!UICONTROL Duración].

+++


## Actualizaciones de octubre de 2021

+++**Actualización de mantenimiento el 28 de octubre de 2021**

**[!UICONTROL Página principal] y [!UICONTROL Mi trabajo] mostrar página en blanco**

_[!UICONTROL Página principal] / [!UICONTROL Mi trabajo]_

Cuando un usuario navega a [!UICONTROL Página principal] Para Mi trabajo, la página se muestra en blanco.

**No se puede ver ni editar [!UICONTROL Grupo de temas] detalles**

_Solicitudes_

Cuando un usuario intenta ver o editar los detalles de un grupo de temas, la página que se abre muestra &quot;[!UICONTROL Detalle del grupo de temas]&quot; en el encabezado, pero en cualquier otro caso está en blanco

**Los botones de radio obligatorios en blanco se rellenan automáticamente**

_Solicitudes_

Cuando un usuario envía una solicitud con un campo de botón de opción requerido y el usuario no ha seleccionado un valor para ese campo antes de enviar la solicitud, el primer valor se selecciona automáticamente cuando se envía la solicitud.

+++

+++**Actualización de mantenimiento el 21 de octubre de 2021**

**No se puede agregar un filtro en [!UICONTROL Equilibrador de carga de trabajo]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario de la variable [!UICONTROL Equilibrador de carga de trabajo] intenta agregar un filtro, la variable [!UICONTROL Añadir filtro] se abre el panel, pero el contenido del panel no se carga y el usuario no puede agregar el filtro.

**El tablero Agile Scrum no muestra historias**

_Águila_

Cuando un usuario intenta ver el panel Anular en la iteración de un equipo, el panel de control se muestra en blanco.

**El tablero de artículo de Anulación está en blanco al usar filtros**

_Águila_

Cuando un usuario intenta ver un tablero de artículos de Anulación utilizando cualquier filtro que no sea &quot;[!UICONTROL Todo el equipo]&quot;, aparece una pantalla en blanco. El usuario no puede volver a cambiar al &quot;[!UICONTROL Todo el equipo]&quot;.

**Las listas solo están visibles en un área pequeña de la pantalla**

_Listas_

Cuando un usuario intenta ver una lista mientras utiliza un [!DNL Safari] explorador en un [!DNL Mac] usando la variable [!DNL Big Sur OS], la lista solo aparece en un área pequeña de la pantalla. El usuario puede desplazarse por la lista, pero el área puede ser tan pequeña que la lista sea difícil o imposible de leer.

**Los botones de radio obligatorios en blanco se rellenan automáticamente**

_Solicitudes_

Cuando un usuario envía una solicitud con un campo de botón de opción requerido y el usuario no ha seleccionado un valor para ese campo antes de enviar la solicitud, el primer valor se selecciona automáticamente cuando se envía la solicitud.

+++

+++**Actualización de mantenimiento (corrección) el 21 de octubre de 2021**

**[!UICONTROL Página principal] y [!UICONTROL Mi trabajo] mostrar página en blanco**

_[!UICONTROL Página principal] / [!UICONTROL Mi trabajo]_

Cuando un usuario navega a [!UICONTROL Página principal] o [!UICONTROL Mi trabajo], la página se muestra en blanco.

+++

+++**Actualización de mantenimiento el 20 de octubre de 2021**

**[!UICONTROL Equilibrador de carga de trabajo] establecer como opción de programación predeterminada**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Si un usuario que tiene la variable [!UICONTROL Planificador] definido como predeterminado va a usarlo, verán que la variable [!UICONTROL Equilibrador de carga de trabajo] se ha establecido como predeterminado.

+++

+++**Actualización de mantenimiento (corrección) el 19 de octubre de 2021**

**No se puede asignar una solicitud al crearla**

_Solicitudes_

Cuando un usuario está en el nuevo [!DNL Workfront] experience está creando una solicitud e intenta asignar un usuario escribiendo su nombre en el [!UICONTROL Asignaciones] , el campo no muestra la lista desplegable y el usuario no puede seleccionar el nombre del usuario asignado.

**El tablero de artículo de Anulación está en blanco al usar filtros**

_Águila_

Cuando un usuario intenta ver un tablero de artículos de Anulación utilizando cualquier filtro que no sea &quot;[!UICONTROL Todo el equipo]&quot;, aparece una pantalla en blanco. El usuario no puede volver a cambiar al &quot;[!UICONTROL Todo el equipo]&quot;.

+++

+++**Actualización de mantenimiento el 14 de octubre de 2021**

**Las plantillas compartidas en todo el sistema no son visibles**

_Plantillas_

Cuando un usuario está creando un proyecto e intenta utilizar una plantilla que se ha compartido en todo el sistema, el usuario no puede ver la plantilla en la lista de plantillas disponibles y no puede utilizarla.

**Error al crear proyectos a partir de plantillas**

_Plantillas_

Cuando un usuario intenta crear un proyecto a partir de una plantilla que incluya un formulario personalizado con una sección visible únicamente para los administradores, el usuario no puede crear el proyecto y se muestra el siguiente mensaje:

&quot;[!UICONTROL No se encuentra la categoría con el valor de clave principal &quot;xxxxxxxxxxxxxxx&quot;]&quot;

**Vínculos actualizados para copiar y mover tareas**

_Tareas_

Los vínculos para copiar y mover tareas se han actualizado a &quot;[!UICONTROL Copiar en]&quot; y &quot;[!UICONTROL Mover a]&quot; tanto en la página de tareas como en una lista de tareas.

**Eliminar el límite de la búsqueda de funciones de trabajo al anular las tasas de facturación de un proyecto**

Roles

NOTA: Esta actualización se encuentra actualmente en el entorno de vista previa y estará en producción con la versión de producción 2.1. Para obtener más información, consulte &quot;Información general sobre la versión 22.1&quot;.

Al anular las tasas de facturación de las funciones de trabajo en un proyecto ahora se buscan todas las funciones de trabajo en el sistema.

Anteriormente, [!DNL Workfront] se buscaron roles de trabajo en las primeras 2000 funciones en orden alfabético.

+++

+++**Actualización de mantenimiento el 7 de octubre de 2021**

**[!UICONTROL Las notificaciones en la aplicación desaparecen de] centro de notificaciones**

_Notificaciones_

Cuando un usuario ve el centro de notificaciones, algunas notificaciones visibles anteriormente ya no están visibles. En algunos casos, la notificación puede desaparecer antes de que el usuario la vea.

**Los anuncios no están visibles en la [!UICONTROL Todos los anuncios] página**

_Notificaciones_

Cuando un usuario abre el [!UICONTROL Todos los anuncios] desde la página [!UICONTROL Notificaciones] no hay anuncios visibles en las siguientes áreas:

* [!UICONTROL Bandeja de entrada]
* [!UICONTROL Favoritos]
* [!UICONTROL Borradores]
* [!UICONTROL Eliminado]

**Error al realizar la asignación en el [!UICONTROL Equilibrador de carga de trabajo]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta realizar una asignación desde el [!UICONTROL Equilibrador de carga de trabajo], el trabajo no se asigna y el usuario ve el siguiente error:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

+++


## Actualizaciones de septiembre de 2021

+++**Actualización de mantenimiento el 30 de septiembre de 2021**

**Error al navegar rápidamente hasta o desde [!UICONTROL Página principal]**

_Página de inicio_

Cuando un usuario navega rápidamente a o desde [!UICONTROL Página principal], la página no se carga y el usuario ve el siguiente error:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

Esto también puede ocurrir al navegar a [!UICONTROL Página principal] mediante un pin.

+++

+++**Actualización de mantenimiento el 23 de septiembre de 2021**

**[!UICONTROL Acceso denegado] error al ver los tickets enviados a[!DNL Workfront]**

_Problemas_

Cuando un usuario ha enviado un ticket a [!DNL Workfront] e intenta ver el ticket, ven el siguiente error:

&quot;[!UICONTROL Acceso denegado: ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

**El resumen de casos empresariales muestra valores incorrectos**

_Proyectos_

Cuando un usuario ve la variable [!UICONTROL Caso empresarial] resumen, los valores mostrados no reflejan los valores del [!UICONTROL Caso empresarial] secciones.

**Los encabezados de columna no se alinean con las columnas de las listas**

_Configurar_

Cuando un usuario está en la variable [!UICONTROL Configuración] y visualiza una lista, como [!UICONTROL Forms personalizado] o [!UICONTROL Niveles de acceso], los encabezados de columna de esa lista no se alinean con las columnas de la lista.

**Los usuarios que no tengan los permisos adecuados para compartir pueden adjuntar formularios personalizados a los objetos**

_Formularios personalizados_

Cuando un formulario personalizado en el nuevo [!DNL Adobe Workfront] experiencia está definida para ser visible en todo el sistema, todos los usuarios pueden adjuntar este formulario personalizado a un objeto. Sin embargo, solo deben poder ver el formulario personalizado y no pueden adjuntarlo a un objeto a menos que se haya compartido específicamente con ellos.

+++

+++**Actualización de mantenimiento el 16 de septiembre de 2021**

**No se pueden editar grupos**

_Grupos_

Cuando un usuario intenta editar o eliminar un grupo, el grupo no se edita ni elimina y el usuario ve el siguiente mensaje:

&quot;[!UICONTROL Intentemos de nuevo. No se encuentra el grupo con valores de clave principal &quot;(ID del grupo)&quot;]&quot;

**[!UICONTROL Optimizador de Portfolio] no mostrar proyectos**

_Portafolios_

Cuando un usuario intenta ver proyectos en la [!UICONTROL Optimizador de Portfolio], la lista de proyectos no se muestra y, por lo tanto, el usuario no puede interactuar con los proyectos.

+++

+++**Actualización de mantenimiento (corrección) el 10 de septiembre de 2021**

**Fecha y hora marcadas como UTC al editar en línea**

_Listas_

Cuando un usuario edita una fecha u hora en línea (en una lista de objetos), la fecha y la hora se marcan como UTC. La fecha y la hora no están establecidas en UTC en [!DNL Workfront]. Este problema afecta únicamente a la visualización, no a los datos reales.

**El color del texto no se muestra correctamente cuando se aplica formato condicional**

_Informes_

Cuando un usuario ve un informe con formato condicional que altera el color del texto, el color del texto se muestra como sin modificar.

+++

+++**Actualización de mantenimiento el 9 de septiembre de 2021**

**Los problemas no muestran los detalles del problema**

_Página de inicio_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] la experiencia selecciona un problema de [!UICONTROL Lista de trabajo], la vista previa en el panel derecho muestra ciertos campos como si no se hubieran introducido valores. Sin embargo, si va al problema y ve la [!UICONTROL Detalles del problema], estos campos tienen valores introducidos.

**Los usuarios necesitan permisos de Contribute para ver la variable [!UICONTROL Aprobaciones] en la nueva experiencia de Workfront**

_Rutas de aprobación_

Los usuarios necesitan [!UICONTROL Contribute] permisos en un objeto para ver el [!UICONTROL Aprobaciones] en la sección [!DNL Workfront] Experiencia. Solo deberían necesitar [!UICONTROL Ver] permisos para ver [!UICONTROL Aprobaciones] cuando haya un proceso de aprobación en el objeto.

**[!UICONTROL Whoops] error al usar filtros**

_Listas_

Cuando un usuario intenta utilizar uno de los filtros siguientes:

* [!UICONTROL Todos los proyectos]
* [!UICONTROL Proyectos en los que participo]
* [!UICONTROL Mis tareas actuales]

la lista se queda en blanco y el usuario ve el siguiente error:

&quot;[!UICONTROL Intentemos de nuevo.]&quot;

**[!UICONTROL Tareas] se deja en blanco al editar en línea**

_Plantillas_

Cuando un usuario intenta insertar tareas de edición en una plantilla mediante una vista que incluye el[!UICONTROL Asignar a: Nombre]&quot; y la asignación contiene un usuario, la variable [!UICONTROL Tareas] se deja en blanco y el usuario no puede editar las tareas de la plantilla.

**No se puede exportar [!UICONTROL Optimizador de Portfolio]**

_Portafolios_

Cuando un usuario intenta exportar la variable [!UICONTROL Optimizador de Portfolio] y hace clic en cualquiera de las opciones de exportación, la variable [!UICONTROL Optimizador de Portfolio] no exporta.

**Las notificaciones no se envían para las respuestas**

_Notificaciones_

Cuando un usuario responde a una actualización en [!DNL Workfront], otros usuarios del hilo de comentarios no reciben notificaciones.

**Los cambios en los datos personalizados provocan un retraso**

_Campos personalizados_

Cuando un usuario modifica los datos personalizados que déclencheur a cambios en otros datos mostrados, los cambios se cargan lentamente.

**Agrupación[!UICONTROL Contraer o Expandir todo]&quot; no se muestra**

_Informes_

La variable[!UICONTROL Contraer o Expandir todo]&quot; no se muestra en el encabezado de una lista o informe cuando se aplican agrupaciones a la lista o al informe.

**[!UICONTROL Marque] y [!UICONTROL Cancelar] opciones no visibles al cambiar asignaciones de tareas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta cambiar la asignación de tareas para una tarea y el lapso de tiempo de esa tarea se extiende hasta el borde de la página visible o más allá de él, la variable [!UICONTROL Marque] y [!UICONTROL Cancelar] Los botones no están visibles y el usuario no puede guardar ni cancelar los cambios de asignación.

**Adición de un campo personalizado a [!UICONTROL Página principal] causa que falten datos de campo**

_[!UICONTROL Página de inicio]_

Cuando se agrega un campo personalizado a [!UICONTROL Página principal], otros campos empiezan a faltar datos y a mostrarse incorrectamente.

**No se pueden ver los elementos vinculados al iniciar sesión como otro usuario**

_Integraciones_

Si un administrador intentaba ver elementos vinculados desde un proveedor externo mientras iniciaba sesión como otro usuario, no podía abrir las carpetas vinculadas y no podía ver los elementos.

+++

+++**Actualización de mantenimiento el 2 de septiembre de 2021**

**No se puede anclar el tablero personalizado**

_Paneles_

Cuando un usuario intenta anclar un tablero personalizado, el tablero no fija y el usuario ve el siguiente error:

&quot;[!UICONTROL Algo salió mal mientras sonaba. Póngase en contacto con [!DNL Workfront] así que podemos arreglar esto.]&quot;

**[!DNL Workfront Proof]resumen de impresión está en blanco**

[!DNL Workfront Proof]

Cuando un usuario abre el resumen de impresión para imprimir una prueba, aparece el encabezado, pero el resumen en sí está en blanco.

+++


## Actualizaciones en agosto de 2021

+++**Actualización de mantenimiento el 26 de agosto de 2021**

**En [!DNL Safari] hay un fondo gris oscuro en el texto de los encabezados de columna**

_Listas_

En el [!DNL Safari] navegador, hay un fondo gris oscuro en los encabezados de columna, resaltando el texto. Este no es un problema con ningún otro navegador compatible.

**Error inesperado al configurar predecesores**

_Tareas_

Cuando un usuario intenta establecer una tarea como predecesor mediante la edición en línea, el predecesor no se establece y el usuario ve el siguiente mensaje:

&quot;[!UICONTROL Se produjo un error inesperado]&quot;

+++

+++**Actualización de mantenimiento el 19 de agosto de 2021**

**Faltan filtros guardados después de seleccionar un filtro que no muestra problemas**

_Listas_

Los filtros guardados no aparecen en una lista de problemas después de seleccionar un filtro que no muestre ningún resultado.

**Los problemas no muestran los detalles del problema**

_[!UICONTROL Página principal] resumen_

Cuando un usuario [!DNL Adobe Workfront Classic] selecciona un problema de la variable [!UICONTROL Lista de trabajo], la vista previa en el panel derecho muestra ciertos campos como si no se hubieran introducido valores. Sin embargo, si va al problema y ve la [!UICONTROL Detalles del problema], estos campos tienen valores introducidos.

+++

+++**Actualización de mantenimiento el 12 de agosto de 2021**

**No se puede personalizar la vista ágil en el proyecto**

_Águila_

Cuando un usuario intenta personalizar una vista ágil existente anteriormente en un proyecto, la ventana se cierra y el usuario no puede editar la vista.

**El nombre no cambia en las versiones de documentos nuevos**

_Documentos_

Cuando un usuario carga una nueva versión de un documento, el nombre del documento no se actualiza para que coincida con el nombre de la versión más reciente.

**El icono del predecesor no se vuelve verde cuando se completa el predecesor.**

_Tareas_

Cuando una tarea tiene una tarea predecesora y esta tarea predecesora ha finalizado, el icono predecesor de la tarea dependiente no se vuelve verde.

Cuando un formulario personalizado en el nuevo [!DNL Adobe Workfront] experiencia está definida para ser visible en todo el sistema, todos los usuarios pueden adjuntar este formulario personalizado a un objeto. Sin embargo, solo deben poder ver el formulario personalizado y no pueden adjuntarlo a un objeto a menos que se haya compartido específicamente con ellos.

+++

+++**Actualización de mantenimiento (corrección) el 6 de agosto de 2021**

**No se pueden seleccionar calendarios en [!DNL Outloo]k Configuración del calendario**

_Página de inicio_

Cuando un usuario está en el nuevo [!DNL Workfront] la experiencia está viendo su [!DNL Outlook] Calendario en casa, y abre la configuración, faltan las casillas de verificación para seleccionar calendarios. Si el usuario hace clic en la casilla de verificación, el calendario responde como si la casilla estuviera allí.

**No se puede volver a autorizar o verificar la conexión con [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] usuarios con escenarios conectados a [!UICONTROL Webdam] debe tener en cuenta que [!UICONTROL Webdam] las conexiones requieren una reautenticación manual cada 14 días. La variable [!UICONTROL Webdam] Actualmente, la API no admite la reautorización automática.

+++

+++**Actualización de mantenimiento el 5 de agosto de 2021**

**No se puede interactuar con el documento en [!UICONTROL Panel de resumen] o [!UICONTROL Más] menú**

_Documentos_

Cuando un usuario está en el nuevo [!DNL Workfront] experience está viendo un documento e intenta realizar una selección en la [!UICONTROL Panel de resumen] o [!UICONTROL Más] , el documento no está seleccionado, lo que provoca que el [!UICONTROL Panel de resumen] o [!UICONTROL Más] para que aparezca en blanco.

**[!UICONTROL Nueva solicitud] botón falta**

_Solicitudes_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] la experiencia va a [!UICONTROL Solicitudes] página, la variable [!UICONTROL Nueva solicitud] no se muestra y no pueden enviar una solicitud.

**Los usuarios que no tengan los permisos adecuados para compartir pueden adjuntar formularios personalizados a los objetos**

_Formularios personalizados_

Cuando un formulario personalizado en el nuevo [!DNL Adobe Workfront] experiencia está definida para ser visible en todo el sistema, todos los usuarios pueden adjuntar este formulario personalizado a un objeto. Sin embargo, solo deben poder ver el formulario personalizado y no pueden adjuntarlo a un objeto a menos que se haya compartido específicamente con ellos.

**No se puede cambiar la configuración de prueba al crear una prueba nueva**

_[!DNL Workfront Proof]_

Cuando un usuario crea una nueva prueba e intenta cambiar la configuración, la configuración vuelve a ser una configuración anterior.

**[!UICONTROL Tablero de historias] no se cargó correctamente**

_Águila_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience navega a un [!UICONTROL Tablero de historias], puede tardar hasta 10 segundos en cargar el tablero. El retraso en la carga se debe a que el sistema carga todas las tarjetas cuando sólo debería cargar 50 tarjetas a la vez.

+++


## Actualizaciones en julio de 2021

+++**Actualización de mantenimiento (corrección) el 29 de julio de 2021**

**No se puede cargar la nueva prueba o la nueva versión de prueba**

_[!DNL Workfront Proof]_

Cuando un usuario intenta cargar una prueba nueva o una versión nueva de una prueba en el [!DNL Workfront] experiencia, la nueva prueba o página de versión nueva está en blanco y el usuario no puede cargar la prueba o la versión.

+++

+++**Actualización de mantenimiento del 29 de julio de 2021**

**[!UICONTROL Actividad de prueba] y [!UICONTROL Configuración del visor de pruebas] páginas siempre disponibles**

_[!DNL Workfront Proof]_

La variable [!UICONTROL Actividad de prueba] y [!UICONTROL Visor de pruebas] Las páginas de configuración ahora siempre están visibles, incluso si el usuario no tiene acceso para actualizar esas páginas.

Anteriormente, cuando un usuario con un perfil de permiso de prueba personalizado navegaba a un documento, la variable [!UICONTROL Actividad de prueba] y [!UICONTROL Configuración del visor de pruebas] las páginas de la izquierda no siempre eran visibles.

**Mensaje de error al usar [!UICONTROL Porcentaje] para [!UICONTROL Horas asignadas]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario selecciona la variable [!UICONTROL Porcentaje] para [!UICONTROL Horas asignadas], y hay trabajo listado en el [!UICONTROL Trabajo sin asignar] , el usuario ve el siguiente error:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

+++

+++**Actualización de mantenimiento del 22 de julio de 2021**

**Nuevos nombres de versión de prueba cortados**

_[!DNL Workfront Proof]_

Cuando un usuario [!DNL Adobe Workfront Classic] carga una nueva versión de una prueba que contiene un punto en el nombre del archivo; el nombre del archivo se corta al final.

+++

+++**Actualización de mantenimiento (corrección) el 19 de julio de 2021**

**Error al intentar navegar a proyectos, partes de horas, tareas o programas**

En el [!DNL Adobe Workfront] experiencia, cuando un usuario intenta navegar a proyectos, partes de horas, tareas o programas, ve el mensaje de error &quot;[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

+++

+++**Actualización de mantenimiento del 15 de julio de 2021**

**La prioridad predeterminada en las nuevas solicitudes es incorrecta**

_Solicitudes_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience crea una solicitud, la solicitud no respeta la prioridad predeterminada establecida en [!UICONTROL Preferencias de proyecto] y no pueden ajustar la prioridad antes de enviar la solicitud.

**[!UICONTROL Vaya a la prueba] el vínculo no dirige a comentar**

_Notificaciones por correo electrónico_

Cuando un usuario recibe una notificación por correo electrónico para un comentario de prueba y hace clic en [!UICONTROL Vaya a la prueba], están dirigidos al comentario incorrecto en la prueba o no están dirigidos a ningún comentario.

**Valores de campo de texto enriquecido que no se transfieren después de convertir un problema en una tarea**

_Formularios personalizados_

Cuando un usuario convierte un problema en una tarea y el problema tiene un formulario personalizado adjunto con un valor introducido en un campo de texto con formato de texto enriquecido, el valor del campo de texto no se transfiere tras la conversión.

**Los valores de los campos personalizados cambian tras la selección**

_[!DNL Workfront Proof]_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience está creando una nueva prueba y especifican un valor en algunos campos personalizados de una prueba, el valor de algunos campos anteriores se revierte a los valores predeterminados en lugar del valor que el usuario ha introducido.

**[!UICONTROL Asignar a] typeforward no funciona**

_[!UICONTROL Página de inicio]_

Cuando un usuario [!DNL Adobe Workfront Classic] crea un proyecto, una tarea o una solicitud desde el [!UICONTROL Página principal] , [!UICONTROL Asignar a] el campo typeforward no rellena los nombres de usuario.

**El redondeo de horas es incorrecto**

_Hojas de horas_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience navega a [!UICONTROL Hojas de tiempo] > [!UICONTROL Todas las HOJAS], observan que los números totales de horas de algunas partes de horas se redondean a un decimal en lugar de a 0,25 incrementos, pero el total de horas se muestra correctamente en cada parte de horas individual. Por ejemplo, en el área Todas las hojas de horas, un parte de horas muestra 44,8 horas totales, pero al abrir el parte de horas, muestra 44,75 horas totales.

**No se pueden delegar aprobaciones**

_[!UICONTROL Página de inicio]_

Cuando un usuario [!DNL Adobe Workfront Classic] clicks [!UICONTROL Delegar mis aprobaciones] en el [!UICONTROL Página principal] y empiezan a escribir el nombre del usuario al que están intentando delegar, no se muestran resultados en el [!UICONTROL typeforward] y no pueden seleccionar un usuario.

**[!UICONTROL Diagrama de Gantt] la vista no está disponible para los informes de tareas**

_Informes_

NOTA: Esto también afecta a los informes de Project.

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience abre un informe Task , la opción para seleccionar una [!UICONTROL Diagrama de Gantt] falta la vista en la barra de herramientas de informes. Si la variable [!UICONTROL Diagrama de Gantt] está seleccionada para mostrarse de forma predeterminada en el informe, se muestra un formato de lista en su lugar.

**Hacer clic [!UICONTROL Más información] en el informe no carga nada**

_Paneles_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] la experiencia está viendo un informe en un tablero y hacen clic en el botón [!UICONTROL Más información] , no ocurre nada y no pueden ver todos los elementos del informe.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento el 1 de julio de 2021**

**La copia de módulos no funciona**

_[!DNL Adobe Workfront Fusion]_

Cuando un usuario selecciona varios módulos e intenta copiarlos y pegarlos, los módulos no se pegan.

+++

+++**Actualización de mantenimiento el 1 de julio de 2021**

**Conjunto de colores para tarjetas no respetadas**

_Kanban_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] conjuntos de experiencias con colores de tarjeta específicos en la configuración del equipo, esos colores no se reflejan en las tarjetas Kanban.

**No se puede pegar texto en el campo de mensaje personalizado**

_[!DNL Workfront Proof]_

Cuando un usuario está creando una prueba nueva en la [!UICONTROL Visor de pruebas web] e intentan pegar texto en el [!UICONTROL Mensaje] en el campo [!UICONTROL Notificación por correo electrónico] , no pueden pegar el texto. Esto solo parece suceder cuando el texto tiene formato de párrafo y hay un salto de párrafo.

**Las solicitudes se envían con campos obligatorios en blanco**

_Solicitudes_

Cuando un usuario realiza una solicitud y la envía, la información de los campos obligatorios no se envía junto con la solicitud.

**[!UICONTROL Nueva solicitud] botón falta**

_Solicitudes_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] la experiencia va a [!UICONTROL Solicitudes] página, la variable [!UICONTROL Nueva solicitud] no se muestra y no pueden enviar una solicitud.

**Error al expandir un formulario personalizado**

_Proyectos_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experiencia intenta expandir un formulario personalizado adjunto a un proyecto, no pueden abrir el formulario personalizado y ver el mensaje de error &quot;[!UICONTROL Se ha producido un error y estamos trabajando para resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador.]Al actualizar la página, el problema no se resuelve.

**[!DNL Adobe Workfront]la marca ahora aparece en los correos electrónicos del centro de anuncios**

Correos electrónicos

Como [!DNL Adobe Workfront] la promoción de la marca se despliega en toda la aplicación, se han realizado las siguientes actualizaciones en los correos electrónicos del centro de anuncios:

* La variable [!DNL Adobe Workfront] se añadió león al área de contenido principal.
* La variable [!DNL Adobe Workfront] se agregó al pie de página.

En el futuro, esta promoción de la marca se mostrará en tipos adicionales de correos electrónicos de Workfront.

+++


## Actualizaciones en junio de 2021

+++**Actualización de mantenimiento del 24 de junio de 2021**

**No se puede editar un equipo**

_Águila_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] clics de experiencia [!UICONTROL Editar] para abrir el [!DNL Edit] Página de equipo de un equipo Agile, la página se carga inicialmente, luego la configuración desaparece y se queda en blanco.

**Datos eliminados de la solicitud enviada**

_Solicitudes_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience rellena una solicitud, a la solicitud enviada le faltan los valores introducidos para algunos campos personalizados, a veces incluidos los campos obligatorios.

**Las columnas no se muestran**

_Kanban_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience añade un [!UICONTROL Campos adicionales] a Kanban Board, todos los encabezados de columna dejan de mostrarse en el tablero.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento del 23 de junio de 2021**

**Se ha eliminado el vínculo roto en los correos electrónicos de notificación**

_[!DNL Adobe Workfront Fusion]_

Hemos eliminado el vínculo a la configuración de notificación de [!DNL Adobe Workfront Fusion] correos electrónicos de notificación.
Para obtener información sobre cómo cambiar la configuración de notificaciones, consulte [!DNL Adobe Workfront Fusion] organizaciones y equipos.

+++

+++**Actualización de mantenimiento del 17 de junio de 2021**

**[!UICONTROL Diagrama de Gantt] la vista no está disponible para el informe Tarea**

_Informes_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience abre un informe Task , la opción para seleccionar una [!UICONTROL Diagrama de Gantt] falta la vista en la barra de herramientas de informes. Si la variable [!UICONTROL Diagrama de Gantt] está seleccionada para mostrarse de forma predeterminada en el informe, se muestra un formato de lista en su lugar.

**El error de límite de caracteres no se produce en los envíos de solicitudes**

_Solicitudes_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience intenta enviar una solicitud y supera el límite de caracteres de un campo, no puede enviar la solicitud y no se muestra ningún mensaje de error. En [!DNL Adobe Workfront Classic], el usuario ve la advertencia &quot;[!UICONTROL [number] y cuando intentan enviar la solicitud, ven el mensaje de error &quot;Compruebe lo siguiente: No escriba más de 2000 caracteres (ha introducido [number] caracteres).]&quot;

+++

+++**Actualización de mantenimiento del 10 de junio de 2021**

**Las tareas de plantilla reordenadas no se mueven**

_Plantillas_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience arrastra una tarea de plantilla a una nueva ubicación de una lista, el número de actualizaciones de la tarea de plantilla, pero no se reordena.

**Tareas secundarias no seleccionadas con tareas principales**

_Plantillas_

Cuando un usuario selecciona una tarea principal en un proyecto creado a partir de una plantilla, las tareas secundarias no se seleccionan automáticamente.

**Los hitos de edición en línea de una lista de tareas muestran todos los hitos**

_Proyectos_

Cuando un proyecto tiene una ruta de hitos añadida y un usuario en la nueva [!DNL Adobe Workfront] experience inline edita la variable [!UICONTROL Milestone: Nombre] en esa lista de tareas, todas las rutas de hitos aparecen en el menú desplegable, en lugar de solo las rutas de hitos que se han adjuntado a ese proyecto.

+++

+++**Actualización de mantenimiento el 3 de junio de 2021**

**Preguntar hace que la página se agite**

_Informes_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience ejecuta un informe con un mensaje, las columnas del informe se mueven rápidamente de izquierda a derecha.

**Algunas frases de la sección [!UICONTROL Nueva prueba] La página no se traduce correctamente**

_[!DNL Workfront Proof]_

Cuando un usuario navega al [!UICONTROL Nueva creación de pruebas] en [!DNL Workfront Proof] y el contenido se está traduciendo a un idioma distinto al inglés, algunas frases siguen apareciendo en inglés.

**Etiquetas desactivadas y eliminadas agregadas a los usuarios[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Desactivado] y [!UICONTROL Eliminado] las etiquetas de usuario se han agregado a las siguientes áreas en [!DNL Workfront] Prueba:

* [!UICONTROL Detalles de la prueba] página
* [!UICONTROL Vistas de prueba]
* [!UICONTROL Visor de pruebas]
* [!UICONTROL Flujos de trabajo de prueba]
* [!UICONTROL Imprimir comentarios] página
* [!UICONTROL Usuario] página

+++


## Actualizaciones de mayo de 2021

+++**Actualización de mantenimiento el 27 de mayo de 2021**

**[!UICONTROL Fecha de confirmación] se muestra calendario para las actualizaciones**

_Tareas_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experiencia está introduciendo una actualización en una tarea, la variable [!UICONTROL Fecha de confirmación] se muestra el calendario sin que el usuario seleccione el [!UICONTROL Fecha de confirmación] campo .

**[!UICONTROL Más] falta el menú en los filtros, vistas y agrupaciones**

_Listas_

Cuando un usuario está en el nuevo [!DNL Adobe Workfront] experience visualiza los filtros, vistas o agrupaciones de una lista, la variable [!UICONTROL Más] falta el icono de menú, lo que les impide compartir o, si tienen acceso, eliminar filtros, vistas o agrupaciones.

**Copia y pegado de un proyecto [!UICONTROL Número de referencia] agrega &quot;[!UICONTROL Esta]&quot;**

_Proyectos_

Cuando un usuario está en el nuevo [!DNL Workfront] experience navega a un proyecto, copia el [!UICONTROL Número de referencia] de la variable [!UICONTROL Información general] , luego pega la palabra &quot;[!UICONTROL Esta]&quot; se añade al final del número.

**[!UICONTROL Resumen diario] los correos electrónicos se envían cuando están desactivados**

_Notificaciones por correo electrónico_

Algunos usuarios reciben [!UICONTROL Resumen diario] las notificaciones por correo electrónico cuando no se hayan habilitado en la configuración de usuario.

**El objeto ya no existe error**

_Objetos_

Cuando un usuario está en el nuevo [!DNL Workfront] experiencia intenta abrir ciertos objetos, ven el mensaje de error &quot;[!UICONTROL El (objeto) ya no existe: Puede que haya escrito mal la dirección web. Vuelva a comprobarlo e intente introducir la dirección de nuevo.]El vínculo de objeto sigue apareciendo en listas, actualizaciones, favoritos, resultados de búsqueda, etc., pero no pueden acceder a él y no aparece en la Papelera de reciclaje con objetos eliminados.



+++

+++**Actualización de mantenimiento del 20 de mayo de 2021**

**Faltan opciones de prueba**

_Pruebas_

Cuando un usuario carga otra versión de una prueba en [!DNL Workfront], el [!UICONTROL Prueba abierta] y [!UICONTROL Flujo de trabajo de prueba] faltan vínculos, por lo que parece que es un documento en lugar de una prueba. Cuando faltan estos vínculos, la etiqueta [!UICONTROL Pendiente] también muestra y otros usuarios no pueden generar la prueba mientras esté en esta [!UICONTROL Pendiente] estado.

**Usuarios que no reciben envíos de informes programados**

_Informes_

Cuando algunos informes están programados para su envío, a veces los usuarios no reciben los informes.

**No se puede quitar el acceso para la plantilla de diseño**

_Paneles_

Cuando se abre un usuario [!UICONTROL Uso compartido] opciones de un tablero para quitar el acceso a una plantilla de diseño, no [!UICONTROL Eliminar] aparece junto a la plantilla de diseño y no pueden eliminar el acceso.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 17 de mayo de 2021**

**El panel de organización ahora muestra correctamente el número de escenarios activos**

_[!DNL Workfront Fusion]_

La variable [!UICONTROL Organización] el tablero mostraba anteriormente un campo en blanco en lugar del número de escenarios que se están utilizando.

**La exploración del almacén de datos ahora muestra las etiquetas de columna**

_[!DNL Workfront Fusion]_

Las estructuras de datos que utilizaban etiquetas de columna anteriormente mostraban el nombre de columna en el [!UICONTROL navegación por el almacén de datos] vista.  Ahora, se muestra la etiqueta de columna.  Si no se identifica ninguna etiqueta para la columna, se muestra el nombre de la columna.

**El error de inicialización del escenario ya no afecta a los datos de weblock**

_[!DNL Workfront Fusion]_

Anteriormente, un escenario iniciado por un enlace web (incluidos los que usan eventos en tiempo real para el déclencheur) que encontró un error durante la inicialización del escenario potencialmente resultaría en la pérdida de acceso a esos datos del enlace web.  Ahora, si se produce un error durante la inicialización del escenario (por ejemplo, si no se puede verificar una conexión), los datos del enlace web se mantendrán en la cola del enlace web y la ejecución se reintentará automáticamente.  Después de tres intentos fallidos, el escenario se desactiva y la información permanece en la cola.

**Los registros de las colas de weblock ahora se procesan en lotes más pequeños**

_[!DNL Workfront Fusion]_

Anteriormente, si un usuario activaba un escenario inactivo que tenía una cola de enlace web asociada de muchos registros, [!DNL Workfront Fusion] intentaría procesar toda la cola en una sola ejecución (aunque en varios ciclos).  En función de la cantidad de registros procesados, esto a veces puede hacer que la ejecución única supere la cantidad máxima de tiempo de ejecución (40 minutos).  Ahora, cuando se activa un escenario inactivo que tiene una cola de registros de enlace web asociada, Workfront Fusion procesará hasta el número máximo de registros identificados en una sola ejecución (normalmente, 2 registros por ejecución).

**Los almacenes de datos ahora muestran correctamente los valores &quot;0&quot;**

_[!DNL Workfront Fusion]_

Anteriormente, los valores del almacén de datos de 0 se mostraban como vacíos. &lt;..>

+++

+++**Actualización de mantenimiento el 13 de mayo de 2021**

**El calendario desplegable aparece detrás del [!UICONTROL Trabajo no asignado] header**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario navega al [!UICONTROL Equilibrador de carga de trabajo] en [!DNL Workfront Classic], la parte superior del selector de fecha está oculta detrás del [!UICONTROL Trabajo no asignado] , lo que impide que el usuario navegue a meses diferentes.

**No se puede pegar texto en el campo de mensaje personalizado**

_[!DNL Workfront Proof]_

Nota: Este problema parece estar afectando solamente a la [!DNL Google Chrome] en este momento.

Cuando un usuario está creando una prueba nueva en [!DNL Workfront Proof] e intentan pegar texto de un correo electrónico en el [!UICONTROL Mensaje] en el campo [!UICONTROL Notificación por correo electrónico] , no pueden pegar el texto.

**Se muestran los campos no admitidos en el generador**

_Formularios personalizados_

Cuando un usuario está creando un formulario personalizado e intenta crear un campo calculado utilizando un campo dinámico, como [!UICONTROL Número de riesgos abiertos]: el cuadro de cálculo resalta el color rojo y no permite guardar los cambios. Los campos dinámicos no deben mostrarse en el selector de campos calculados.

**Vista previa de tareas en [!UICONTROL Lista de trabajo] no se carga**

_Página de inicio_

Cuando un usuario está en el nuevo [!DNL Workfront] la experiencia se asigna a una plantilla de diseño que incluye campos personalizados en [!UICONTROL Página principal], la página no responde y no carga tareas desde el [!UICONTROL Lista de trabajo] si los usuarios los seleccionan.

**Objetos en [!UICONTROL Lista de trabajo] no se carga en [!UICONTROL Página principal]**

_[!UICONTROL Página de inicio]_

Cuando un usuario hace clic en un objeto de la [!UICONTROL Lista de trabajo en el hogar], el encabezado del objeto aparece en el panel derecho, pero no aparecen los detalles del objeto. Finalmente, el usuario ve el mensaje &quot;[!UICONTROL Páginas que no responden.]&quot;

**Problemas con campos de texto enriquecido en[!DNL Microsoft Outlook]**

_Integraciones de Workfront_

Cuando un usuario actualiza un campo de texto enriquecido con la variable [!DNL Workfront for Outlook] , no pueden:

* Retroceso
* Copiar texto
* Pegar texto
* Enviar una solicitud cuando se rellenen todos los campos

+++

+++**Actualización de mantenimiento el 6 de mayo de 2021**

**[!UICONTROL Moneda] el campo no funciona como se esperaba**

_Listas_

Cuando un usuario intenta editar en línea el CurrEl campo de moneda de una lista no puede guardar los cambios debido a los siguientes problemas:

* Listas de tareas y problemas que no permiten la entrada de símbolos de moneda
* Listas que no permiten la introducción de abreviaturas de moneda al utilizar una configuración regional distinta del inglés
* Listas de subtareas y problemas que permiten solamente la abreviación de moneda de USD, independientemente de la moneda del proyecto establecida

**El nombre no se actualiza para que coincida con el nuevo nombre de prueba**

_Documentos_

Cuando un usuario crea una nueva versión de una prueba y actualiza el nombre de la prueba, el objeto de documento en [!DNL Workfront] conserva el nombre original en lugar de coincidir con el nuevo nombre de prueba.

**[!UICONTROL Caso empresarial] los botones no funcionan cuando los formularios personalizados están adjuntos**

_Proyectos_

Cuando un proyecto se incluye en el nuevo [!DNL Workfront] la experiencia se crea a partir de una plantilla de proyecto y hay un formulario personalizado adjunto, los usuarios no pueden enviar, rechazar ni aprobar un caso empresarial.

**Pruebas archivadas que se muestran en listas e informes**

_Pruebas_

Cuando un usuario ve su lista de trabajo en [!UICONTROL Página principal] o [!UICONTROL Mi trabajo], las pruebas que ya se han archivado aparecen en la lista. Las pruebas archivadas también aparecen en informes y tableros.

**El proyecto creado a partir de una plantilla tiene una configuración de acceso incorrecta**

_Proyectos_

Cuando un usuario crea un proyecto a partir de una plantilla, la configuración de acceso de la plantilla no se transfiere al nuevo proyecto creado.

**Objetos en [!UICONTROL Lista de trabajo] no se carga en [!UICONTROL Página principal]**

_[!UICONTROL Página de inicio]_

Cuando un usuario hace clic en un objeto de la [!UICONTROL Lista de trabajo en el hogar], el encabezado del objeto aparece en el panel derecho, pero no aparecen los detalles del objeto. Finalmente, el usuario ve el mensaje &quot;[!UICONTROL Páginas que no responden.]&quot;

+++


## Actualizaciones de abril de 2021

+++**Actualización de mantenimiento del 29 de abril de 2021**

**[!DNL SharePoint]la integración se autentica con credenciales de una integración independiente**

_Integraciones de Workfront_

Cuando un usuario tiene más de uno [!DNL SharePoint] integración, una [!DNL SharePoint] la autenticación intenta autenticarse con las credenciales de otro [!DNL SharePoint] integración.

**No se pueden cargar ni exportar archivos desde [!DNL Adobe] products**

_Integraciones de Workfront_

Cuando un usuario intenta cargar o exportar archivos utilizando la variable [!DNL Workfront for Adobe Creative Cloud] , verán el mensaje de error &quot;[!UICONTROL No se puede leer la propiedad &#39;stage&#39; de undefined]&quot; y no pueden cargar ni exportar los archivos.

**Los archivos no están visibles en[!DNL Internet Explorer]**

_Documentos_

Cuando un usuario con un [!DNL Internet Explorer] El explorador se desplaza a la [!UICONTROL Documentos] área de un objeto, la variable [!UICONTROL Documentos] está en blanco y no carga los archivos. Para algunos usuarios, la pantalla sí carga algunos archivos, pero el número de archivos que aparecen no coincide con el número mostrado al lado del [!UICONTROL Documentos] para obtener más información.

+++

+++**Actualización de mantenimiento del 22 de abril de 2021**

**Tareas agregadas en el orden incorrecto**

_Plantillas_

Cuando un usuario agrega una tarea a una plantilla, la tarea no recibe el número de tarea que espera y se añade en el lugar incorrecto.

**Las pruebas ahora se combinan en un único correo electrónico**

_Pruebas_

[!DNL Workfront] ahora envía un correo electrónico para pruebas combinadas en lugar de enviar un correo electrónico para cada archivo incluido.
+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 15 de abril de 2021**

**&quot;[!UICONTROL Escenario rechazado]&quot; error al ejecutar un escenario**

_[!DNL Workfront Fusion]_

Cuando un usuario intenta ejecutar un escenario, el escenario no se ejecuta y el usuario recibe el mensaje &quot;[!UICONTROL Caso rechazado.]&quot;

+++

+++**Actualización de mantenimiento el 15 de abril de 2021**

**[!UICONTROL Equilibrador de carga de trabajo] muestra las horas planificadas incorrectas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario ve las horas planificadas de una tarea en la variable [!UICONTROL Equilibrador de carga de trabajo] el valor de las horas planificadas no coincide con las horas planificadas asignadas a la tarea.

**La barra de navegación superior no está visible en[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Cuando un usuario navega a cualquier [!DNL Workfront Proof] que no sean la página Tablero , la barra de navegación superior desaparece. El usuario no puede acceder a las funciones de la barra de navegación, como la configuración de su cuenta o su perfil.

**Mejora de los formularios personalizados**

_Formularios personalizados de mi grupo_

Para obtener una mejor experiencia al rellenar un formulario personalizado, hemos mejorado la forma en que se muestran las etiquetas de campo personalizadas largas. Cuando hay suficiente espacio horizontal para mostrarlos en su totalidad, estas etiquetas ya no se truncan.

+++

+++**Actualización de mantenimiento el 8 de abril de 2021**

**No se pueden crear pruebas en [!DNL Adobe Creative Cloud] integración**

_Integraciones de Workfront_

Cuando un usuario intenta crear una prueba directamente desde el [!DNL Adobe Creative Cloud], no se genera la prueba.

+++

+++**Actualización de mantenimiento el 1 de abril de 2021**

**Problemas al ver el panel de resumen en[!DNL Chrome]**

_[!UICONTROL Resumen]_

Cuando un usuario abre el [!UICONTROL Resumen] mientras se usa el [!DNL Chrome] , la interfaz de usuario del panel de resumen no se comporta como se espera. El usuario no puede desplazarse, los iconos pueden desaparecer y el contenido puede superponerse a otro contenido.

**[!UICONTROL Equipos] área [!UICONTROL Configuración] no mostrar todos los equipos**

_[!UICONTROL Configurar]_

Cuando un administrador va al [!UICONTROL Equipos] área de [!UICONTROL Configuración], solo pueden ver los equipos que han creado. Los equipos creados por otros administradores no son visibles.

**No se pueden agregar actualizaciones al proyecto en [!UICONTROL Pendiente de aprobación] status**

_Proyectos_

Si un usuario intenta agregar una actualización a un proyecto en [!UICONTROL Pendiente de aprobación] y no son el usuario asignado para aprobar el proyecto, la actualización no se agrega y verán el siguiente aviso:

Un proyecto con &#39;[!DNL Pending Approval]No se puede editar el estado &#39;. Puede modificar el proyecto cambiando el estado.

+++


## Actualizaciones en marzo de 2021

+++**Actualización de mantenimiento del 26 de marzo de 2021**

**Los botones de un caso empresarial se muestran incorrectamente**

_Proyectos_

Cuando un usuario está viendo un caso empresarial y la ventana está en modo de pantalla completa, la variable [!UICONTROL Guardar] y [!UICONTROL Cancelar] los botones aparecen cerca del centro de la pantalla, superponiendo elementos de casos empresariales.

**No se puede cambiar la ordenación de un informe**

_Informes_

Cuando un usuario intenta cambiar la clasificación de un informe en la nueva [!DNL Workfront] , la clasificación no cambia de la seleccionada cuando se creó el informe.

**Uso compartido deshabilitado en pruebas nuevas**

_[!DNL Workfront Proof]_

Cuando un usuario que tiene [!UICONTROL Uso compartido público] activada en la configuración de prueba predeterminada crea una prueba, la prueba se crea con el uso compartido deshabilitado. Otros usuarios no pueden ver la variable [!UICONTROL Compartir] o comparta la prueba.

**&quot;[!UICONTROL No se pudo generar la prueba]&quot; error al crear la prueba**

_[!DNL Workfront Proof]_

Cuando un usuario intenta crear una prueba, esta no se crea y el usuario ve el siguiente mensaje de error:

&quot;[!UICONTROL Error al generar la prueba: error interno]&quot;

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento del 25 de marzo de 2021**

**Se ha eliminado la colección redundante o el campo de referencia del panel de asignación**

_[!DNL Workfront Fusion]2,0_

Cuando un usuario utiliza un término del [!DNL Workfront] API para seleccionar una colección o un campo de referencia para incluirlos en la salida de un [!DNL Workfront] , la salida de ese módulo muestra ese campo con dos puntos (por ejemplo, [!UICONTROL propietario:nombre]) y también en los atributos (el nombre es un campo bajo propietario). El campo etiquetado con dos puntos no contiene datos y proporciona datos incorrectos si se asigna a un módulo más adelante en el escenario.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento del 18 de marzo de 2021**

**La configuración de la plantilla de proyecto ahora se aplica a los proyectos creados mediante [!DNL Workfront Fusion] 2,0**

_[!DNL Workfront Fusion]2,0_

Al crear un proyecto a partir de una plantilla con la variable [!DNL Workfront Fusion] 2.0, la configuración de la plantilla se aplica al nuevo proyecto. Este comportamiento es el mismo al crear un proyecto a partir de una plantilla en la variable [!DNL Workfront] aplicación.

+++

+++**Actualización de mantenimiento del 18 de marzo de 2021**

**La configuración de la plantilla de proyecto ahora se aplica a los proyectos creados mediante la API**

_[!DNL Workfront]API_

Al crear un proyecto a partir de una plantilla con la variable [!DNL Workfront] , la configuración de plantilla se aplica al nuevo proyecto. Este comportamiento es el mismo al crear un proyecto a partir de una plantilla en la variable [!DNL Workfront] aplicación.

+++

+++**Actualización de mantenimiento (corrección) el 15 de marzo de 2021**

**El componente compartido no funciona como se esperaba**

_[!DNL Workfront Proof]_

Si es independiente [!DNL Workfront Proof] las cuentas se mueven a un componente compartido; la siguiente funcionalidad puede producirse cuando un usuario agrega una nueva versión de una prueba o documento:

* El usuario no puede eliminar el usuario [!UICONTROL Prueba de estudio].
* El mensaje predeterminado no aparece en la nueva versión.

**El uso compartido de vínculos públicos no está habilitado en la nueva versión de una prueba**

_Documentos_

Cuando un usuario habilita el uso compartido de vínculos públicos en una prueba y después carga una nueva versión de la prueba, el uso compartido de vínculos públicos no se habilita automáticamente en la nueva versión de la prueba.

**[!UICONTROL Aprobar], [!UICONTROL Cambios], [!UICONTROL Rechazar] botones que faltan en la prueba**

_[!DNL Workfront Proof]_

Cuando un usuario ve una prueba en el visor de pruebas, la variable [!UICONTROL Aprobar], [!UICONTROL Cambios]y [!UICONTROL Rechazar] no aparecen en la parte superior de la pantalla.

**No se puede cambiar la ordenación de un informe**

_Informes_

Cuando un usuario intenta cambiar la clasificación de un informe en la nueva [!DNL Workfront] , la clasificación no cambia de la seleccionada cuando se creó el informe.

**Mensaje personalizado en la prueba que no se transfiere a la nueva versión**

_[!DNL Workfront Proof]_

Cuando un usuario adjunta un mensaje personalizado a una prueba y luego carga una nueva versión de esa prueba, el mensaje personalizado no aparece en la nueva prueba.

**La lista de usuarios no se muestra**

_Listas_

Cuando un usuario intenta ver una lista de usuarios, y la vista incluye el[!UICONTROL Iconos de estado]&quot;, la lista no se muestra.

**&quot;[!UICONTROL Notificar a los destinatarios sobre esta prueba]&quot; opción desactivada independientemente de la configuración del flujo de trabajo**

_[!DNL Workfront Proof]_

Cuando un usuario crea una prueba nueva y no activa manualmente el[!UICONTROL Notificar a los destinatarios sobre esta prueba]&quot; , no se notifica al destinatario deseado. Esto ocurre incluso si la opción está habilitada en la configuración del flujo de trabajo.

**No se puede cambiar el lapso de tiempo**

_[!UICONTROL Análisis mejorado]_

Cuando el usuario ve [!UICONTROL Análisis mejorado] y hace clic en el calendario para ajustar el intervalo de fechas, las fechas no cambian.

**No se puede descargar un documento compartido públicamente**

_Documentos_

Cuando un usuario hace clic en un vínculo compartido para descargar un documento, el documento no se descarga y el usuario ve un error del explorador que indica que la página no existe.

+++

+++**Actualización de mantenimiento del 11 de marzo de 2021**

**Sección del formulario personalizado que no se exporta para los usuarios que no son administradores**

_Formularios personalizados_

Si un formulario personalizado adjunto a un objeto tiene un salto de sección que requiere cualquier elemento superior a &quot;[!UICONTROL Ver]&quot; acceso necesario para ver el contenido de la sección, el contenido de la sección no se puede exportar a ningún otro usuario que no sea un administrador.

**El documento descargado tiene un nombre incorrecto**

_[!DNL Workfront Proof]_

Cuando un usuario descarga un documento desde la [!UICONTROL Visor de prueba], el del documento tiene el nombre de una versión anterior del documento, no de la versión descargada.

+++

+++**Actualización de mantenimiento del 4 de marzo de 2021**

**Error al acceder a la plantilla de diseño**

_Plantillas de diseño_

Cuando un usuario se inscribe en el nuevo [!DNL Workfront] la experiencia cambia a [!DNL Classic] experiencia e intentos de acceder a un [!DNL Classic] plantilla de diseño, verán el error &quot;[!UICONTROL Esa página no existe.]&quot;

**No se pueden editar los filtros en el [!UICONTROL Equilibrador de carga de trabajo]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta editar un filtro en la [!UICONTROL Equilibrador de carga de trabajo], el generador de filtros no se abre.

**&quot;[!UICONTROL Ver todas las notificaciones]&quot; vínculo en notificación por correo electrónico redirige a página incorrecta**

_Notificaciones por correo electrónico_

Cuando un usuario hace clic en el &quot;[!UICONTROL Ver todas las notificaciones]&quot; en una notificación por correo electrónico, se redirigen a una página con el siguiente mensaje:

&quot;[!UICONTROL El usuario ya no existe. Es posible que haya escrito mal la dirección de Internet. Revise e intente ingresar la dirección nuevamente.]&quot;

**El usuario no está dirigido al comentario de prueba en el que está etiquetado**

_Notificaciones por correo electrónico_

Cuando se etiqueta a un usuario en un comentario de prueba y hace clic en el botón [!UICONTROL Ir a prueba] en una notificación por correo electrónico, se dirigen a la prueba, pero no al comentario específico. Si el usuario se encuentra en [!DNL Workfront Classic], se dirigen al [!UICONTROL Detalles del documento] en lugar del comentario en la prueba.

**Usuarios agregados a [!DNL Workfront] recepción de notificaciones por correo electrónico**

_[!DNL Workfront Proof]_

Cuando un usuario que no está en el flujo de trabajo abre una prueba desde [!DNL Workfront], el sistema crea automáticamente un escenario, agrega este usuario a la prueba y envía un [!UICONTROL Nueva prueba] notificación por correo electrónico.

**El panel de resumen del documento se oscurece, lo que hace que las acciones no estén disponibles**

_Documentos_

Cuando un usuario está en una página de documento y pasa el ratón por encima del panel de resumen del documento, el panel oscurece y puede mostrar otros botones. El usuario no puede hacer clic en las acciones del panel de resumen.

**Actualización de los cambios de rendimiento del flujo**

_Actualizar flujo_

Se ha reducido el número de actualizaciones de usuario que se muestran en la [!UICONTROL Actualizaciones] de 50 a 25 a la vez para mejorar el rendimiento.

+++

+++**Actualización de mantenimiento (corrección) el 1 de marzo de 2021**

**No se envían nuevos correos electrónicos de prueba**

_[!DNL Workfront Proof]_

NOTA: Este problema se corrigió en la nueva [!DNL Workfront] experiencia del 26 de febrero de 2021.
Se corrigió en la variable [!DNL Classic] experiencia del 1 de marzo de 2021.

Cuando un usuario crea una nueva prueba y activa la opción [!UICONTROL Notificar a los destinatarios sobre esta prueba], no hay ningún correo electrónico enviado para notificar al destinatario.

+++


## Actualizaciones en febrero de 2021

+++**Actualización de mantenimiento del 25 de febrero de 2021**

**[!UICONTROL Programación] La herramienta no se carga en ningún área**

_Administración de recursos_

Cuando un usuario con un apóstrofo en su nombre de usuario intenta acceder a la variable [!UICONTROL Programación] herramienta en [!DNL Workfront Classic], la página está en blanco y la herramienta nunca se carga.

**El nombre no cambia en las nuevas versiones de prueba**

_Documentos_

Cuando un usuario está en el nuevo [!DNL Workfront] experience carga una nueva versión de un documento con un nombre diferente, el nombre no se actualiza para que coincida con el nombre de la versión más reciente.

**[!UICONTROL Uso compartido de documentos] error al eliminar proyectos**

_Proyectos_

Cuando un usuario administrador del sistema tiene acceso a un proyecto que se ha copiado e intenta eliminarlo o eliminar un documento del proyecto, no puede eliminarlo y verá el error &quot;[!UICONTROL No se ha encontrado el uso compartido de documentos con valores de clave principal.]&quot;

**El informe de usuario no aplica todos los filtros**

_Informes_

Cuando un usuario está en el nuevo [!DNL Workfront] experience crea un informe de usuario con una regla de filtro que incluye el [!UICONTROL ID principal] , las demás reglas de filtro del informe no se aplican.

**Los campos calculados no se vuelven a calcular después de ediciones**

_Formularios personalizados_

Cuando un usuario está en el nuevo [!DNL Workfront] experience edita y guarda un formulario personalizado que contiene campos calculados; estos campos no se actualizan.

**Documentos que se eliminan al eliminar el formulario personalizado**

_Formularios personalizados_

Cuando un usuario está en el nuevo [!DNL Workfront] experience elimina un formulario personalizado Documents que está adjunto a documentos, esos documentos también se eliminan.

+++

+++**Actualización de mantenimiento el 18 de febrero de 2021**

**Casilla de verificación innecesaria eliminada de [!UICONTROL Solicitudes] area**

_Solicitudes_

Se ha eliminado la casilla de verificación a la izquierda de los nombres de solicitud en la lista Enviado del [!UICONTROL Solicitudes] . Esta casilla de verificación no estaba conectada a ninguna funcionalidad, por lo que la eliminamos para eliminar una experiencia confusa.

**No se puede acceder a los documentos desde los vínculos**

_Documentos_

Cuando un usuario está en el nuevo [!DNL Workfront] la experiencia hace clic en algunos vínculos de documento, no pueden acceder al documento y ven el mensaje de error &quot;[!UICONTROL El documento ya no existe: Puede que haya escrito mal la dirección web. Vuelva a comprobarlo e intente introducir la dirección de nuevo.]&quot; Este mismo error ocurre con la variable [!UICONTROL Ver detalles] en las notificaciones de correo electrónico de prueba.

+++

+++**Actualización de mantenimiento de Workfront Fusion del 16 de febrero de 2021**

**[!DNL Workfront Fusion]2.0 muestra zonas horarias inexactas**

_Escenarios_

Esta actualización solucionó un problema en el que [!DNL Fusion] 2.0 mostraba las zonas horarias del usuario de forma inexacta. Ahora los usuarios pueden ver su zona horaria en los campos de entrada de las fechas.

+++

+++**Actualización de mantenimiento el 11 de febrero de 2021**

**Las pruebas no se cargan en la carpeta seleccionada**

_[!DNL Workfront Proof]_

Cuando un usuario abre una carpeta y agrega una prueba nueva, la prueba se carga en el [!UICONTROL Documentos] del objeto en lugar de en la carpeta.

**Demasiadas páginas ancladas hacen que la navegación superior desaparezca**

_Exploración_

Cuando un usuario tiene más de 60 páginas ancladas, la navegación superior deja de mostrarse, lo que impide que el usuario acceda a ella [!UICONTROL Buscar], el [!UICONTROL Menú principal], [!UICONTROL Notificaciones], y más.

**El usuario no puede escribir texto en un campo de texto enriquecido**

_Listas_

Cuando un usuario intenta editar en línea un campo de texto enriquecido, solo puede escribir un carácter individual.

+++

+++**Actualización de mantenimiento el 4 de febrero de 2021**

**Se muestran informes exportados [!DNL Workfront Classic] promoción de la marca**

_Informes_

Cuando un usuario de la nueva experiencia de Workfront exporta un informe, el logotipo que se muestra en el informe exportado coincide con el de [!DNL Workfront Classic] configuración encontrada en [!UICONTROL Configuración] > [!UICONTROL Sistema] > [!UICONTROL Marcas].

+++


## Actualizaciones de enero de 2021

+++**Actualización de mantenimiento el 28 de enero de 2021**

**Comentarios que no muestran &quot;[!UICONTROL en nombre de]&quot;**

_Actualizaciones_

Cuando [!DNL Workfront] el administrador inicia sesión como otro usuario y responde a un comentario en la [!UICONTROL Actualizaciones] área de un objeto, el texto &quot;[!UICONTROL en nombre de]&quot; no se muestra antes del nombre de usuario.

**No se puede adjuntar un documento**

_Solicitudes_

Cuando un usuario está en el nuevo [!DNL Workfront] experience intenta añadir un documento a una nueva solicitud de un proveedor de documentos externo, el [!UICONTROL Documentos] La lista no se carga, lo que impide que el usuario seleccione el documento y complete la solicitud.

**La anchura de la pantalla se expande a la derecha, lo que provoca problemas de navegación**

_[!UICONTROL Calendario principal]_

Cuando un usuario está en el nuevo [!DNL Workfront] experience abre el [!UICONTROL Calendario principal] y tienen artículos que vencen en algunas semanas, la pantalla se expande a la derecha, evitando que vean la semana completa a la vez. Si el usuario selecciona un elemento para abrir el [!UICONTROL Detalles] en este estado y desean ver los detalles de otro elemento, deben desplazarse hacia la izquierda, lo que cierra el [!UICONTROL Detalles] panel.

**Se corrigió la etiqueta del proceso de aprobación de un solo uso**

_Proyectos_

Cuando se utiliza un proceso de aprobación de un solo uso para un proyecto en el nuevo [!DNL Workfront] experiencia, ahora se muestra como &quot;[!UICONTROL Proceso de aprobación de un solo uso]&quot; en lugar de &quot;\&lt;custom>&quot; en el [!UICONTROL Editar proyecto] en la ventana Esto aún no está disponible para tareas y problemas.

**Aspecto y presentación mejorados para formularios personalizados**

_Proyectos_

Hemos mejorado la apariencia de trabajar con formularios personalizados en el nuevo [!DNL Workfront] experiencia para proyectos.

**La funcionalidad de API para la moneda del proyecto ahora coincide con la funcionalidad en la aplicación**

_Proyectos_

No puede cambiar la moneda de un proyecto cuando ya hay información financiera en él. Con la actualización de mantenimiento más reciente, la funcionalidad de la API para este caso ahora coincide con la experiencia en la [!DNL Workfront] interfaz.

**No genera automáticamente la semana siguiente**

_Hojas de horas_

Cuando un usuario navega al [!UICONTROL Hojas de tiempo] , solo verán el parte de horas de la semana actual. El parte de horas de las próximas semanas no se genera automáticamente.

+++

+++**Actualización de mantenimiento el 21 de enero de 2021**

**Al ordenar manualmente por una columna, se muestran todos los resultados**

_Informes_

Cuando un usuario está en el nuevo [!DNL Workfront] la experiencia hace clic en una barra del gráfico de un informe y, a continuación, hace clic en un encabezado de columna para ordenar manualmente los resultados de esa agrupación, se muestran todos los resultados del informe, no solo los resultados de la agrupación seleccionada originalmente.

**&quot;[!UICONTROL Permitir el uso compartido de la prueba mediante una URL o un código incrustado]&quot; configurar cambios**

_[!DNL Workfront Proof]_

Cuando un usuario crea una prueba y desmarca la configuración [!UICONTROL Permitir el uso compartido de la prueba mediante una URL o un código incrustado], la configuración se vuelve a comprobar una vez generada la prueba. Si el usuario deja la configuración marcada, se desmarca después de generar la prueba.

**[!DNL Mac]los usuarios no pueden pegar en campos de texto en el visor de pruebas**

_[!DNL Workfront Proof]_

Cuando un usuario intenta pegar texto en ciertos campos del visor de pruebas, el texto no aparece en el campo.

+++

+++**Actualización de mantenimiento el 14 de enero de 2021**

**No se puede actualizar la configuración de las notificaciones por correo electrónico**

_Configurar_

Cuando un usuario intenta actualizar la configuración de las notificaciones por correo electrónico, no puede acceder a la variable [!UICONTROL Notificaciones por correo electrónico] y vea el mensaje de error &quot;[!UICONTROL Intentémoslo otra vez. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

**[!UICONTROL Diagrama de Gantt] hace que algunos campos se trunquen**

_Listas_

Cuando un usuario abre el [!UICONTROL Diagrama de Gantt] en algunas áreas de lista, ciertos campos, como [!UICONTROL Descripción]: trunca el texto. El usuario debe hacer doble clic en el campo para ver el texto completo.

**No se pueden enviar archivos desde [!UICONTROL Detalles del documento]**

_Documentos_

Cuando un usuario está en el nuevo [!DNL Workfront] experience intenta enviar un documento desde el [!UICONTROL Detalles del documento] , verán el mensaje de error &quot;[!UICONTROL Se ha producido un error y estamos trabajando para resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador.]&quot;

+++

+++**Actualización de mantenimiento el 7 de enero de 2021**

**Se cierra el cuadro de diálogo Delegar aprobaciones**

_Página de inicio_

Cuando un usuario intenta delegar aprobaciones en [!UICONTROL Página principal] y hacen clic en cualquier fecha, el cuadro de diálogo se cierra sin seleccionar la fecha o permitir al usuario completar la delegación de usuarios.

**Problema al mover un documento a una tarea**

_Documentos_

Cuando un usuario intenta mover un documento o una prueba en el [!DNL Workfront] experiencia, algunas tareas fuera del proyecto no enumeran el proyecto principal como se esperaba.

**El PDF descargado tiene un nombre incorrecto**

_[!DNL Workfront Proof]_

Cuando un usuario recibe un vínculo de descarga por correo electrónico ([!UICONTROL Prueba] > [!UICONTROL Imprimir comentarios] > [!UICONTROL PDF]) y exportan el archivo, el archivo descargado se titula con números aleatorios en lugar del ID de prueba.

+++
