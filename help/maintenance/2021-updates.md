---
title: Actualizaciones de mantenimiento de Workfront para 2021
description: Historial de actualizaciones de mantenimiento de 2021 para [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
feature: Get Started with Workfront
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: ht
source-wordcount: '10060'
ht-degree: 100%

---

# Actualizaciones de mantenimiento de [!DNL Workfront] para 2021

En 2021 se realizaron las siguientes actualizaciones de mantenimiento:

## Actualizaciones en diciembre de 2021

+++**Actualización de mantenimiento el 23 de diciembre de 2021**

**Las nuevas tareas tienen por defecto una restricción de tareas incorrecta**

_Tareas_

Cuando un usuario crea una nueva tarea con el botón “[!UICONTROL Nueva Tarea]”, y la opción de [!UICONTROL Fecha de inicio predeterminada de la nueva tarea] se establece en “[!UICONTROL Hoy]”, la restricción de la tarea creada se establece en “[!UICONTROL Cuanto antes]” en lugar de “[!UICONTROL No empezar antes de]”. Esto también puede ocurrir al usar plantillas de proyectos.

**Abrir la programación en el área de [!UICONTROL Grupos] lleva a una página en blanco**

_Configurar_

Cuando un usuario está viendo los grupos en el área de [!UICONTROL Configuración] e intenta abrir, editar o copiar una programación, esta no se abre y el usuario ve una página en blanco.

**Los cambios no se muestran al reordenar la navegación izquierda**

_Exploración_

Cuando un usuario intenta reordenar el panel de navegación izquierdo arrastrando un elemento, este vuelve a aparecer en su lugar anterior cuando el usuario lo suelta. Si el usuario actualiza la página, el panel izquierdo muestra el orden nuevo.

**El enlace para presentar un documento solicitado dirige a una página en blanco.**

_Documentos_

Cuando un usuario recibe una solicitud de envío de un documento y hace clic en el enlace al objeto donde se solicitó, el enlace dirige a una página en blanco. Esto puede ocurrir al hacer clic en un enlace en un correo electrónico o en una notificación dentro de la aplicación.

**[!UICONTROL El Distribuidor de cargas de trabajo] muestra 0 horas asignadas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario está viendo el [!UICONTROL Distribuidor de cargas de trabajo] y tiene activado el ajuste “[!UICONTROL Mostrar fechas proyectadas]”, cualquier fecha en el futuro muestra 0 horas asignadas.

**Las pruebas desaparecen intermitentemente de las carpetas**

_[!DNL Workfront Proof]_

Cuando un usuario que ha iniciado sesión en [!DNL Workfront Proof] ve una carpeta, aparece vacía. Si el usuario regresa más tarde, las pruebas son visibles.

+++

+++**Actualización de mantenimiento el 16 de diciembre de 2021**

**Si se hace clic en el anuncio de la lista de notificaciones se acaba en una página en blanco**

_Notificaciones_

Cuando un usuario abre su lista de notificaciones desde el icono de [!UICONTROL notificaciones] y luego hace clic en un anuncio, acaba en una página en blanco y el anuncio no se muestra.

**El panel de resumen muestra “[!UICONTROL Sin selección]” cuando la tarea está seleccionada**

_Tareas_

Cuando un usuario abre un resumen de documento en el área de [!UICONTROL Documentos] de un proyecto y va a la lista de tareas, selecciona una e intenta abrir su resumen, este no se muestra y el usuario ve el siguiente mensaje:

[!UICONTROL No hay selección. Seleccione un documento de la lista para ver detalles.]

El mensaje menciona los documentos aunque el usuario esté en la lista de tareas.

**[!UICONTROL El trabajo no asignado] no se carga**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario del [!UICONTROL Distribuidor de cargas de trabajo] crea un filtro con el campo [!UICONTROL Asignación:ID de rol], el área de [!UICONTROL trabajo no asignado] no se carga.

**Al adjuntar una plantilla con la opción “[!UICONTROL Personalizar y adjuntar]” se borran los valores de los campos personalizados**

_Proyectos_

Si un usuario adjunta una plantilla a un proyecto con la opción “[!UICONTROL Personalizar y adjuntar]” y el proyecto ya tiene un formulario personalizado adjunto, los valores de los campos personalizados no se transfieren y deben volver a introducirse manualmente. Esto ocurre incluso aunque la plantilla incluya el mismo formulario personalizado.

+++

+++**Actualización de mantenimiento (Hot Fix) el 10 de diciembre de 2021**

Error “**[!UICONTROL Uy]” al adjuntar una plantilla a un proyecto existente**

_Proyectos_

Cuando un usuario intenta adjuntar una plantilla a un proyecto existente, esta no se adjunta y aparece el siguiente error:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo]”.

+++

+++**Actualización de mantenimiento el 9 de diciembre de 2021**


**Si el panel de navegación izquierdo está colapsado, se expande al cargar la página**

_Exploración_

Cuando un usuario ha configurado su navegación izquierda para que esté colapsada y actualiza una página, la navegación se expande en la página recargada. La navegación izquierda también se expande si el usuario abre una página en una nueva pestaña.

**[!UICONTROL El Distribuidor de cargas de trabajo] muestra 0 horas asignadas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario está viendo el [!UICONTROL Distribuidor de cargas de trabajo] y tiene activado el ajuste “[!UICONTROL Mostrar fechas proyectadas]”, cualquier fecha en el futuro muestra 0 horas asignadas.

+++

+++**Actualización de mantenimiento el 8 de diciembre de 2021**

**La aprobación se restablece cuando se realiza una actualización**

_Rutas de aprobación_

Si un usuario toma una decisión sobre una aprobación con la cabecera del objeto e inmediatamente lo actualiza, los iconos de aprobación vuelven a aparecer en la cabecera y la decisión de aprobación no se guarda.

**[!UICONTROL No se puede editar en línea una asignación en un informe]**

_Informes_

Cuando un usuario intenta editar en línea una asignación en un informe, el valor del campo no cambia y la edición no se guarda.


+++

+++**Actualización de mantenimiento el 2 de diciembre de 2021**

**Se añade una barra extra al escribir manualmente la URL**

_Solicitudes_

Cuando un usuario está rellenando una solicitud y empieza a teclear manualmente una URL, se añade una barra extra en algún punto cerca del principio de la URL. El usuario no puede eliminar la barra.

**Las secciones personalizadas no se pueden eliminar del panel de navegación izquierdo**

_Exploración_

Cuando un usuario intenta eliminar una sección personalizada del panel de navegación izquierdo haciendo clic en la X junto a la sección, esta no se elimina.

**El trabajo no asignado no se carga**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario del [!UICONTROL Distribuidor de cargas de trabajo] crea un filtro con el campo [!UICONTROL Asignación:ID de rol], el área de [!UICONTROL trabajo no asignado] no se carga.

**Las páginas no se cargan en ciertos navegadores**

_[!DNL Workfront]_

Cuando un usuario está trabajando en [!DNL Workfront], las páginas no se cargan y el usuario ve el siguiente mensaje de error:

“[!UICONTROL Se ha producido un error y se está tratando de resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador]”.

Se ha informado de ello en

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Este error se produce de forma aleatoria y puede afectar a cualquier zona de [!DNL Workfront].

+++


## Actualizaciones en noviembre de 2021

+++**Actualización de mantenimiento el 18 de noviembre de 2021**

**[!DNL Workfront]para [!DNL Jira] el error “[!UICONTROL clientID o clientSecret inválidos]” al inicio de sesión**

_Integraciones de Workfront_

Los usuarios se han desconectado del [!DNL Jira] para la integración de Workfront. Cuando un usuario intenta conectarse a la integración [!DNL Workfront for Jira], no puede hacerlo y ve el siguiente error:

“[!UICONTROL clientID o clientSecret inválidos]”

**El formulario personalizado adjunto a la solicitud no se actualiza cuando se selecciona un nuevo tema de la cola**

_Solicitudes_

Cuando un usuario está creando una solicitud y selecciona un Tema de la cola que adjunta automáticamente un formulario personalizado a la solicitud, y luego selecciona un Tema de la cola distinto, el formulario personalizado del primer Tema de la cola permanece adjunto a la solicitud.

**Los iconos se muestran incorrectamente**

_[!DNL Workfront]_

Las imágenes de los iconos se muestran incorrectamente. Se ha informado de esto en muchas áreas a través de [!UICONTROL Workfront].

**Las tareas no se exportan a PDF cuando se selecciona la opción ”Otros tamaños”.**

_Tareas_

Si un usuario intenta exportar una lista de tareas a PDF y selecciona la opción “[!UICONTROL Otros tamaños]”, puede seleccionar un tamaño y hacer clic en [!UICONTROL Exportar], pero la lista no se exporta. No hay ningún mensaje de error ni ninguna otra indicación de que la exportación no haya tenido éxito.

**El indicador de imagen no se muestra en las notificaciones por correo electrónico**

_Notificaciones_

Cuando un usuario añade una imagen a una actualización y se envía una notificación por correo electrónico al destinatario, el correo electrónico no incluye un indicador de que hay una imagen en la actualización.

**Las páginas no se cargan en ciertos navegadores**

_[!DNL Workfront]_

Cuando un usuario está trabajando en [!DNL Workfront], las páginas no se cargan y el usuario ve el siguiente mensaje de error:

“[!UICONTROL Se ha producido un error y estamos tratando de resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador]”.

Se ha informado de ello en

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Este error se produce de forma aleatoria y puede afectar a cualquier zona de Workfront.

+++

+++**Actualización de mantenimiento el 11 de noviembre de 2021**

**Problema con las integraciones de documentos, página en blanco en la ventana emergente de carga de documentos desde[!DNL Google Drive*]*

_Documentos_

Cuando un usuario intenta añadir un nuevo documento a [!DNL Workfront] desde [!DNL Google Drive] mediante [!UICONTROL Añadir nuevo] > [!UICONTROL Desde [!DNL Google Drive]], la pantalla emergente de carga permanece en blanco.

**No se puede usar más de un filtro en el Distribuidor de cargas de trabajo**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta usar más de un filtro en el [!UICONTROL Distribuidor de cargas de trabajo], ve los siguientes problemas:

* Si el usuario selecciona dos filtros, solo se aplica el filtro inferior.
* Si el usuario selecciona más de dos filtros, no se muestra ningún resultado.

**La cabecera del documento “[!UICONTROL Carpetas del proyecto]” no se encuentra en el área de documentos del proyecto**

_Proyectos_

Cuando un usuario se encuentra en un proyecto y visualiza sus documentos, el epígrafe “[!UICONTROL Carpetas del proyecto]” no aparece en la navegación izquierda. La flecha desplegable sigue ahí y el usuario puede seleccionar una carpeta.

**Las columnas del panel Kanban son demasiado anchas y no se pueden ajustar**

_Agile_

Cuando un usuario ve un panel Kanban con varias columnas, estas son demasiado anchas y el usuario debe desplazarse para ver o mover las tarjetas a las columnas más a la derecha. Las anchuras de las columnas no son ajustables, por lo que el usuario no puede reducirlas para que todas sean visibles en la pantalla al mismo tiempo.

**Interfaz mejorada para crear un nuevo equipo**

_Equipos_

Ahora la creación de equipos es más intuitiva con nuevas indicaciones visuales. Cuando se selecciona el icono de [!UICONTROL cambiar de equipo] en cualquier página de equipo, el enlace [!UICONTROL Crear nuevo equipo] tiene un icono que indica “[!UICONTROL nuevo]” y el enlace está separado del resto de la lista para que no parezca un nombre de equipo. Esta interfaz es la misma para los equipos Agile y no Agile.

+++

+++**Actualización de mantenimiento el 4 de noviembre de 2021**

**Las nuevas tareas tienen por defecto una restricción de tareas incorrecta**

_Tareas_

Cuando un usuario crea una nueva tarea con el botón “[!UICONTROL Nueva Tarea]”, y la opción de Fecha de inicio predeterminada de la nueva tarea se establece en “[!UICONTROL Hoy]”, la restricción de la tarea creada se establece en “[!UICONTROL Cuanto antes]” en lugar de “[!UICONTROL No empezar antes de]”.

**Los campos no se muestran en las tarjetas de Agile Story**

_Agile_

Cuando un usuario ve un guion gráfico de Agile, las tarjetas solo muestran los campos [!UICONTROL Descripción] y [!UICONTROL Estado]. No se muestra ningún otro campo, incluidos los campos personalizados.

**Las tarjetas vuelven a la columna original antes de pasar a la nueva columna**

_Agile_

Cuando un usuario arrastra una tarjeta a una nueva columna del guion gráfico, puede ver la tarjeta arrastrada. Sin embargo, cuando el usuario suelta la tarjeta en la nueva columna, esta aparece brevemente en la columna original antes de aparecer en la nueva.

**Valores no disponibles para el campo personalizado en el filtro**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta crear un filtro con un campo personalizado, su valor no se muestra y no se puede introducir en el filtro.

**Las páginas no se cargan en el [!DNL Firefox] navegador**

_[!DNL Workfront]_

Cuando un usuario está trabajando en [!DNL Workfront] con un navegador [!DNL Firefox], las páginas no se cargan y el usuario ve el siguiente mensaje de error:

“[!UICONTROL Se ha producido un error y estamos tratando de resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador]”.

Este error se produce de forma aleatoria y puede afectar a cualquier zona de [!DNL Workfront].

**Error relacionado con la fecha al crear un proyecto a partir de una plantilla.**

_Plantillas_

Si un usuario crea un proyecto a partir de una plantilla, establece el modo de programación en [!UICONTROL Fecha de inicio] y a continuación selecciona una restricción de tarea, el proyecto no se crea y el usuario ve un mensaje de error basado en la restricción de tarea.

El diálogo para **[!UICONTROL exportar el gráfico Gantt] no responde**

_Gráfico Gantt_

Si un usuario de la nueva experiencia [!DNL Workfront] intenta exportar el [!UICONTROL gráfico Gantt] y selecciona la opción “[!UICONTROL Lo que veo]”, el [!UICONTROL gráfico] no se exporta y el cuadro de diálogo no responde. El usuario no puede cerrar o hacer clic para salir del cuadro de diálogo.

**Los iconos se muestran incorrectamente**

_[!DNL Workfront]_

Las imágenes de los iconos se muestran incorrectamente. Se han notificado situaciones que incluyen, pero no se limitan a:

* Imágenes para roles o grupos de trabajo al compartir un objeto
* Iconos de izquierda y derecha en los informes del calendario
* Iconos de ordenación en las columnas del informe

**Añadir casillas de verificación a las solicitudes en la sección de [!UICONTROL enviadas] del área de [!UICONTROL solicitudes]**

_Solicitudes_

Hemos añadido casillas de verificación a la izquierda de los nombres de las solicitudes en la [!UICONTROL lista de Enviados] del área de [!UICONTROL Solicitudes]. Esto facilita la selección de una solicitud y la visualización de información adicional.

**Ahora se admiten trimestres personalizados en los filtros del Distribuidor de cargas de trabajo**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Ahora, los filtros del [!UICONTROL Distribuidor de cargas de trabajo] admiten trimestres personalizados.

**Operador de filtro actualizado para el campo Duración en los filtros del Distribuidor de cargas de trabajo**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Hemos actualizado los operadores de filtro cuando se filtran las áreas del[!UICONTROL  Distribuidor de cargas de trabajo] por [!UICONTROL Duración].

+++


## Actualizaciones en octubre de 2021

+++**Actualización de mantenimiento el 28 de octubre de 2021**

**[!UICONTROL Inicio] y [!UICONTROL Mi trabajo] muestran una página en blanco**

_[!UICONTROL Inicio] / [!UICONTROL Mi trabajo]_

Cuando un usuario navega a [!UICONTROL Inicio] o a Mi trabajo, la página se muestra en blanco.

**No se pueden ver o editar los detalles del [!UICONTROL grupo de temas]**

_Solicitudes_

Cuando un usuario intenta ver o editar los detalles de un Grupo de temas, la página que se abre muestra “[!UICONTROL Detalle del grupo de temas]” en la cabecera pero por lo demás está en blanco

**Los botones de opción requeridos en blanco se rellenan automáticamente**

_Solicitudes_

Cuando un usuario envía una solicitud con un campo de botón de opción obligatorio y no ha seleccionado un valor para ese campo antes de enviar la solicitud, el primer valor se selecciona automáticamente cuando se envía la solicitud.

+++

+++**Actualización de mantenimiento el 21 de octubre de 2021**

**No se puede añadir un filtro en el [!UICONTROL Distribuidor de cargas de trabajo]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario del [!UICONTROL Distribuidor de cargas de trabajo] intenta añadir un filtro, se abre el panel [!UICONTROL Añadir filtro], pero su contenido no se carga y el usuario no puede añadir el filtro.

**El panel de exploración de Agile no muestra las historias**

_Agile_

Cuando un usuario intenta ver el guion gráfico de Scrum en una iteración del equipo, se muestra en blanco.

**El guion gráfico de Scrum está en blanco cuando se usan filtros**

_Agile_

Cuando un usuario intenta ver un guion gráfico de Scrum usando cualquier filtro excepto el de “[!UICONTROL Todo el equipo]”, aparece una pantalla en blanco. El usuario no puede volver a cambiar al filtro “[!UICONTROL Todo el equipo]”.

**Las listas solo son visibles en una pequeña zona de la pantalla**

_Listas_

Cuando un usuario intenta ver una lista mientras usa un navegador [!DNL Safari] en un [!DNL Mac] con el [!DNL Big Sur OS], la lista solo aparece en una pequeña zona de la pantalla. El usuario puede desplazarse por la lista, pero el área puede ser tan pequeña que podría resultar difícil o imposible de leer.

**Los botones de opción requeridos en blanco se rellenan automáticamente**

_Solicitudes_

Cuando un usuario envía una solicitud con un campo de botón de opción obligatorio y no ha seleccionado un valor para ese campo antes de enviar la solicitud, el primer valor se selecciona automáticamente cuando se envía la solicitud.

+++

+++**Actualización de mantenimiento (Hot Fix) el 21 de octubre de 2021**

**[!UICONTROL Inicio] y [!UICONTROL Mi trabajo] muestran una página en blanco**

_[!UICONTROL Inicio] / [!UICONTROL Mi trabajo]_

Cuando un usuario navega a [!UICONTROL Inicio] o a [!UICONTROL Mi trabajo], la página se muestra en blanco.

+++

+++**Actualización de mantenimiento el 20 de octubre de 2021**

**[!UICONTROL Distribuidor de cargas de trabajo] establecido como opción de programación por defecto**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Si un usuario que tiene el [!UICONTROL Planificador] configurado como predeterminado va a usarlo, verá que el [!UICONTROL Distribuidor de cargas de trabajo] se ha configurado como predeterminado.

+++

+++**Actualización de mantenimiento (Hot Fix) el 19 de octubre de 2021**

**No se puede asignar una solicitud al crearla**

_Solicitudes_

Cuando un usuario de la nueva experiencia [!DNL Workfront] está creando una solicitud e intenta asignar un usuario escribiendo su nombre en el campo [!UICONTROL Asignaciones], el campo no muestra la lista desplegable y el usuario no puede seleccionar el nombre del asignado.

**El guion gráfico de Scrum está en blanco cuando se usan filtros**

_Agile_

Cuando un usuario intenta ver un guion gráfico de Scrum usando cualquier filtro excepto el de “[!UICONTROL Todo el equipo]”, aparece una pantalla en blanco. El usuario no puede volver a cambiar al filtro “[!UICONTROL Todo el equipo]”.

+++

+++**Actualización de mantenimiento el 14 de octubre de 2021**

**Las plantillas que se comparten en todo el sistema no son visibles**

_Plantillas_

Cuando un usuario está creando un proyecto e intenta usar una plantilla que se ha compartido en todo el sistema, no puede verla en la lista de plantillas disponibles ni usarla.

**Error al crear proyectos a partir de plantillas**

_Plantillas_

Cuando un usuario intenta crear un proyecto a partir de una plantilla que incluye un formulario personalizado con una sección visible solo para administradores, el usuario no puede crear el proyecto y aparece el siguiente mensaje:

“[!UICONTROL Categoría tiene uno o varios valores claves principales “xxxxxxxxxxxxxxxx” que no se encontraron]”

**Enlaces actualizados para copiar y mover tareas**

_Tareas_

Los enlaces para copiar y mover tareas se han actualizado a “[!UICONTROL Copiar a]” y “[!UICONTROL Mover a]” tanto en la página de la tarea como en una lista de tareas.

**Eliminado el límite de búsqueda de funciones cuando se anulan las tarifas de facturación de un proyecto**

Roles

NOTA: esta actualización se encuentra actualmente en el entorno de vista previa y llegará a Production en la versión 22.1. Para más información, consulte “Resumen de la versión 22.1”.

Ahora la anulación de las tarifas de facturación para las funciones en un proyecto busca todos los roles de trabajo en el sistema.

Anteriormente, [!DNL Workfront] buscaba las funciones en las primeras 2000 por orden alfabético.

+++

+++**Actualización de mantenimiento el 7 de octubre de 2021**

**[!UICONTROL Las notificaciones en la aplicación desaparecen del] centro de notificaciones**

_Notificaciones_

Cuando un usuario ve el centro de notificaciones, algunas notificaciones anteriormente visibles dejan de serlo. En algunos casos, la notificación puede desaparecer antes de que el usuario la vea.

**Los anuncios no son visibles en la página de [!UICONTROL Todos los anuncios]**

_Notificaciones_

Cuando un usuario abre la página de [!UICONTROL Todos los anuncios] desde el área de [!UICONTROL Notificaciones], no hay anuncios visibles en las siguientes áreas:

* [!UICONTROL Bandeja de entrada]
* [!UICONTROL Favoritos]
* [!UICONTROL Borradores]
* [!UICONTROL Eliminado]

**Error al realizar la asignación en el [!UICONTROL Distribuidor de cargas de trabajo]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta realizar una asignación desde el [!UICONTROL Distribuidor de cargas de trabajo], el trabajo no se asigna y se muestra el siguiente error:

“[!UICONTROL Se ha producido un error y estamos tratando de resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador]”.

+++


## Actualizaciones en septiembre de 2021

+++**Actualización de mantenimiento el 30 de septiembre de 2021**

**Error al navegar rápidamente hacia o desde [!UICONTROL Inicio]**

_Página de inicio_

Cuando un usuario navega rápidamente hacia o desde [!UICONTROL Inicio], la página no se carga y se muestra el siguiente error:

“[!UICONTROL Se ha producido un error y estamos tratando de resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador]”.

Esto también puede ocurrir cuando se navega a [!UICONTROL Inicio] a través de un pin.

+++

+++**Actualización de mantenimiento el 23 de septiembre de 2021**

Error de **[!UICONTROL acceso denegado] al ver los tickets enviados a[!DNL Workfront]**

_Problemas_

Cuando un usuario ha enviado un ticket a [!DNL Workfront] e intenta verlo, aparece el siguiente error:

“[!UICONTROL Acceso denegado: ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo]”.

**El resumen del caso empresarial muestra valores incorrectos**

_Proyectos_

Cuando un usuario ve el panel de resumen del [!UICONTROL caso empresarial], los valores mostrados no reflejan los valores de las secciones individuales del [!UICONTROL caso].

**Las cabeceras de las columnas no se alinean con las columnas en las listas**

_Configurar_

Cuando un usuario se encuentra en el área de [!UICONTROL Configuración] y ve una lista, como la de [!UICONTROL Formularios personalizados] o la de [!UICONTROL Niveles de acceso], los encabezados de la lista no se alinean con sus columnas.

**Los usuarios sin los permisos adecuados para compartir pueden adjuntar formularios personalizados a los objetos**

_Formularios personalizados_

Cuando un formulario personalizado de la nueva experiencia [!DNL Adobe Workfront] se configura para que sea visible en todo el sistema, todos los usuarios pueden adjuntar este formulario personalizado a un objeto. Sin embargo, solo pueden ver el formulario personalizado y no pueden adjuntarlo a un objeto a menos que se haya compartido específicamente con ellos.

+++

+++**Actualización de mantenimiento el 16 de septiembre de 2021**

**No se pueden editar los grupos**

_Grupos_

Cuando un usuario intenta editar o eliminar un grupo, no se edita ni se elimina, y se muestra el siguiente mensaje:

“[!UICONTROL Intentémoslo de nuevo. El grupo tiene uno o varios valores claves principales “(ID de grupo)” que no se encontraron]”

**[!UICONTROL El optimizador de portafolios] no muestra los proyectos**

_Portafolios_

Cuando un usuario intenta ver los proyectos en el [!UICONTROL Optimizador de portafolios], la lista de proyectos no se muestra y, por tanto, el usuario no puede interactuar con los proyectos.

+++

+++**Actualización de mantenimiento (Hot Fix) el 10 de septiembre de 2021**

**Fecha y hora marcadas como UTC al editar en línea**

_Listas_

Cuando un usuario edita una fecha u hora en línea (en una lista de objetos), la fecha y la hora se marcan como UTC. La fecha y la hora no se fijan en UTC en [!DNL Workfront]. Este problema solo afecta a la visualización, no a los datos reales.

**El color del texto no se muestra correctamente cuando se aplica el formato condicional**

_Informes_

Cuando un usuario ve un informe con un formato condicional que altera el color del texto, el color no se muestra correctamente.

+++

+++**Actualización de mantenimiento el 9 de septiembre de 2021**

**Los problema no muestran los detalles**

_Página de inicio_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] selecciona un problema de la [!UICONTROL Lista de trabajos], la vista previa en el panel derecho muestra ciertos campos como sin valores introducidos. Sin embargo, si navega hasta el problema y ve sus [!UICONTROL detalles], los campos tienen valores introducidos.

**Los usuarios necesitan permisos de contribución para ver la sección de [!UICONTROL aprobaciones] en la nueva experiencia de Workfront**

_Rutas de aprobación_

Los usuarios necesitan permisos de [!UICONTROL contribución] para ver la sección de [!UICONTROL aprobaciones] en la nueva experiencia [!DNL Workfront]. Solo deberían necesitar permisos de [!UICONTROL Vista] para ver la pestaña [!UICONTROL Aprobaciones] cuando haya un proceso de aprobación en el objeto.

Error “**[!UICONTROL ¡Uy!]” al usar los filtros**

_Listas_

Cuando un usuario intenta usar uno de los siguientes filtros:

* [!UICONTROL Todos los proyectos]
* [!UICONTROL Proyectos en los que participo]
* [!UICONTROL Mis tareas actuales]

la lista se queda en blanco y aparece el siguiente error:

“[!UICONTROL Intentémoslo de nuevo.]”

La sección de **[!UICONTROL tareas] queda en blanco al editar en línea**

_Plantillas_

Cuando un usuario intenta editar en línea las tareas de una plantilla con una vista que incluye el campo “[!UICONTROL Asignar a: Nombre]”, y la asignación contiene un usuario, la sección [!UICONTROL Tareas] queda en blanco y el usuario no puede editar las tareas de la plantilla.

**No se puede exportar el [!UICONTROL Optimizador de portafolios]**

_Portafolios_

Cuando un usuario intenta exportar el [!UICONTROL Optimizador de portafolios] y hace clic en cualquiera de las opciones de exportación, el [!UICONTROL Optimizador de portafolios] no se exporta.

**No se envían notificaciones para las respuestas**

_Notificaciones_

Cuando un usuario responde a una actualización en [!DNL Workfront], los demás usuarios del hilo de comentarios no reciben notificaciones.

**Los cambios en los datos personalizados provocan un retraso**

_Campos personalizados_

Cuando un usuario modifica datos personalizados que desencadenan cambios en otros datos visualizados, estos se cargan lentamente.

**No aparece el icono de agrupación “[!UICONTROL Contraer o expandir todo]”**

_Informes_

No aparece el icono “[!UICONTROL Contraer o expandir todo]” en la cabecera de una lista o informe cuando se le aplican agrupaciones.

Las opciones **[!UICONTROL Verificar] y [!UICONTROL Cancelar] no son visibles al cambiar las asignaciones de tareas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta cambiar la asignación de una tarea y el plazo se extiende hasta o más allá del borde de la página visible, los botones [!UICONTROL Verificar] y [!UICONTROL Cancelar] no son visibles, y el usuario no puede guardar o cancelar los cambios de asignación.

**Añadir un campo personalizado a [!UICONTROL Inicio] causa una pérdida de datos en los campos**

_[!UICONTROL Página de inicio]_

Cuando se añade un campo personalizado a [!UICONTROL Inicio], los demás campos empiezan a perder datos y a mostrarse de forma incorrecta.

**No se pueden ver los elementos vinculados cuando se inicia la sesión como otro usuario**

_Integraciones_

Si un administrador intentaba ver los elementos vinculados de un proveedor externo mientras estaba conectado como otro usuario, no podía abrir las carpetas vinculadas ni ver los elementos.

+++

+++**Actualización de mantenimiento el 2 de septiembre de 2021**

**No se puede fijar el panel personalizado**

_Paneles_

Cuando un usuario intenta fijar un panel personalizado, este no se fija y aparece el siguiente error:

“[!UICONTROL Se ha producido un error al fijar el panel. Póngase en contacto con [!DNL Workfront]para solucionarlo]”.

El resumen de impresión **[!DNL Workfront Proof]está en blanco**

[!DNL Workfront Proof]

Cuando un usuario abre el resumen de impresión para imprimir una prueba, aparece la cabecera pero el propio resumen está en blanco.

+++


## Actualizaciones en agosto de 2021

+++**Actualización de mantenimiento el 26 de agosto de 2021**

**En [!DNL Safari] hay un fondo gris oscuro en el texto de las cabeceras de las columnas**

_Listas_

En el navegador [!DNL Safari], hay un fondo gris oscuro en las cabeceras de las columnas que resalta el texto. Esto no es un problema con otros navegadores compatibles.

**Error inesperado al establecer predecesores**

_Tareas_

Cuando un usuario intenta establecer una tarea como predecesora mediante la edición en línea, el predecesor no se establece y aparece el siguiente mensaje:

“[!UICONTROL Se produjo un error inesperado]”

+++

+++**Actualización de mantenimiento el 19 de agosto de 2021**

**Faltan los filtros guardados después de seleccionar un filtro que no muestra problemas**

_Listas_

Los filtros guardados no aparecen en una lista de problemas después de seleccionar un filtro que no muestra resultados.

**Los problema no muestran los detalles**

Resumen de _[!UICONTROL Inicio]_

Cuando un usuario en [!DNL Adobe Workfront Classic] selecciona un problema de la [!UICONTROL Lista de trabajos], la vista previa en el panel derecho muestra ciertos campos como sin valores introducidos. Sin embargo, si navega hasta el problema y ve sus [!UICONTROL detalles], los campos tienen valores introducidos.

+++

+++**Actualización de mantenimiento el 12 de agosto de 2021**

**No se puede personalizar la vista Agile en el proyecto**

_Agile_

Cuando un usuario intenta personalizar una vista Agile preexistente en un proyecto, la ventana se cierra y el usuario no puede editar la vista.

**El nombre no cambia en las nuevas versiones del documento**

_Documentos_

Cuando un usuario sube una nueva versión de un documento, el nombre no se actualiza para coincidir con el de la nueva versión.

**El icono de la predecesora no se pone verde cuando está completa.**

_Tareas_

Cuando una tarea tiene una tarea predecesora que está completa, el icono de la predecesora en la tarea dependiente no se vuelve verde.

Cuando un formulario personalizado de la nueva experiencia [!DNL Adobe Workfront] se configura para que sea visible en todo el sistema, todos los usuarios pueden adjuntar este formulario personalizado a un objeto. Sin embargo, solo pueden ver el formulario personalizado y no pueden adjuntarlo a un objeto a menos que se haya compartido específicamente con ellos.

+++

+++**Actualización de mantenimiento (Hot Fix) el 6 de agosto de 2021**

No **se puede seleccionar los calendarios en la configuración del calendario [!DNL Outloo]k**

_Página de inicio_

Cuando un usuario en la nueva experiencia [!DNL Workfront] está viendo su Calendario [!DNL Outlook] en inicio y abre los ajustes, no aparecen las casillas para seleccionar calendarios. Si el usuario hace clic en el lugar donde estaría la casilla de verificación, el calendario responde como si la casilla estuviera allí.

**No se puede reautorizar o verificar la conexión con [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

Los usuarios de [!DNL Adobe Workfront Fusion] con escenarios que se conectan a [!UICONTROL Webdam] deben saber que las conexiones de [!UICONTROL Webdam] requieren una reautenticación manual cada 14 días. Actualmente, la API de [!UICONTROL Webdam] no admite una reautorización automática.

+++

+++**Actualización de mantenimiento el 5 de agosto de 2021**

**No se puede interactuar con el documento en el [!UICONTROL panel de resumen] o en el menú [!UICONTROL Más]**

_Documentos_

Cuando un usuario de la nueva experiencia [!DNL Workfront] está viendo un documento e intenta hacer una selección en el [!UICONTROL panel de resumen] o en el menú [!UICONTROL Más], el documento se deselecciona, lo que provoca que el [!UICONTROL panel de resumen] o el menú [!UICONTROL Más] queden en blanco.

Desaparece el botón **[!UICONTROL Nueva solicitud]**

_Solicitudes_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] va a la página de [!UICONTROL solicitudes], no aparece el botón [!UICONTROL Nueva solicitud] y no puede enviar una.

**Los usuarios sin los permisos adecuados para compartir pueden adjuntar formularios personalizados a los objetos**

_Formularios personalizados_

Cuando un formulario personalizado de la nueva experiencia [!DNL Adobe Workfront] se configura para que sea visible en todo el sistema, todos los usuarios pueden adjuntar este formulario personalizado a un objeto. Sin embargo, solo pueden ver el formulario personalizado y no pueden adjuntarlo a un objeto a menos que se haya compartido específicamente con ellos.

**No se puede cambiar la configuración al crear una nueva prueba**

_[!DNL Workfront Proof]_

Cuando un usuario crea una nueva prueba e intenta cambiar su configuración, vuelve a la configuración anterior.

**[!UICONTROL El guion gráfico] no se carga correctamente**

_Agile_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] navega a un [!UICONTROL guion gráfico], puede tardar hasta 10 segundos en cargarse. El retraso en la carga se debe a que el sistema carga todas las tarjetas cuando solo debería cargarlas de 50 en 50.

+++


## Actualizaciones en julio de 2021

+++**Actualización de mantenimiento (Hot Fix) el 29 de julio de 2021**

**No se puede subir una nueva prueba o versión**

_[!DNL Workfront Proof]_

Cuando un usuario intenta subir una nueva prueba o versión en la experiencia clásica [!DNL Workfront], la página de la nueva prueba o de la nueva versión está en blanco y no se puede subir la prueba o versión.

+++

+++**Actualización de mantenimiento el 29 de julio de 2021**

Las páginas de **[!UICONTROL actividad de pruebas] y de [!UICONTROL configuración del visor de pruebas] siempre están disponibles**

_[!DNL Workfront Proof]_

Ahora, las páginas de [!UICONTROL Actividad de pruebas] y de [!UICONTROL Configuración del visor de pruebas] siempre están visibles, aunque el usuario no tenga acceso para actualizar esas páginas.

Anteriormente, cuando un usuario con un perfil de permiso de pruebas personalizado navegaba a un documento, las páginas de [!UICONTROL Actividad de pruebas] y [!UICONTROL Configuración del visor de pruebas] de la izquierda no siempre eran visibles.

**Mensaje de error al usar la opción de [!UICONTROL porcentaje] para las [!UICONTROL horas asignadas]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario selecciona la opción [!UICONTROL porcentaje] para las [!UICONTROL horas asignadas] y hay trabajo en la sección de [!UICONTROL trabajo no asignado], aparece el siguiente error:

“[!UICONTROL Se ha producido un error y se está tratando de resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador]”.

+++

+++**Actualización de mantenimiento el 22 de julio de 2021**

**Los nombres de la nueva versión de prueba aparecen cortados**

_[!DNL Workfront Proof]_

Cuando un usuario en [!DNL Adobe Workfront Classic] sube una nueva versión de una prueba que contiene un punto en el nombre del archivo, este se corta al final.

+++

+++**Actualización de mantenimiento (Hot Fix) el 19 de julio de 2021**

**Error al intentar navegar a proyectos, plantillas de horas, tareas o programas**

En la nueva experiencia [!DNL Adobe Workfront], cuando un usuario intenta navegar a proyectos, plantillas de horas, tareas o programas, ve el mensaje de error “[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo]”.

+++

+++**Actualización de mantenimiento el 15 de julio de 2021**

**La prioridad por defecto en las nuevas solicitudes es incorrecta**

_Solicitudes_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] crea una solicitud, esta no respeta la prioridad por defecto establecida en las [!UICONTROL Preferencias del proyecto] y no puede ajustarla antes de enviar la solicitud.

El enlace **[!UICONTROL ir a la prueba] no dirige al comentario**

_Notificaciones por correo electrónico_

Cuando un usuario recibe una notificación por correo electrónico de un comentario de la prueba y hace clic en [!UICONTROL ir a la prueba], se le dirige al comentario equivocado de la prueba o no se le dirige a ningún comentario.

**Los valores de los campos de texto enriquecido no se arrastran después de convertir un problema en una tarea**

_Formularios personalizados_

Cuando un usuario convierte un problema en una tarea y el problema tiene un formulario personalizado adjunto con un valor introducido en un campo de texto con formato de texto enriquecido, el valor del campo de texto no se traslada tras la conversión.

**Los valores de los campos personalizados cambian después de la selección**

_[!DNL Workfront Proof]_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] está creando una nueva prueba e introduce un valor en algunos campos personalizados, el valor de algunos de los campos anteriores vuelve a los valores por defecto en lugar del valor que el usuario haya introducido.

“**[!UICONTROL Asignar a]” no funciona**

_[!UICONTROL Página de inicio]_

Cuando un usuario en [!DNL Adobe Workfront Classic] crea un proyecto, una tarea o una solicitud desde el área de [!UICONTROL Inicio], el campo [!UICONTROL Asignar a] no rellena los nombres de los usuarios.

**Redondeo de horas incorrecto**

_Hojas de horas_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] navega a [!UICONTROL Plantillas de horas] > [!UICONTROL Todas las plantillas de horas], ve que los números de horas totales para algunas plantillas se redondean a un decimal en lugar de en incrementos de 0,25, pero las horas totales se muestran correctamente en la hoja de horas individual. Por ejemplo, en el área de Todas las plantillas de horas, una plantilla muestra 44.8 horas totales, pero al abrir la hoja de horas, muestra 44.75 horas totales.

**No se pueden delegar las aprobaciones**

_[!UICONTROL Página de inicio]_

Cuando un usuario en [!DNL Adobe Workfront Classic] hace clic en [!UICONTROL Delegar mis aprobaciones] en el área de [!UICONTROL Inicio] y comienza a escribir el nombre del usuario al que intenta delegar, no se muestran resultados en la [!UICONTROL lista de escritura] y no puede seleccionar un usuario.

La vista del **[!UICONTROL gráfico Gantt] no está disponible para los informes de tareas**

_Informes_

NOTA: Esto también afecta a los informes de los proyectos.

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] abre un informe de tareas, no aparece la opción de seleccionar una vista de [!UICONTROL gráfico Gantt] en la barra de herramientas del informe. Si se selecciona la vista de [!UICONTROL gráfico Gantt] para que aparezca por defecto en el informe, en su lugar aparece un formato de lista.

**Al hacer clic en [!UICONTROL Ver más] en el informe no se carga nada**

_Paneles_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] está viendo un informe en un panel y hace clic en el botón [!UICONTROL Ver más], no ocurre nada y no puede ver todos los elementos del informe.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento el 1 de julio de 2021**

**La copia de módulos no funciona**

_[!DNL Adobe Workfront Fusion]_

Cuando un usuario selecciona varios módulos e intenta copiarlos y pegarlos, no se pegan.

+++

+++**Actualización de mantenimiento el 1 de julio de 2021**

**No se respetan los conjuntos de colores para las tarjetas**

_Kanban_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] establece colores específicos para las tarjetas en los ajustes del equipo, no se reflejan en las tarjetas Kanban.

**No se puede pegar el texto en el campo de mensaje personalizado**

_[!DNL Workfront Proof]_

Cuando un usuario está creando una nueva prueba en el [!UICONTROL Visor de pruebas web] e intenta pegar un texto en el campo [!UICONTROL Mensaje] de la sección de [!UICONTROL notificación por correo electrónico], no puede pegar el texto. Esto solo parece ocurrir cuando el texto tiene formato de párrafo y hay un salto de párrafo.

**Las solicitudes se presentan con los campos obligatorios en blanco**

_Solicitudes_

Cuando un usuario realiza una solicitud y la envía, la información de los campos obligatorios no se envía con la solicitud.

Desaparece el botón **[!UICONTROL Nueva solicitud]**

_Solicitudes_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] va a la página de [!UICONTROL solicitudes], no aparece el botón [!UICONTROL nueva solicitud] y no puede enviar una.

**Error al expandir un formulario personalizado**

_Proyectos_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] intenta ampliar un formulario personalizado adjunto a un proyecto, no puede abrir el formulario personalizado y ve el mensaje de error “[!UICONTROL Se ha producido un error. Estamos trabajando para resolverlo. Para continuar con su trabajo, intente actualizar esta página del explorador.]” Al actualizar la página, el problema no se resuelve.

Ahora la marca **[!DNL Adobe Workfront]aparece en los correos electrónicos del centro de anuncios**

Correos electrónicos

A medida que la marca [!DNL Adobe Workfront] se implanta en toda la aplicación, se han realizado las siguientes actualizaciones en los correos electrónicos del centro de anuncios:

* Se ha añadido el león [!DNL Adobe Workfront] al área de contenido principal.
* Se ha añadido el logotipo [!DNL Adobe Workfront] al pie de página.

En el futuro, esta marca se mostrará en otros tipos de correos electrónicos de Workfront.

+++


## Actualizaciones en junio de 2021

+++**Actualización de mantenimiento el 24 de junio de 2021**

**No se puede editar un equipo**

_Agile_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] hace clic en [!UICONTROL Editar] para abrir la página [!DNL Edit] de Equipo para un equipo ágil, la página se carga inicialmente, pero los ajustes desaparecen y se queda en blanco.

**Datos eliminados de la solicitud enviada**

_Solicitudes_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] rellena una solicitud, a la solicitud enviada le faltan los valores introducidos para algunos campos personalizados, a veces incluso en campos obligatorios.

**Las columnas no se muestran**

_Kanban_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] añade una columna de [!UICONTROL Campos adicionales] personalizada a un panel Kanban, todas las cabeceras de las columnas dejan de mostrarse en el panel.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento el 23 de junio de 2021**

**Se ha eliminado el enlace roto en los correos electrónicos de notificación**

_[!DNL Adobe Workfront Fusion]_

Hemos eliminado el enlace a la configuración de las notificaciones de los correos electrónicos de notificación de [!DNL Adobe Workfront Fusion].
Para más información sobre cómo cambiar la configuración de las notificaciones, consulte organizaciones y equipos de [!DNL Adobe Workfront Fusion].

+++

+++**Actualización de mantenimiento el 17 de junio de 2021**

La vista del **[!UICONTROL gráfico Gantt] no está disponible para el informe de tareas**

_Informes_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] abre un informe de tareas, no aparece la opción de seleccionar una vista de [!UICONTROL gráfico Gantt] en la barra de herramientas del informe. Si se selecciona la vista de [!UICONTROL gráfico Gantt] para que aparezca por defecto en el informe, en su lugar aparece un formato de lista.

**El error de límite de caracteres no se produce en los envíos de solicitudes**

_Solicitudes_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] intenta enviar una solicitud y supera el límite de caracteres de un campo, no puede enviarla y no aparece ningún mensaje de error. En [!DNL Adobe Workfront Classic], el usuario ve la advertencia “[!UICONTROL [número] caracteres de más” y cuando intenta enviar la solicitud, ve el mensaje de error “Compruebe lo siguiente: no introduzca más de 2000 caracteres (ha introducido [número] caracteres)”].

+++

+++**Actualización de mantenimiento el 10 de junio de 2021**

**Las tareas de plantilla reordenadas no se mueven**

_Plantillas_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] arrastra una tarea de plantilla a una nueva ubicación en una lista, el número de la tarea de plantilla se actualiza, pero no se reordena.

**Tareas hijas no seleccionadas con las tareas principales**

_Plantillas_

Cuando un usuario selecciona una tarea principal en un proyecto creado a partir de una plantilla, las tareas hijas no se seleccionan automáticamente.

**La edición en línea de los hitos en una lista de tareas muestra todos los hitos**

_Proyectos_

Cuando un proyecto tiene una ruta de hitos añadida y un usuario de la nueva experiencia [!DNL Adobe Workfront] edita en línea la columna [!UICONTROL Hito: nombre] en esa lista de tareas, todas las rutas de hitos aparecen en el menú desplegable, en lugar de solo las que se han adjuntado a ese proyecto.

+++

+++**Actualización de mantenimiento el 3 de junio de 2021**

**El aviso hace que la página se sacuda**

_Informes_

Cuando un usuario de la nueva experiencia [!DNL Adobe Workfront] ejecuta un informe con un aviso, las columnas del informe se mueven rápidamente de izquierda a derecha.

**Algunas frases de la página [!UICONTROL nueva prueba] no se traducen correctamente**

_[!DNL Workfront Proof]_

Cuando un usuario navega a la página de [!UICONTROL creación de una nueva prueba] en [!DNL Workfront Proof] y el contenido se está traduciendo a un idioma que no sea el inglés, algunas frases siguen apareciendo en inglés.

**Etiquetas desactivadas y borradas añadidas a los usuarios [!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Se han añadido etiquetas de usuario [!UICONTROL desactivado] y [!UICONTROL eliminado] a las siguientes áreas en [!DNL Workfront] Proof:

* Página de [!UICONTROL detalles de la prueba]
* [!UICONTROL Vistas de prueba]
* [!UICONTROL Visor de pruebas]
* [!UICONTROL Flujos de trabajo de prueba]
* Página de [!UICONTROL imprimir comentarios]
* Página de [!UICONTROL usuario]

+++


## Actualizaciones en mayo de 2021

+++**Actualización de mantenimiento el 27 de mayo de 2021**

Visualización del calendario de **[!UICONTROL fechas de compromiso] para las actualizaciones**

_Tareas_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] está introduciendo una actualización en una tarea, el calendario de la [!UICONTROL fecha de compromiso] se muestra sin que el usuario seleccione el campo de la [!UICONTROL fecha de compromiso].

No aparece el menú **[!UICONTROL Más] en los filtros, vistas y agrupaciones**

_Listas_

Cuando un usuario en la nueva experiencia [!DNL Adobe Workfront] ve los filtros, las vistas o las agrupaciones de una lista, falta el icono del menú [!UICONTROL Más], lo que le impide compartir o eliminar (en caso de que tenga acceso) los filtros, las vistas o las agrupaciones.

**Copiar y pegar un [!UICONTROL número de referencia] de proyecto añade “[!UICONTROL Este]”**

_Proyectos_

Cuando un usuario de la nueva experiencia [!DNL Workfront] navega hasta un proyecto, copia el [!UICONTROL número de referencia] del área de [!UICONTROL visión general] y lo pega, se añade la palabra “[!UICONTROL Este]” al final del número.

Los correos electrónicos de **[!UICONTROL resumen diario] se envían cuando están desactivados**

_Notificaciones por correo electrónico_

Algunos usuarios están recibiendo notificaciones por correo electrónico de [!UICONTROL resumen diario] aunque no los hayan activado en su configuración de usuario.

**Error “El objeto ya no existe”**

_Objetos_

Cuando un usuario en la nueva experiencia [!DNL Workfront] intenta abrir ciertos objetos, ve el mensaje de error “[!UICONTROL El (objeto) ya no existe: es posible que haya escrito mal la dirección web. Vuelva a comprobarlo e introduzca la dirección de nuevo.]” El enlace del objeto sigue apareciendo en las listas, en los recientes, en los favoritos, en los resultados de las búsquedas, etc., pero no pueden acceder a él y no aparece en la papelera de reciclaje con los objetos eliminados.



+++

+++**Actualización de mantenimiento el 20 de mayo de 2021**

**No aparecen las opciones de prueba**

_Pruebas_

Cuando un usuario sube otra versión de una prueba en [!DNL Workfront], no aparecen los enlaces [!UICONTROL Abrir prueba] y [!UICONTROL Flujo de trabajo de pruebas], lo que hace que parezca que es un documento en lugar de una prueba. Cuando faltan estos enlaces, también aparece la etiqueta [!UICONTROL Pendiente] y los demás usuarios no pueden generar la prueba mientras esté [!UICONTROL Pendiente].

**Los usuarios no reciben las entregas de informes programadas**

_Informes_

Cuando algunos informes están programados para su entrega, los usuarios a veces no reciben los informes.

**No se puede eliminar el acceso para la plantilla de diseño**

_Paneles_

Cuando un usuario abre las opciones de [!UICONTROL acceso compartido] de un panel para eliminar el acceso a una plantilla de diseño, no aparece el icono [!UICONTROL Eliminar] junto a la plantilla y no puede eliminar el acceso.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 17 de mayo de 2021**

**Ahora, el panel de organización muestra correctamente el número de escenarios activos**

_[!DNL Workfront Fusion]_

Anteriormente, el panel de [!UICONTROL organización] mostraba un campo en blanco en lugar del número de escenarios en uso.

**Ahora, la navegación por el almacén de datos muestra las etiquetas de las columnas**

_[!DNL Workfront Fusion]_

Antes, las estructuras de datos que empleaban etiquetas de columna mostraban el nombre en la vista de [!UICONTROL exploración del almacén de datos]. Ahora, se muestra la etiqueta de columna. Si no se identifica ninguna etiqueta para la columna, se muestra su nombre.

**El error de inicialización del escenario ya no afecta a los datos del gancho web**

_[!DNL Workfront Fusion]_

Anteriormente, un escenario iniciado por un gancho web (incluidos los que están usando un evento en tiempo real como activador) que se encontraba con un error durante la inicialización podría resultar en la pérdida de acceso a los datos. Ahora, si se produce un error durante la inicialización del escenario (como no la imposibilidad de verificar una conexión), los datos del gancho web se mantendrán en la cola y la ejecución se reintentará automáticamente. Después de tres intentos fallidos, el escenario se desactiva y la información seguirá en la cola.

**Ahora los registros en las colas de los ganchos web se procesan en lotes más pequeños**

_[!DNL Workfront Fusion]_

Anteriormente, si un usuario activaba un escenario inactivo que tenía una cola de ganchos web asociada de muchos registros, [!DNL Workfront Fusion] intentaba procesar toda la cola en una sola ejecución (aunque con varios ciclos). En función, de la cantidad de registros procesados, esto puede hacer que la ejecución única supere el tiempo máximo de ejecución (40 minutos). Ahora, cuando active un escenario inactivo con una cola de registros asociada al gancho web, Workfront Fusion procesará hasta el número máximo de registros identificados en una sola ejecución (normalmente 2 registros por ejecución).

**Ahora, los almacenes de datos muestran los valores “0” correctamente**

_[!DNL Workfront Fusion]_

Anteriormente, los valores del almacén de datos de 0 se mostraban como vacíos. &lt;...>

+++

+++**Actualización de mantenimiento el 13 de mayo de 2021**

**El calendario desplegable aparece detrás de la cabecera de [!UICONTROL Trabajo no asignado]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario navega al [!UICONTROL Distribuidor de cargas de trabajo] en [!DNL Workfront Classic], la parte superior del selector de fechas se oculta tras la cabecera de [!UICONTROL Trabajo no asignado], lo que impide al usuario navegar a diferentes meses.

**No se puede pegar el texto en el campo de mensaje personalizado**

_[!DNL Workfront Proof]_

Nota: este problema parece afectar solo al navegador web [!DNL Google Chrome] en este momento.

Cuando un usuario está creando una nueva prueba en [!DNL Workfront Proof] e intenta pegar el texto de un correo electrónico en el campo [!UICONTROL Mensaje] de la sección de [!UICONTROL notificación por correo electrónico], no puede pegarlo.

**Se muestran campos no admitidos en el generador**

_Formularios personalizados_

Cuando un usuario está construyendo un formulario personalizado e intenta crear un campo calculado usando un campo dinámico, como [!UICONTROL Número de riesgos abiertos], el cuadro de cálculo se resalta en rojo y no le permite guardar los cambios. Los campos dinámicos no deben mostrarse en el selector de campos calculados.

**La vista previa de las tareas en la [!UICONTROL Lista de trabajos] no se carga**

_Página de inicio_

Cuando un usuario de la nueva experiencia [!DNL Workfront] se asigna a una plantilla de diseño que incluye campos personalizados en [!UICONTROL Inicio], la página no responde y no carga las tareas de la [!UICONTROL Lista de trabajos] si el usuario las selecciona.

**Los objetos de la [!UICONTROL Lista de trabajos] no se cargan en [!UICONTROL Inicio]**

_[!UICONTROL Página de inicio]_

Cuando un usuario hace clic en un objeto de la [!UICONTROL Lista de trabajos en Inicio], el encabezado del objeto aparece en el panel derecho, pero no aparecen los detalles del objeto. Finalmente, el usuario ve el mensaje “[!UICONTROL Las páginas no responden”].

**Problemas con campos de texto enriquecido en[!DNL Microsoft Outlook]**

_Integraciones de Workfront_

Cuando un usuario actualiza un campo de texto enriquecido con la integración [!DNL Workfront for Outlook], no puede:

* Retroceder
* Copiar texto
* Pegar texto
* Enviar una solicitud cuando se rellenen todos los campos

+++

+++**Actualización de mantenimiento el 6 de mayo de 2021**

El campo **[!UICONTROL Moneda] no funciona como se esperaba**

_Listas_

Cuando un usuario intenta editar en línea el campo Moneda en una lista, no puede guardar los cambios debido a los siguientes problemas:

* Listas de tareas y problemas que no permiten la entrada de símbolos de moneda
* Listas que no permiten la introducción de abreviaturas de moneda al utilizar una configuración regional que no sea el inglés
* Listas de subtareas y problemas que solo permiten la abreviación de moneda USD, independientemente de la moneda del proyecto establecida

**El nombre no se actualiza para que coincida con el nuevo nombre de la prueba**

_Documentos_

Cuando un usuario crea una nueva versión de una prueba y actualiza su nombre, el objeto documento en [!DNL Workfront] conserva el nombre original en lugar de coincidir con el nuevo nombre de la prueba.

Los botones de **[!UICONTROL caso empresarial] no funcionan cuando se adjuntan formularios personalizados**

_Proyectos_

Cuando se crea un proyecto en la nueva experiencia [!DNL Workfront] a partir de una plantilla de proyecto y hay un formulario personalizado adjunto, los usuarios no pueden enviar, rechazar o aprobar un caso empresarial.

**Visualización de pruebas archivadas en listas e informes**

_Pruebas_

Cuando un usuario ve su Lista de trabajos en [!UICONTROL Inicio] o en [!UICONTROL Mi trabajo], las pruebas que ya se han archivado aparecen en la lista. Las pruebas archivadas también aparecen en los informes y paneles.

**El proyecto creado a partir de una plantilla tiene una configuración de acceso incorrecta**

_Proyectos_

Cuando un usuario crea un proyecto a partir de una plantilla, su configuración de acceso no se traslada al nuevo proyecto creado.

**Los objetos de la [!UICONTROL Lista de trabajos] no se cargan en [!UICONTROL Inicio]**

_[!UICONTROL Página de inicio]_

Cuando un usuario hace clic en un objeto de la [!UICONTROL Lista de trabajos en Inicio], el encabezado del objeto aparece en el panel derecho, pero no aparecen los detalles del objeto. Finalmente, el usuario ve el mensaje “[!UICONTROL Las páginas no responden”].

+++


## Actualizaciones en abril de 2021

+++**Actualización de mantenimiento el 29 de abril de 2021**

La integración **[!DNL SharePoint] se autentifica usando credenciales de una integración separada**

_Integraciones de Workfront_

Cuando un usuario tiene más de una integración [!DNL SharePoint], una autentificación [!DNL SharePoint] intenta autentificarse con las credenciales de otra integración [!DNL SharePoint].

**No se pueden cargar o exportar archivos de [!DNL Adobe] productos**

_Integraciones de Workfront_

Cuando un usuario intenta subir o exportar archivos usando la integración [!DNL Workfront for Adobe Creative Cloud], ve el mensaje de error “[!UICONTROL No se puede leer la propiedad “stages” de undefined]” y no puede subir o exportar los archivos.

**Los archivos no son visibles en [!DNL Internet Explorer]**

_Documentos_

Cuando un usuario con un navegador [!DNL Internet Explorer] navega al área de [!UICONTROL Documentos] de un objeto, la pantalla de [!UICONTROL Documentos] está en blanco y no carga los archivos. Para algunos usuarios, la pantalla sí carga algunos archivos, pero el número de archivos que aparecen no coincide con el que aparece junto a la sección de [!UICONTROL Documentos].

+++

+++**Actualización de mantenimiento el 22 de abril de 2021**

**Tareas agregadas en el orden incorrecto**

_Plantillas_

Cuando un usuario agrega una tarea a una plantilla, la tarea no recibe el número que espera y se añade en el lugar incorrecto.

**Ahora, las pruebas se combinan en un solo correo electrónico**

_Pruebas_

Ahora, [!DNL Workfront] envía un solo correo electrónico para las pruebas combinadas en lugar de enviar un correo electrónico para cada archivo incluido.
+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 15 de abril de 2021**

**Error “[!UICONTROL Escenario rechazado]” al ejecutar un escenario**

_[!DNL Workfront Fusion]_

Cuando un usuario intenta ejecutar un escenario, este no se ejecuta y el usuario recibe el mensaje “[!UICONTROL Escenario rechazado]”.

+++

+++**Actualización de mantenimiento el 15 de abril de 2021**

El **[!UICONTROL Distribuidor de cargas de trabajo] muestra horas planificadas incorrectas**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario ve las horas planificadas de una tarea en el [!UICONTROL Distribuidor de cargas de trabajo], el valor de las horas no coincide con las asignadas a la tarea.

**La barra de navegación superior no es visible en [!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Cuando un usuario navega a cualquier página de [!DNL Workfront Proof] que no sea la del panel, la barra de navegación superior desaparece. El usuario no puede acceder a las funciones de la barra de navegación, como la configuración de su cuenta o su perfil.

**Mejora de los formularios personalizados**

_Formularios personalizados_

Para una mejor experiencia al rellenar un formulario personalizado, hemos mejorado la forma en que se muestran las etiquetas largas de los campos personalizados. Cuando hay suficiente espacio horizontal para mostrarlas en su totalidad, ya no se truncan.

+++

+++**Actualización de mantenimiento el 8 de abril de 2021**

**No se pueden crear pruebas en la [!DNL Adobe Creative Cloud] integración**

_Integraciones de Workfront_

Cuando un usuario intenta crear una prueba directamente desde el [!DNL Adobe Creative Cloud], la prueba no se genera.

+++

+++**Actualización de mantenimiento el 1 de abril de 2021**

**Problemas de visualización del panel de resumen en [!DNL Chrome]**

_[!UICONTROL Resumen]_

Cuando un usuario abre el panel de [!UICONTROL resumen] mientras usa el navegador [!DNL Chrome], la interfaz de usuario del panel de resumen no se comporta como se espera. El usuario no puede desplazarse, los iconos pueden desaparecer y los contenidos pueden superponerse.

El área de **[!UICONTROL equipos] en la [!UICONTROL configuración] no muestra todos los equipos**

_[!UICONTROL Configurar]_

Cuando un administrador va al área de [!UICONTROL Equipos] de la [!UICONTROL Configuración], solo puede ver los equipos que ha creado. Los equipos creados por otros administradores no son visibles.

**No es posible añadir actualizaciones al proyecto en estado [!UICONTROL Pendiente de aprobación]**

_Proyectos_

Si un usuario intenta añadir una actualización a un proyecto en estado [!UICONTROL Pendiente de aprobación] y no es el usuario que tiene asignado aprobar el proyecto, la actualización no se añade y aparece el siguiente aviso:

No se puede editar un proyecto con un estado “[!DNL Pending Approval]”. Puede modificar el proyecto si cambia el estado.

+++


## Actualizaciones en marzo de 2021

+++**Actualización de mantenimiento el 26 de marzo de 2021**

**Los botones de un caso empresarial se muestran incorrectamente**

_Proyectos_

Cuando un usuario está viendo un caso empresarial y la ventana está en modo de pantalla completa, los botones [!UICONTROL Guardar] y [!UICONTROL Cancelar] aparecen cerca del centro de la pantalla, superponiéndose a los elementos del caso empresarial.

**No se puede cambiar la clasificación de un informe**

_Informes_

Cuando un usuario intenta cambiar la ordenación de un informe en la nueva experiencia [!DNL Workfront], la ordenación no cambia respecto a la seleccionada cuando se creó el informe.

**El uso compartido está desactivado en las nuevas pruebas**

_[!DNL Workfront Proof]_

Cuando un usuario que tiene activado el [!UICONTROL uso compartido público] en su configuración de pruebas por defecto crea una prueba, esta se crea con el uso compartido desactivado. Los demás usuarios no pueden ver el botón [!UICONTROL Compartir] ni compartir la prueba.

**Error “[!UICONTROL No se ha podido generar la prueba]” al crearla**

_[!DNL Workfront Proof]_

Cuando un usuario intenta crear una prueba, esta no se crea y aparece el siguiente mensaje de error:

“[!UICONTROL No se ha podido generar la prueba. Error interno]”

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 25 de marzo de 2021**

**Se ha eliminado la colección redundante o el campo de referencia del panel de asignación**

_[!DNL Workfront Fusion]2.0_

Cuando un usuario usa un término de la API [!DNL Workfront] para seleccionar un campo de colección o de referencia para incluirlo en la salida de un módulo [!DNL Workfront], la salida muestra ese campo con dos puntos (como [!UICONTROL owner:name]), y también en los atributos (name es un campo bajo owner). El campo etiquetado con dos puntos no contiene datos, y proporciona datos incorrectos si se asigna a un módulo más adelante en el escenario.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 18 de marzo de 2021**

**Ahora, los ajustes de las plantillas de proyectos se aplican a los proyectos creados a través de [!DNL Workfront Fusion] 2.0**

_[!DNL Workfront Fusion]2.0_

Al crear un proyecto a partir de una plantilla mediante [!DNL Workfront Fusion] 2.0, los ajustes de la plantilla se aplican al nuevo proyecto. Este comportamiento es el mismo cuando se crea un proyecto a partir de una plantilla en la aplicación [!DNL Workfront].

+++

+++**Actualización de mantenimiento el 18 de marzo de 2021**

**Ahora, los ajustes de las plantillas de proyectos se aplican a los proyectos creados a través de la API**

_[!DNL Workfront]API_

Al crear un proyecto a partir de una plantilla mediante la API [!DNL Workfront], los ajustes de la plantilla se aplican al nuevo proyecto. Este comportamiento es el mismo cuando se crea un proyecto a partir de una plantilla en la aplicación [!DNL Workfront].

+++

+++**Actualización de mantenimiento (Hot Fix) el 15 de marzo de 2021**

**El componente compartido no funciona como se esperaba**

_[!DNL Workfront Proof]_

Si las cuentas independientes de [!DNL Workfront Proof] se trasladan a un componente compartido, puede ocurrir lo siguiente cuando un usuario añade una nueva versión de una prueba o documento:

* El usuario no puede eliminar la prueba de [!UICONTROL Studio Proof].
* El mensaje por defecto no aparece en la nueva versión.

**El uso compartido de enlaces públicos no está habilitado en la nueva versión de una prueba**

_Documentos_

Cuando un usuario activa el uso compartido de enlaces públicos en una prueba y luego sube una nueva versión de la prueba, el uso compartido de enlaces públicos no se activa automáticamente.

No aparecen los botones **[!UICONTROL Aprobar], [!UICONTROL Cambios] y [!UICONTROL Rechazar] en la prueba**

_[!DNL Workfront Proof]_

Cuando un usuario ve una prueba en el Visor de pruebas, los botones [!UICONTROL Aprobar], [!UICONTROL Cambios] y [!UICONTROL Rechazar] no aparecen en la parte superior de la pantalla.

**No se puede cambiar la clasificación de un informe**

_Informes_

Cuando un usuario intenta cambiar la ordenación de un informe en la nueva experiencia [!DNL Workfront], la ordenación no cambia respecto a la seleccionada cuando se creó el informe.

**El mensaje personalizado en la prueba no se traslada a la nueva versión**

_[!DNL Workfront Proof]_

Cuando un usuario adjunta un mensaje personalizado a una prueba y luego sube una nueva versión de esa prueba, no aparece el mensaje personalizado.

**No aparece la lista de usuarios**

_Listas_

Cuando un usuario intenta ver una lista de usuarios que incluye la columna “[!UICONTROL Iconos de estado]”, la lista no se muestra.

**La opción “[!UICONTROL Notificar a los destinatarios sobre esta prueba]” está desactivada independientemente de la configuración del flujo de trabajo**

_[!DNL Workfront Proof]_

Cuando un usuario crea una nueva prueba y no activa manualmente la opción “[!UICONTROL Notificar a los destinatarios sobre esta prueba]”, no se notifica al destinatario. Esto ocurre aunque la opción esté habilitada en la configuración del flujo de trabajo.

**No se puede cambiar el lapso de tiempo**

_[!UICONTROL Análisis mejorado]_

Cuando un usuario ve los [!UICONTROL análisis mejorados] y hace clic en el calendario para ajustar el intervalo de fechas, las fechas no cambian.

**No se puede descargar un documento compartido públicamente**

_Documentos_

Cuando un usuario hace clic en un enlace compartido para descargar un documento, este no se descarga y aparece un error del explorador que indica que la página no existe.

+++

+++**Actualización de mantenimiento el 11 de marzo de 2021**

**Sección del formulario personalizado que no se exporta para los no administradores**

_Formularios personalizados_

Si un formulario personalizado adjunto a un objeto tiene un salto de sección que requiera algo más que el acceso “[!UICONTROL Ver]” necesario para ver el contenido de la sección, nadie que no sea un administrador podrá exportar el contenido de la sección.

**El documento descargado tiene un nombre incorrecto**

_[!DNL Workfront Proof]_

Cuando un usuario descarga un documento del [!UICONTROL Visor de pruebas], el documento tiene el nombre de una versión anterior, no la versión que se ha descargado.

+++

+++**Actualización de mantenimiento el 4 de marzo de 2021**

**Error al acceder a la plantilla de diseño**

_Plantillas de diseño_

Cuando un usuario inscrito en la nueva experiencia [!DNL Workfront] cambia a la experiencia [!DNL Classic] e intenta acceder a una plantilla de diseño de [!DNL Classic], ve el error “[!UICONTROL Esa página no existe]”.

**No se pueden editar los filtros en el [!UICONTROL Distribuidor de cargas de trabajo]**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario intenta editar un filtro en el [!UICONTROL Distribuidor de cargas de trabajo], el generador de filtros no se abre.

**El enlace “[!UICONTROL Ver todas las notificaciones]” en la notificación por correo electrónico redirige a una página incorrecta**

_Notificaciones por correo electrónico_

Cuando un usuario hace clic en el enlace “[!UICONTROL Ver todas las notificaciones]” de una notificación por correo electrónico, se le redirige a una página con el siguiente mensaje:

“[!UICONTROL El usuario ya no existe. Es posible que haya escrito mal la dirección web. Compruébela e intente introducir de nuevo la dirección.]”

**El usuario no es dirigido al comentario de prueba en el que está etiquetado**

_Notificaciones por correo electrónico_

Cuando se etiqueta a un usuario en un comentario de prueba y hace clic en el enlace [!UICONTROL Ir a la prueba] en una notificación por correo electrónico, se le dirige a la prueba pero no al comentario específico. Si el usuario está en [!DNL Workfront Classic], se le dirige a la página de [!UICONTROL detalles del documento] en lugar de al comentario de la prueba.

**Los usuarios añadidos al escenario [!DNL Workfront] reciben notificaciones por correo electrónico**

_[!DNL Workfront Proof]_

Cuando un usuario que no está en el flujo de trabajo abre una prueba desde [!DNL Workfront], el sistema crea automáticamente una etapa, añade al usuario a la prueba y envía una notificación por correo electrónico de [!UICONTROL Nueva prueba].

**El panel de resumen del documento se oscurece y las acciones dejan de estar disponibles**

_Documentos_

Cuando un usuario está en una página de documento y pasa el ratón por encima del panel de resumen del documento, el panel oscurece y puede mostrar otros botones. El usuario no puede hacer clic en las acciones del panel de resumen.

**Actualización de los cambios de rendimiento del flujo**

_Actualización del flujo_

Hemos reducido el número máximo de actualizaciones que aparecen en la pestaña [!UICONTROL Actualizaciones] de 50 a 25 para mejorar el rendimiento.

+++

+++**Actualización de mantenimiento (Hot Fix) el 1 de marzo de 2021**

**No se envían nuevos correos electrónicos de pruebas**

_[!DNL Workfront Proof]_

NOTA: Este problema se solucionó en la nueva experiencia [!DNL Workfront] el 26 de febrero de 2021.
Se solucionó en la experiencia [!DNL Classic] el 1 de marzo de 2021.

Cuando un usuario crea una nueva prueba y activa la opción [!UICONTROL Notificar a los destinatarios sobre esta prueba], no se envía ningún correo electrónico para notificarlos.

+++


## Actualizaciones en febrero de 2021

+++**Actualización de mantenimiento el 25 de febrero de 2021**

La herramienta **[!UICONTROL Programación] no se carga en ninguna zona**

_Administración de recursos_

Cuando un usuario con un apóstrofe en su nombre de usuario intenta acceder a la herramienta de [!UICONTROL programación] en [!DNL Workfront Classic], la página está en blanco y la herramienta no se carga.

**El nombre no cambia en las nuevas versiones de prueba**

_Documentos_

Cuando un usuario en la nueva experiencia [!DNL Workfront] sube una nueva versión de un documento con un nombre diferente, no se actualiza para coincidir con el de la nueva versión.

Error en el **[!UICONTROL uso compartido de documentos] al eliminar proyectos**

_Proyectos_

Cuando un usuario administrador del sistema tiene acceso a un proyecto que se ha copiado y trata de eliminarlo o de borrar un documento del proyecto, no puede eliminar el objeto y ve el error “[!UICONTROL Documento compartido con valor(es) de clave primaria no encontrado(s)]”.

**El informe del usuario no está aplicando todos los filtros**

_Informes_

Cuando un usuario de la nueva experiencia [!DNL Workfront] crea un informe de usuario con una regla de filtrado que incluye el campo [!UICONTROL Identificador de elemento principal superior], no se aplican las demás reglas de filtrado del informe.

**Los campos calculados no se recalculan después de las ediciones**

_Formularios personalizados_

Cuando un usuario de la nueva experiencia [!DNL Workfront] edita y guarda un formulario personalizado que contiene campos calculados, estos no se actualizan.

**Se borran documentos al eliminar el formulario personalizado**

_Formularios personalizados_

Cuando un usuario de la nueva experiencia [!DNL Workfront] elimina el formulario personalizado de un documento que está adjunto a los documentos, estos también se eliminan.

+++

+++**Actualización de mantenimiento el 18 de febrero de 2021**

**Casilla de verificación innecesaria eliminada del área de [!UICONTROL Solicitudes]**

_Solicitudes_

Hemos eliminado la casilla de verificación a la izquierda de los nombres de las solicitudes en la lista de Enviados del área de [!UICONTROL Solicitudes]. Esta casilla de verificación no estaba conectada a ninguna funcionalidad, por lo que se ha eliminado para evitar una experiencia confusa.

**No se puede acceder a los documentos desde los enlaces**

_Documentos_

Cuando un usuario en la nueva experiencia [!DNL Workfront] hace clic en algunos enlaces de documentos, no puede acceder al documento y ve el mensaje de error “[!UICONTROL El documento ya no existe: es posible que haya escrito mal la dirección web. Vuelva a comprobarlo e introduzca la dirección de nuevo.]” Este mismo error se produce con el enlace [!UICONTROL Ver detalles] en las notificaciones de correo electrónico de prueba.

+++

+++**Actualización de mantenimiento de Workfront Fusion el 16 de febrero de 2021**

**[!DNL Workfront Fusion] 2.0 muestra zonas horarias inexactas**

_Escenarios_

Esta actualización ha solucionado un problema por el [!DNL Fusion] 2.0 mostraba las zonas horarias de los usuarios de forma inexacta. Ahora los usuarios pueden ver su zona horaria en los campos de entrada de las fechas.

+++

+++**Actualización de mantenimiento el 11 de febrero de 2021**

**Las pruebas no se cargan en la carpeta seleccionada**

_[!DNL Workfront Proof]_

Cuando un usuario abre una carpeta y añade una nueva prueba, esta se carga en el área general de [!UICONTROL Documentos] del objeto en lugar de dentro de la carpeta.

**Demasiadas páginas ancladas hacen que la navegación superior desaparezca**

_Exploración_

Cuando un usuario tiene más de 60 páginas ancladas, la navegación superior deja de mostrarse, lo que impide al usuario acceder a la [!UICONTROL Búsqueda], al [!UICONTROL Menú principal], a las [!UICONTROL Notificaciones], etc.

**El usuario no puede escribir texto en el campo de texto enriquecido**

_Listas_

Cuando un usuario intenta editar en línea un campo de texto enriquecido, solo puede escribir un carácter individual.

+++

+++**Actualización de mantenimiento el 4 de febrero de 2021**

**El informe exportado muestra la [!DNL Workfront Classic] marca**

_Informes_

Cuando un usuario de la nueva experiencia de Workfront exporta un informe, el logotipo que aparece en el informe exportado coincide con la configuración de [!DNL Workfront Classic]que se encuentra en [!UICONTROL Configuración] > [!UICONTROL Sistema] > [!UICONTROL Marca].

+++


## Actualizaciones en enero de 2021

+++**Actualización de mantenimiento el 28 de enero de 2021**

**Los comentarios no muestran “[!UICONTROL en nombre de]”**

_Actualizaciones_

Cuando un administrador de [!DNL Workfront] se conecta como otro usuario y responde a un comentario en el área de [!UICONTROL Actualizaciones] de un objeto, no aparece el texto “[!UICONTROL en nombre de]” antes del nombre de usuario.

**No se puede adjuntar un documento**

_Solicitudes_

Cuando un usuario en la nueva experiencia [!DNL Workfront] intenta añadir un documento a una nueva solicitud de un proveedor de documentos externo, la lista de [!UICONTROL documentos] no se carga, lo que impide al usuario seleccionar el documento y completar la solicitud.

**La anchura de la pantalla se expande a la derecha, lo que provoca problemas de navegación**

_[!UICONTROL Calendario principal]_

Cuando un usuario en la nueva experiencia [!DNL Workfront] abre el [!UICONTROL Calendario principal] y tiene elementos pendientes en algunas semanas, la pantalla se expande hacia la derecha, lo que le impide ver la semana completa. Si el usuario selecciona un elemento para abrir el panel de [!UICONTROL detalles] en este estado y quiere ver los detalles de otro elemento, tiene que desplazarse hacia la izquierda, lo que cierra el panel de [!UICONTROL detalles].

**Se ha corregido la etiqueta del proceso de aprobación de uso único**

_Proyectos_

Cuando se usa un proceso de aprobación de un solo uso para un proyecto en la nueva experiencia [!DNL Workfront], ahora se muestra como “[!UICONTROL Proceso de aprobación de un solo uso]” en lugar de “&lt;Custom>” en el cuadro [!UICONTROL Editar proyecto]. Esto aún no está disponible para tareas y problemas.

**Se ha mejorado la apariencia de los formularios personalizados**

_Proyectos_

Hemos mejorado la apariencia a la hora de trabajar con formularios personalizados en la nueva experiencia [!DNL Workfront] para proyectos.

**Ahora, la funcionalidad de la API para la moneda del proyecto coincide con la funcionalidad de la aplicación**

_Proyectos_

No se puede cambiar la moneda de un proyecto cuando ya contiene información financiera Con la última actualización de mantenimiento, la funcionalidad de la API para este caso coincide ahora con la experiencia en la interfaz de [!DNL Workfront].

**No genera automáticamente la semana siguiente**

_Hojas de horas_

Cuando un usuario navega al área de [!UICONTROL Plantillas de horas], solo ve la correspondiente a la semana actual. La plantilla de horas de las próximas semanas no se genera automáticamente.

+++

+++**Actualización de mantenimiento el 21 de enero de 2021**

**Al ordenar manualmente por una columna, se muestran todos los resultados**

_Informes_

Cuando un usuario de la nueva experiencia [!DNL Workfront] hace clic en una barra del gráfico de un informe y, a continuación, hace clic en la cabecera de una columna para ordenar manualmente los resultados de esa agrupación, se muestran todos los resultados del informe, no solo los de la agrupación originalmente seleccionada.

**Cambios en la configuración de “[!UICONTROL Permitir el uso compartido de la prueba a través de una URL o un código incrustado]”**

_[!DNL Workfront Proof]_

Cuando un usuario crea una prueba y desmarca el ajuste [!UICONTROL Permitir el uso compartido de la prueba a través de una URL o un código incrustado], el ajuste se vuelve a comprobar después de generar la prueba. Si el usuario deja el ajuste marcado, se desmarca después de generar la prueba.

Los usuarios de **[!DNL Mac] no pueden pegar en campos de texto en el visor de pruebas**

_[!DNL Workfront Proof]_

Cuando un usuario intenta pegar texto en ciertos campos del visor de pruebas, el texto no aparece en el campo.

+++

+++**Actualización de mantenimiento el 14 de enero de 2021**

**No se puede actualizar la configuración de las notificaciones por correo electrónico**

_Configurar_

Cuando un usuario intenta actualizar la configuración de las [!UICONTROL notificaciones por correo electrónico], no puede acceder al área de notificaciones por correo electrónico y ve el mensaje de error “[!UICONTROL Intentémoslo de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo]”.

El **[!UICONTROL gráfico Gantt] hace que algunos campos se trunquen**

_Listas_

Cuando un usuario abre el [!UICONTROL gráfico Gantt] en algunas áreas de la lista, ciertos campos, como la [!UICONTROL Descripción], truncan el texto. El usuario debe hacer doble clic en el campo para ver el texto completo.

**No se pueden enviar archivos desde [!UICONTROL Detalles del documento]**

_Documentos_

Cuando un usuario de la nueva experiencia [!DNL Workfront] intenta enviar un documento desde la página de [!UICONTROL detalles del documento], ve el mensaje de error “[!UICONTROL Se ha producido un error. Estamos trabajando para resolverlo. Para continuar con su trabajo, intente actualizar esta página del explorador]”.

+++

+++**Actualización de mantenimiento el 7 de enero de 2021**

**Se cierra el cuadro de diálogo Delegar aprobaciones**

_Página de inicio_

Cuando un usuario intenta delegar aprobaciones en [!UICONTROL Inicio] y hace clic en cualquier fecha, el diálogo se cierra sin seleccionar la fecha ni permitir al usuario completar la delegación.

**Problema al mover un documento a una tarea**

_Documentos_

Cuando un usuario intenta mover un documento o una prueba en la nueva experiencia [!DNL Workfront], algunas tareas fuera del proyecto no enumeran el proyecto principal como se esperaba.

**El PDF descargado tiene un nombre incorrecto**

_[!DNL Workfront Proof]_

Cuando un usuario recibe un enlace de descarga por correo electrónico ([!UICONTROL Prueba] > [!UICONTROL Imprimir comentarios] > [!UICONTROL PDF]) y exporta el archivo, el archivo descargado se titula con números aleatorios en lugar del ID de la prueba.

+++
