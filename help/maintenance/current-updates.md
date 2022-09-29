---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 4db776a758d437a6f08bb088a5ad8fa11f4d8211
workflow-type: tm+mt
source-wordcount: '13519'
ht-degree: 3%

---

# [!DNL Workfront] Actualizaciones de mantenimiento

En 2022 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. [!DNL Workfront] El servicio de asistencia técnica le avisará cuando haya solucionado un problema que haya enviado.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Para ver las actualizaciones de mantenimiento anteriores a 2022, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones de septiembre de 2022

+++**Actualización de mantenimiento el 29 de septiembre de 2022**

**El usuario no vuelve a la página anterior al cerrar la prueba**

*Pruebas*

Cuando un usuario que está viendo una prueba en [!DNL Workfront] cierra la prueba, no devuelve la página en la que se encontraba antes de abrirla. En su lugar, se les redirige a otra página de [!DNL Workfront].

**No se puede abrir la prueba en[!DNL Workfront]**

*Pruebas*

Cuando un usuario está viendo un documento en [!DNL Workfront] e intenta abrir la prueba, la prueba no se abre y el usuario vuelve al [!UICONTROL Detalles del documento] página.

**Las horas no se guardan al utilizar [!UICONTROL Tabulación] key**

*Hojas de horas*

Cuando un usuario rellena una hoja de tiempo y navega entre celdas con la variable [!UICONTROL Tabulación] , las horas no se guardan. La variable [!UICONTROL Guardar automáticamente] la notificación no aparece en la parte inferior de la pantalla y, si el usuario actualiza la página, puede ver las horas que no se guardaron.

**Páginas en blanco al ver una prueba con varias páginas**

*[!DNL Workfront Proof]*

Cuando un usuario ve una prueba con varias páginas, puede ver miniaturas de las páginas, pero estas no se abren en el visor principal.



+++

+++**Actualización de mantenimiento el 22 de septiembre de 2022**

**No se puede cerrar la tarjeta de usuario en el flujo de actualización**

*Actualizaciones*

Cuando un usuario está viendo actualizaciones y pasa el ratón por encima de un nombre, se abre una tarjeta con detalles sobre el usuario cuyo nombre se abre y no se cierra automáticamente. La página no responde hasta que la tarjeta se cierre manualmente haciendo clic en la X en la esquina superior derecha.

+++

+++**Actualización de mantenimiento el 15 de septiembre de 2022**

**&quot;[!UICONTROL Alguien más intentó guardar este proyecto]&quot; error al introducir horas**

*Hojas de horas*

Cuando un usuario intenta registrar horas en una tarea de su parte de horas, las horas no se guardan automáticamente y ve el siguiente error:

&quot;[!UICONTROL Lo lamentamos, no se pudo guardar debido a que otro usuario intentó guardar el proyecto al mismo tiempo. Intente guardar de nuevo.]&quot;

**No se puede cerrar la tarjeta de usuario en el flujo de actualización**

*Actualizaciones*

Cuando un usuario está viendo actualizaciones y pasa el ratón por encima de un nombre, se abre una tarjeta con detalles sobre el usuario cuyo nombre se abre y no se cierra automáticamente. La página no responde hasta que la tarjeta se cierre manualmente haciendo clic en la X en la esquina superior derecha.

**La variable[!UICONTROL Asignación de funciones de tarea]&quot; se ha cambiado el nombre del campo a &quot;[!UICONTROL Asignación de funciones]&quot; al asignar trabajo de forma masiva mediante la variable [!UICONTROL Equilibrador de carga de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Para reflejar la nueva funcionalidad de poder asignar tareas y problemas de forma masiva desde la variable [!UICONTROL Trabajo no asignado] , se ha cambiado el nombre de &quot;[!UICONTROL Asignación de funciones de tarea]&quot; campo a &quot;[!UICONTROL Asignación de funciones]&quot; en el [!UICONTROL Equilibrador de carga de trabajo]. El campo hace referencia a las funciones de trabajo que se han asignado a tareas o problemas y se muestra al asignar usuarios a elementos en la variable [!UICONTROL Asignaciones masivas] en la ventana

+++

+++**[!DNL Workfront Scenario Planner]Actualización de mantenimiento el 15 de septiembre de 2022**

**El filtro compartido con un grupo ahora se muestra en la sección [!DNL Scenario Planner]&#39;s  [!UICONTROL Importar proyectos] lista de miembros de todos los subgrupos**

*[!DNL Workfront Scenario Planner]*

Ahora, cuando comparte un filtro de proyecto con un grupo que tiene subgrupos adicionales, el filtro es visible para todos los miembros de grupo y subgrupo que ven proyectos en la variable [!UICONTROL Importar proyectos] en la [!DNL Scenario Planner].

+++

+++**Actualización de mantenimiento el 8 de septiembre de 2022**

**Nombres actualizados revertidos para los campos de asignación de usuarios y funciones**

*Asignaciones*

Los campos de asignación cuyo nombre cambió temporalmente a la semana pasada se han revertido a sus nombres originales:

* [!UICONTROL Usuarios de asignación]
* [!UICONTROL Roles de asignación]

**Error al quitar el propietario del proyecto del encabezado**

*Proyectos*

Cuando un usuario intenta eliminar un [!UICONTROL Propietario del proyecto] desde el encabezado de un proyecto, la variable [!UICONTROL Propietario del proyecto] no se elimina y el usuario ve el siguiente mensaje de error:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Redimensionado [!UICONTROL Descripción] vuelve al tamaño original**

*Proyectos, tareas y problemas*

Cuando un usuario cambia el tamaño de la variable [!UICONTROL Descripción] en el área de detalles de un elemento de trabajo para agrandarlo, después empieza a escribir en el cuadro, el cuadro vuelve a su tamaño original. El usuario puede seguir escribiendo en el cuadro y el contenido se guarda según lo esperado

**Salida involuntaria al crear tareas o problemas**

*Tareas y problemas*

Cuando un usuario crea una tarea o un problema en un proyecto y hace clic fuera de la ventana emergente de creación, la ventana emergente se cierra sin previo aviso y se pierde toda la información introducida anteriormente.

**Se ha eliminado la capacidad de enviar una prueba por correo electrónico a una zona de colocación**

*[!DNL Workfront Proof]*

Desde el jueves 8 de septiembre de 2022, hemos eliminado la capacidad de enviar una prueba por correo electrónico a una zona de colocación independiente [!DNL Workfront Proof] producto.

Puede seguir utilizando las zonas de colocación de otros modos para enviar nuevas pruebas y nuevas versiones de pruebas a su cuenta sin tener que iniciar sesión en su cuenta. Consulte [Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) para obtener más información.

+++

+++**Actualización de mantenimiento el 6 de septiembre de 2022**

**Fechas proyectadas agregadas a la lista de campos para encabezados de proyecto personalizables**

*Proyectos*

Hemos añadido la variable [!UICONTROL Fecha inicial prevista] y [!UICONTROL Fecha de finalización prevista] a la lista de campos para encabezados de proyecto personalizables al utilizar una plantilla de diseño.

**Nuevo límite con un mensaje de confirmación que muestra el número de elementos agregados a un parte de horas**

*Hojas de horas*

Cuando selecciona más de 50 elementos para agregarlos a un parte de horas, ahora recibe un mensaje de confirmación que muestra el número de elementos que se agregarán al parte de horas y le da la oportunidad de cambiar de curso y no de agregar todos los elementos. Todos los elementos añadidos se anclan automáticamente en el parte de horas y deberán eliminarse manualmente de las hojas de horas actuales y futuras.

+++

+++**Actualización de mantenimiento el 2 de septiembre de 2022**

Agregue la variable [!UICONTROL Integraciones] al encabezado personalizado del proyecto

*Integraciones*

Ahora puede agregar la variable [!UICONTROL Integraciones] al encabezado personalizado de un proyecto cuando se utiliza una plantilla de diseño. Una vez añadido, el campo muestra un vínculo a un elemento externo vinculado al proyecto que se encuentra en [!DNL Salesforce] o [!DNL Anaplan], según la integración.

>[!NOTE]
>
>Esta actualización de mantenimiento se publicó anteriormente en el entorno Vista previa el 25 de agosto de 2022 y ahora se encuentra en producción.

+++

+++**Actualización de mantenimiento el 1 de septiembre de 2022**

**Elementos completados eliminados de la delegación**

*Delegaciones*

Ahora, solo los elementos incompletos cuyas fechas coincidan con las fechas de una delegación se delegarán a otros usuarios cuando se inicie la delegación de elementos de trabajo. Si los artículos se completaron antes de que comenzara la delegación, no se delegarán. Los elementos que se completen durante el período de tiempo de delegación permanecerán en la lista de trabajo del área principal durante dos semanas, tanto para el delegado como para el cesionario, antes de que se eliminen automáticamente, si la delegación no ha finalizado durante esas semanas.

**Actualizaciones de metadatos para [!DNL Adobe Workfront] para [!DNL Experience Manager Assets] y [!DNL Assets Essentials] integraciones**

*Integraciones*

Los metadatos se insertan automáticamente al agregar un recurso a una carpeta vinculada.

Anteriormente, los metadatos solo se insertaban cuando se agregaba un recurso mediante la función [!UICONTROL Agregar nuevo] menú desplegable.

**No se pueden aprobar ni rechazar horas en un problema**

*Problemas*

Cuando un usuario intenta aprobar o rechazar horas en la [!UICONTROL Horas] de un problema, la pestaña [!UICONTROL Aprobar] y [!UICONTROL Rechazar] faltan botones.

**La conversión de un problema en un proyecto mediante una plantilla muestra un mensaje de error incorrecto**

*Problemas*

Al convertir un problema en un proyecto mediante una plantilla y se produce un error, se muestra al usuario una página con el mensaje &quot;[!UICONTROL El proyecto ya no existe]&quot; en lugar del mensaje de error correcto que explica la causa del error de conversión.

**No se puede crear la prueba para archivos de más de 1,5 GB**

*[!DNL Workfront Proof]*

Al crear una prueba nueva, si un usuario carga un archivo de más de 1,5 GB, el nombre del archivo se pondrá rojo y no se podrá crear la prueba.

+++

## Actualizaciones de agosto de 2022

+++**Actualización de mantenimiento el 25 de agosto de 2022**

**Los vínculos del equilibrador de carga de trabajo se muestran incorrectamente en los tableros**

*Paneles*

Los vínculos del equilibrador de carga de trabajo compartible se muestran incorrectamente cuando se añaden a un tablero como una página externa. En lugar de utilizar la vista o los filtros exclusivos asociados al vínculo, el panel utiliza la vista o los filtros aplicados más recientemente al equilibrador de carga de trabajo.

**Agregue la variable [!UICONTROL Integraciones] al encabezado personalizado del proyecto**

*Proyectos*

Ahora puede agregar la variable [!UICONTROL Integraciones] al encabezado personalizado de un proyecto cuando se utiliza una plantilla de diseño. Una vez añadido, el campo muestra un vínculo a un elemento externo vinculado al proyecto que se encuentra en [!DNL Salesforce] o [!DNL Anaplan], según la integración.

>[!NOTE]
>
>Actualmente, esta actualización de mantenimiento solo se encuentra en el entorno de Vista previa. Se lanzará a Producción una semana después de la versión de Vista previa.

**Los datos personalizados no se conservan al convertir un problema en un proyecto en blanco**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto en blanco (sin plantilla), los datos de los campos calculados no se transfieren al nuevo proyecto.

**Error &quot;Modo de planificación de cronología&quot; al cambiar una fecha de un proyecto**

*Proyectos*

Cuando un usuario intenta cambiar una fecha en un proyecto que tiene la variable [!UICONTROL Modo de plan] configure como [!UICONTROL Guardar manualmente] > [!UICONTROL Planificación de la cronología], la fecha no cambia y el usuario ve un error.

&quot;[!UICONTROL El modo de planificación de línea de tiempo solo está disponible cuando se carga la fecha de la línea de tiempo. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

**Coherencia al abrir el equilibrador de carga de trabajo mediante la vista Mes**

*Distribuidor de cargas de trabajo*

Ahora, el equilibrador de carga de trabajo muestra los elementos asignados por los usuarios expandidos al mostrarlos en el [!UICONTROL Día], [!UICONTROL Semana]o [!UICONTROL Mes] vistas. Antes de esta actualización, los elementos asignados se mostraban expandidos para la variable [!UICONTROL Día] y [!UICONTROL Semana] vistas y contraído para [!UICONTROL Mes] vista.


+++

+++**Actualización de mantenimiento el 18 de agosto de 2022**

**&quot;[!UICONTROL Agregar a iteración]&quot; y &quot;[!UICONTROL Agregar a Kanban Board]&quot; opciones no disponibles cuando se editan tareas en línea en un informe**

*Informes*

Cuando un usuario está viendo una lista de tareas en un informe y abre el [!UICONTROL Más] (tres puntos), el[!UICONTROL Agregar a iteración]&quot; y &quot;[!UICONTROL Agregar a Kanban Board]&quot; no están disponibles en la lista desplegable. Si el informe se ve en un tablero, la variable[!UICONTROL Agregar a iteración]&quot; y &quot;[!UICONTROL Agregar a Kanban Board]&quot; están disponibles en la lista desplegable.

**Los informes de matriz se muestran incorrectamente al desplazarse**

*Informes*

Cuando un usuario está viendo un informe de matriz y se desplaza, algunos elementos visuales del informe pueden superponerse o duplicarse.

**[!UICONTROL Milestone] vista eliminada de la lista de proyectos Hojas de horas**

*Hojas de horas*

La variable [!UICONTROL Milestone] se ha eliminado de la lista de proyectos de parte de horas al agregar un proyecto.

**Los hipervínculos de una prueba interactiva no están activos**

*[!DNL Workfront Proof]*

Cuando un usuario está viendo una prueba interactiva y hace clic en un vínculo o en un botón que contiene un vínculo, no se le redirige a la página a la que está vinculado el vínculo o el botón.

**Nuevos campos de texto que faltan en la página de prueba**

*[!DNL Workfront Proof]*

En el [!DNL New Proof] , no se muestran muchos campos de texto (incluidas etiquetas de campo, opciones desplegables y nombres de casilla de verificación).

**Los usuarios no reciben notificaciones cuando están etiquetados en una prueba**

*[!DNL Workfront Proof]*

Cuando un usuario está etiquetado en un comentario de prueba, no recibe una notificación por correo electrónico sobre el comentario.

+++

+++**Actualización de mantenimiento el 12 de agosto de 2022**

**Nuevo campo de encabezado personalizable añadido al principio del encabezado**

*Encabezados*

Cuando se agrega un nuevo campo a un encabezado personalizable, el campo ahora se agrega como el primer campo a la izquierda en el encabezado o inmediatamente después de la variable [!UICONTROL Buscar] dentro de la plantilla de diseño. Antes de este cambio, el campo se añadía como el último campo del encabezado.

+++

+++**Actualización de mantenimiento el 11 de agosto de 2022**

**No se pueden editar los formularios personalizados debido a un límite de caracteres incorrecto en los campos de texto descriptivo**

*Formularios personalizados de mi grupo*

Cuando un usuario intenta editar un formulario personalizado, este tiene un [!UICONTROL Texto descriptivo] que actualmente contiene más de 512 caracteres, el usuario no puede guardar las ediciones en el formulario personalizado y ve el siguiente error:

&quot;Los campos siguientes no son válidos: (Campo) es demasiado largo, máximo 512&quot;

Esto afecta a [!UICONTROL Texto descriptivo] campos que anteriormente funcionaban bien a pesar de tener más de 512 caracteres.

**Los datos de los campos ocultos por salto de sección no se conservan al convertir un problema en un proyecto**

*Formularios personalizados de mi grupo*

Cuando un usuario está convirtiendo un problema en un proyecto y el problema incluye un formulario personalizado con datos en un salto de sección que se puede ocultar mediante la lógica de visualización, los datos de esa sección no se transfieren al nuevo proyecto.

**Los datos de los campos ocultos por salto de sección no se conservan al convertir una solicitud en un proyecto**

*Formularios personalizados de mi grupo*

Cuando un usuario está convirtiendo una solicitud en un proyecto y esta incluye un formulario personalizado con datos en un salto de sección que se puede ocultar mediante la lógica de visualización, los datos de esa sección no se transfieren al nuevo proyecto.

**No se pueden editar formularios personalizados debido al campo Texto descriptivo**

*Formularios personalizados de mi grupo*

Cuando un usuario intenta editar un formulario personalizado que incluye un campo de texto descriptivo, la etiqueta del campo no se rellena. El usuario ve el error &quot;[!UICONTROL Este campo es obligatorio]&quot; en el campo etiqueta y el usuario no puede editar el formulario personalizado debido a este error.

**No se pueden quitar instrucciones de un campo personalizado en el generador de formularios personalizado**

*Formularios personalizados de mi grupo*

Cuando un usuario está editando un campo personalizado e intenta eliminar el texto existente en la variable [!UICONTROL Instrucciones] , el texto no se elimina cuando se guarda el campo. El usuario puede editar texto, pero no puede eliminarlo por completo.

**La asignación de equipo al crear una solicitud no aparece en una nueva solicitud**

*Solicitudes*

Cuando un usuario crea una solicitud y asigna un equipo a la solicitud y luego la envía, el equipo no se asigna a la solicitud que se crea. Esto solo afecta a la asignación de equipos. Las asignaciones de usuario funcionan según lo esperado.

+++

+++**Actualización de mantenimiento el 4 de agosto de 2022**

Estos problemas se solucionaron solo en la nueva [!DNL Workfront] experiencia.

Todo [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Error al cambiar la fecha de finalización prevista en el encabezado de una tarea o problema**

*Tareas y problemas*

Cuando un usuario intenta cambiar la variable [!UICONTROL Fecha de finalización planeada] en el encabezado de una tarea o problema, la fecha no cambia y el usuario ve un error similar al siguiente:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Actualizaciones en julio de 2022

+++**Actualización de mantenimiento del 28 de julio de 2022**

Estos problemas se solucionaron solo en la nueva [!DNL Workfront] experiencia.

Todo [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Error al abrir un elemento desde el [!UICONTROL Lista de trabajo en el hogar]**

*[!UICONTROL Página de inicio]*

Cuando un usuario intenta abrir un elemento en su [!UICONTROL Lista de trabajo en el hogar], el elemento no se abre y el usuario ve el siguiente mensaje:

&quot;[!UICONTROL Se ha producido un error y estamos trabajando para resolver el problema. Para continuar con su trabajo, intente actualizar esta página del explorador.]&quot;

**Las tareas y los problemas delegados a un usuario no aparecen en la lista de trabajo principal del usuario**

*[!UICONTROL Página de inicio]*

Cuando el usuario ve sus [!UICONTROL Lista de trabajo en el hogar], las tareas o problemas delegados al usuario no aparecen en la lista y es posible que el usuario no tenga conocimiento de las delegaciones.

**Los informes programados no se envían a todos los destinatarios**

*Informes*

Cuando se envía un informe programado, no se envía a todos los usuarios en la sección &quot;[!UICONTROL Enviar a]&quot;. Los usuarios omitidos son aleatorios y pueden variar cada vez que se envía el informe.

**[!UICONTROL No se pueden anular las tareas al adjuntar una plantilla]**

*Plantillas*

Cuando un usuario adjunta y personaliza una plantilla, se le pide que anule la selección de tareas que no desee incluir. Sin embargo, ninguna de las tareas se muestra como seleccionadas y el usuario no puede anular la selección.

**Los campos &quot;Configuración regional&quot; ahora tienen etiquetas más específicas**

*Terminología*

Para hacer la función de la &quot;[!UICONTROL Configuración regional]&quot; campos más claros, hemos actualizado sus etiquetas.

* La variable[!UICONTROL Configuración regional]&quot; en el perfil de usuario ahora se denomina &quot;[!UICONTROL Configuración regional de correo electrónico]&quot;
* La variable[!UICONTROL Configuración regional]&quot; campo encontrado en el [!UICONTROL Configuración] >[!UICONTROL Sistema] >[!UICONTROL Información del cliente] área ahora está etiquetada como &quot;[!UICONTROL Configuración regional de correo electrónico predeterminada]&quot;

La funcionalidad de estos campos no ha cambiado.

**Problemas al crear hojas de horas**

*Hojas de horas*

Se han comunicado los siguientes problemas con respecto a la creación de partes de horas:

* Cuando un usuario intenta crear un parte de horas para una función, el parte de horas no se crea y el usuario ve el error[!UICONTROL No se encuentra el usuario con valores de clave principal &#39;XXXXXXXXXXX&#39;.]&quot;
* Cuando un usuario intenta crear un parte de horas para un equipo, [!UICONTROL typeforward] no se rellena con equipos y la variable [!UICONTROL Crear hoja de horas] está desactivado.


**Áreas de [!DNL Workfront Proof] no actualizar cuando se crea, mueve o archiva una prueba**

*[!DNL Workfront]Revisión*

La prueba está experimentando retrasos en la indexación. Esto puede afectar a la experiencia del usuario de maneras que incluyen lo siguiente:

* Los tableros no muestran el número correcto de pruebas
* Las carpetas no se actualizan cuando se crea o mueve una prueba
* Las pruebas archivadas permanecen en listas de pruebas activas.

+++

+++**Actualización de mantenimiento (corrección) el 26 de julio de 2022**

Estos problemas se solucionaron solo en la nueva [!DNL Workfront] experiencia.

Todo [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Las horas mostradas en el parte de horas son diferentes a las de la lista Hojas de horas**

*Hojas de horas*

Cuando un usuario abre un parte de horas para verlo, las horas que se muestran son diferentes a las que el usuario ve el mismo parte de horas en una lista de parte de horas.


**La solicitud convertida a un proyecto con plantilla muestra el grupo de la cola de solicitudes, no el grupo de la plantilla**

*Solicitudes*

Cuando un usuario convierte una solicitud en un proyecto mediante una plantilla, el proyecto recién creado se asocia al grupo propietario de la cola de solicitudes, no al grupo asignado en la plantilla. Esto ocurre aunque, cuando se crea el proyecto, el grupo asociado a la plantilla se rellena en la variable [!UICONTROL Grupo] campo .

+++

+++**Actualización de mantenimiento del 21 de julio de 2022**

Estos problemas se solucionaron solo en la nueva [!DNL Workfront] experiencia.

Todo [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**El estado de rechazo asociado con una aprobación respeta el flujo de trabajo de aprobación**

**NOTA: Esta funcionalidad se publicó el 22 de julio de 2022.**

*Rutas de aprobación*

Si selecciona un estado asociado a un proceso de aprobación como estado de rechazo de una ruta de aprobación, el objeto rechazado pasa al estado seleccionado y se marcará como &quot;[!UICONTROL Pendiente de aprobación]&quot;. Por ejemplo, si selecciona [!UICONTROL En espera] para el estado de rechazo y la variable [!UICONTROL En espera] estado está asociado a un proceso de aprobación, el objeto rechazado se coloca en el estado de &quot;[!UICONTROL Retención: pendiente de aprobación]&quot;, que requiere la aprobación.

Antes de esta actualización, el objeto omitió el proceso de aprobación para el estado de rechazo y se colocó en la variable [!UICONTROL En espera] estado.

**Configuración de una dirección URL de ayuda personalizada**

*[!UICONTROL Menú principal]*

Si su organización tiene un sitio de ayuda interno personalizado, puede configurar la variable [!UICONTROL Menú principal] [!UICONTROL Ayuda] para ir a ese sitio. Esto resulta útil si el sitio de ayuda contiene información sobre cómo utiliza su organización [!DNL Workfront].
Esta dirección URL personalizada no afecta al vínculo de ayuda principal del área superior de [!DNL Workfront], así como los vínculos de ayuda contextual en todo [!DNL Workfront], que llevan a los usuarios al [!DNL Workfront] Sitio de ayuda.

**No se puede seleccionar el tiempo transcurrido al editar en línea [!UICONTROL Duración de la tarea]**

*Tareas*

Cuando un usuario está viendo una lista de tareas e intenta editar la variable [!UICONTROL Duración de la tarea], no están disponibles las siguientes unidades de duración:

* [!UICONTROL Minutos transcurridos]
* [!UICONTROL Horas transcurridas]
* [!UICONTROL Días transcurridos]
* [!UICONTROL Semanas transcurridas]
* [!UICONTROL Meses transcurridos]

**[!UICONTROL Mis actualizaciones] la página está en blanco**

*Actualizaciones*

Cuando un usuario intenta ver sus [!UICONTROL Mis actualizaciones] , la página no se carga. El usuario solo puede ver la variable [!DNL Workfront] encabezado de navegación.

**&quot;[!UICONTROL Permitir solo la autenticación SAML 2.0]&quot; falta la configuración al copiar un usuario**

*Usuarios*

Cuando un administrador de grupo copia un usuario y anula la selección de &quot;[!UICONTROL Enviar un correo electrónico de invitación a esta persona]&quot;, la opción &quot;O[!UICONTROL Permitir sólo la autenticación SAML 2.0]&quot; la casilla de verificación no aparece como se espera. Esto puede ocurrir incluso cuando se cumplen todos los requisitos de acceso y permisos para esta acción.

+++

+++**Actualización de mantenimiento el 14 de julio de 2022**

Estos problemas se solucionaron solo en la nueva [!DNL Workfront] experiencia.

Todo [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Error al restablecer la contraseña**

*Inicio de sesión*

Cuando un usuario intenta restablecer su contraseña, no puede restablecerla y ve un mensaje que le dice que no tiene acceso. El usuario no puede iniciar sesión en Workfront.

**No se puede solicitar más acceso a un informe**

*Informes*

Cuando un usuario con acceso limitado a un informe intenta solicitar más acceso a un informe, la opción de solicitar más acceso no está disponible en la sección [!UICONTROL acciones del informe] para abrir el Navegador.

**Se ha actualizado el mensaje de confirmación al eliminar un borrador de solicitud**

*Solicitudes*

Cuando se descarta una solicitud redactada, aparece el mensaje de confirmación que aparece después de hacer clic en &quot;[!UICONTROL Descartar borrador]&quot; muestra lo siguiente:

* [!UICONTROL Borrador descartado] (se trata de una notificación para informarle de que su borrador se descartó)
* [!UICONTROL Deshacer] (se trata de un vínculo en el que puede hacer clic para revertir la acción de eliminar el borrador. Esto mantendrá el borrador en lugar de eliminarlo).

Antes de este cambio, las opciones eran:

* [!UICONTROL El borrador se descartará]
* [!UICONTROL Cancelar]

**Los valores de fecha de los campos Entrada de diario son incorrectos cuando se accede a ellos a través de la API**

*Actualizaciones*

Cuando un usuario cambia un valor de fecha en un objeto y, a continuación, se accede a la Entrada de diario que representa ese cambio de fecha a través de la API, se usan los valores de fecha para [!UICONTROL oldDateVal] y [!UICONTROL newDateVal] La API devuelve incorrectos.

**Error al intentar deshacer el comentario**

*Actualizaciones*

Cuando un usuario intenta deshacer un comentario, el comentario no se deshace y el usuario ve el siguiente error:

[!UICONTROL Error 403: No tiene acceso suficiente para eliminar esta Nota /attask/api-internal/NOTE]

**Nueva limitación al número de caracteres de una actualización en Vista previa**

*Actualizaciones*

Para mejorar el rendimiento del [!UICONTROL Actualizaciones] , se ha introducido un nuevo límite en el número de caracteres que se pueden introducir en una actualización o en una respuesta a una actualización existente. El nuevo límite es de 15 000 caracteres. Esta actualización no cambió el número de caracteres permitidos al utilizar la API. El límite de caracteres de la API para las actualizaciones es de 4000.

**Error al cargar datos adjuntos desde [!DNL Workfront] para la integración con Outlook**

*Integraciones de Workfront*

Cuando un usuario intenta cargar un archivo adjunto mediante la variable [!DNL Workfront for Outlook] , el archivo adjunto no se carga y el usuario ve el siguiente mensaje:

[!UICONTROL Algunos archivos adjuntos no se han cargado. Motivo: Se ha producido un error al cargar archivos adjuntos.]

**Probar la actualización de notificaciones por correo electrónico**

*[!DNL Workfront]Revisión*

A principios de este mes, como parte de un parche para el [!DNL Workfront] Entorno de producción, hemos corregido un error en el sistema de notificación de correo electrónico de prueba. Este cambio no se comunicó en la actualización de mantenimiento cuando se publicó. Hemos añadido la siguiente información al [Actualización de mantenimiento del 2 de junio de 2022](#maintenance-update-on-june-2-2022) :

Como resultado de estas correcciones de errores, la dirección de correo electrónico que se utiliza para enviar notificaciones de prueba ha cambiado.

Anteriormente, la prueba de las direcciones de correo electrónico contenía el subdominio de la organización. Por ejemplo, notifications@[dominio de empresa].my.workfront.com

Ahora, la identificación de direcciones de correo electrónico ya no contiene un subdominio de organización. Todas las notificaciones por correo electrónico de prueba provienen de la siguiente dirección: notification@my.workfront.com

Como resultado, le recomendamos que realice las siguientes acciones si aún no lo ha hecho:

* Actualice los filtros de correo no deseado para aceptar correos electrónicos de notification@my.workfront.com
* Actualice sus listas de permitidos para aceptar correos electrónicos de notification@my.workfront.com

**Las opciones de usuario no se pueden modificar después de la configuración inicial en las plantillas de flujo de trabajo**

*[!DNL Workfront Proof]*

Cuando un usuario agrega un usuario a una plantilla de flujo de trabajo, puede configurar opciones. Sin embargo, una vez completada la configuración inicial, el usuario ya no puede modificar lo siguiente:

* &quot;[!UICONTROL Resuelva comentarios y aplique acciones]&quot; capacidad
* [!UICONTROL &quot;Compartir prueba etiquetando]&quot; capacidad
* Función de prueba ([!UICONTROL Revisor], [!UICONTROL Aprobador], etc.)

**&quot;[!UICONTROL Elementos de trabajo de este proyecto]&quot; se ha restaurado el filtro en el proyecto [!UICONTROL Equilibrador de carga de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Hemos restaurado el filtro &quot;Elementos de trabajo de este proyecto&quot; en el [!UICONTROL Asignado] al acceder a la [!UICONTROL Equilibrador de carga de trabajo] de un proyecto.

Este filtro ahora aparece en la sección &quot;[!UICONTROL Sugerido]&quot; de los filtros para la sección [!UICONTROL Trabajo asignado] área de un proyecto [!UICONTROL Equilibrador de carga de trabajo].

+++

## Actualizaciones en junio de 2022

+++**Actualización de mantenimiento del 30 de junio de 2022**

**Visualice la [!UICONTROL Equilibrador de carga de trabajo] para una semana**

*[!UICONTROL Distribuidor de cargas de trabajo]*

En función de los comentarios que hemos recibido de muchos clientes, ahora hemos añadido una opción para mostrar la variable [!UICONTROL Equilibrador de carga de trabajo] durante una semana. Antes de esta actualización, podría mostrar la variable [!UICONTROL Equilibrador de carga de trabajo] durante 4, 6 y 12 semanas. Con esta actualización, también hemos cambiado la opción de 12 semanas a 3 meses.

**El panel Delegar ya está disponible en el equilibrador de carga de trabajo**

*[!UICONTROL Distribuidor de cargas de trabajo]*

NOTA: Esta actualización solo existe en el entorno de Vista previa. La funcionalidad asociada con esta actualización estará disponible en Producción con la versión 22.3.

Ahora puede ver los delegados de una tarea o problema desde el equilibrador de carga de trabajo. Al asignar una tarea o un problema desde el equilibrador de carga de trabajo, puede ver una lista de asignaciones, así como una lista de delegados para la tarea o el problema, si están delegados actualmente.

**No se puede abrir la información de extremo en el Explorador de API**

*API*

Cuando un usuario está viendo la variable [!DNL API Explorer] y hace clic en un extremo, la información del extremo no se muestra.

**Problemas con [!UICONTROL Detalles] al usar la variable [!UICONTROL Calendario principal]**

*Página de inicio*

Cuando un usuario utiliza la variable [!UICONTROL Calendario principal] y hace clic en una tarea, puede producirse una de las siguientes situaciones:

* La variable [!UICONTROL Detalles] aparece brevemente y desaparece. El usuario no puede acceder a los detalles.
* La variable [!UICONTROL Detalles] no aparece. El usuario no puede acceder a los detalles.
* La variable [!UICONTROL Detalles] aparece, pero no está en la ubicación correcta. El usuario puede hacer clic en el botón para acceder a los detalles.

+++

+++**Actualización de mantenimiento (corrección) el 24 de junio de 2022**

**El selector de fechas no se cierra al editar Formulario personalizado**

*Formularios personalizados*

Cuando un usuario está editando un formulario personalizado e intenta cambiar una fecha, el selector de fechas no se cierra cuando se selecciona la fecha. El usuario no puede cerrar el selector de fechas guardando, cancelando o haciendo clic fuera del selector de fechas.

Esto se ha informado en los siguientes ámbitos:

* [!UICONTROL Actualizaciones] area
* [!UICONTROL Página de inicio]

**El usuario no puede pasar a otro paso de una prueba**

*Pruebas*

Cuando un usuario está viendo la variable [!UICONTROL Flujo de trabajo de prueba] de una prueba e intenta arrastrarse a un paso diferente de la prueba, el nombre del usuario se ajusta al escenario original y no se añade al escenario deseado.

+++

+++**Actualización de mantenimiento del 23 de junio de 2022**

**[!UICONTROL No se puede agregar una nueva solicitud a través del panel]**

*Paneles*

Cuando un usuario está viendo un tablero en un proyecto e intenta agregar una nueva solicitud haciendo clic en el botón [!UICONTROL +Nueva solicitud] , el botón no responde y el usuario no puede agregar una solicitud nueva.

**Error al ver elementos en la lista de trabajo principal**

*[!UICONTROL Página de inicio]*

Cuando un usuario está viendo su [!UICONTROL Lista de trabajo en el hogar] y hace clic en un elemento de la sección [!UICONTROL Aprobaciones enviadas] , la página muestra el siguiente error:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

Si el usuario actualiza la página, hace clic en cualquier elemento de la sección [!UICONTROL Lista de trabajo], aparece el error . El problema ya no afecta solo a los elementos del [!UICONTROL Aprobaciones enviadas] para obtener más información.

**La sección personalizada de un objeto incluye resultados que no están en ese objeto**

*Objetos*

Cuando un usuario está viendo un [!UICONTROL custom] en un objeto, la sección personalizada muestra los elementos que no forman parte de ese objeto. Esto se ha informado cuando la sección personalizada se agrega directamente al objeto y cuando se agrega una sección personalizada a través de una plantilla de diseño.

**Las tareas se mueven a un proyecto incorrecto**

*Tareas*

Cuando un usuario mueve tareas del proyecto A al proyecto B y, a continuación, mueve más tareas del proyecto A al proyecto C, las tareas que se movieron originalmente al proyecto B aparecen en el proyecto C.

**Algunos botones o iconos no funcionan al acceder a [!UICONTROL Equilibrador de carga de trabajo] desde un vínculo o panel compartido**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario va al [!UICONTROL Equilibrador de carga de trabajo] a través de un vínculo compartido o un vínculo en un panel e intenta utilizar el elemento en la parte superior de la pantalla, los elementos no funcionan. Se ha informado de ello en relación con los siguientes elementos:

* [!UICONTROL Hoy]
* Flechas atrás y adelante
* [!UICONTROL semanas]
* Icono de calendario (selector de fechas)

+++

+++**[!DNL Workfront]Actualización de mantenimiento del planificador de escenarios el 23 de junio de 2022**

**Usuarios con [!UICONTROL Administrar] los permisos de un plan pueden compartirlo con otros**

Como usuario con [!UICONTROL Administrar] permisos para un plan de [!DNL Scenario Planner], ahora puede compartirlo con otros usuarios. Antes de esta actualización, solo el creador del plan podía compartir el plan con otros usuarios.

+++

+++**Actualización de mantenimiento del 16 de junio de 2022**

**El administrador del grupo no puede agregar miembros al grupo**

*Grupos*

Cuando un administrador de grupo intenta agregar un usuario a un grupo, la lista desplegable para seleccionar el usuario no se rellena. El administrador del grupo no puede seleccionar ningún usuario y, por lo tanto, no puede agregar ningún usuario al grupo.

**Los trimestres personalizados no aparecen al configurar un filtro**

*Filtros*

Cuando un usuario crea un filtro y filtra por un campo de fecha, la lista desplegable de operadores disponibles para el campo de fecha no incluye ningún cuarto personalizado agregado recientemente.

**Error &quot;Whoops&quot; al convertir un problema en un proyecto mediante una plantilla**

*Proyectos*

Cuando un usuario intenta convertir un problema en un proyecto a través de una plantilla y el problema tiene un formulario personalizado que contiene una sección de solo administración, el problema no se convierte y el usuario ve el siguiente error:

&quot;[!UICONTROL Intentemos de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

**Las solicitudes se envían sin rellenar los campos obligatorios**

*Solicitudes*

Cuando un usuario crea una solicitud y no rellena los campos obligatorios y luego envía la solicitud, esta se envía sin datos en los campos obligatorios. El comportamiento esperado es que la solicitud no se envíe y que se notifique al usuario que debe rellenar los campos obligatorios antes de enviar la solicitud.

**Los nuevos trimestres personalizados no parecen guardarse**

*Configurar*

Cuando un usuario agrega un nuevo trimestre personalizado desde el área Proyectos de configuración y hace clic en [!UICONTROL Guardar], no hay ninguna indicación visual del guardado. El usuario no ve un mensaje de éxito y la variable [!UICONTROL Guardar] en todavía presente y activo. Sin embargo, si el usuario actualiza la página, puede ver que los trimestres nuevos aparecen en la lista de trimestres personalizados.

Si el usuario agrega un trimestre nuevo, haga clic en [!UICONTROL Guardar], no recibe ninguna indicación de cómo guardar, agrega otro trimestre sin actualizar la página y hace clic en [!UICONTROL Guardar] de nuevo, es posible que el segundo trimestre añadido no se guarde.

**[!UICONTROL Solicitudes de trabajo del equipo] la página está en blanco**

*Equipos*

NOTA: Este problema solo existe en el entorno de Vista previa.

Cuando un usuario intenta abrir el [!UICONTROL Solicitudes de trabajo] en una página de equipo, la página está en blanco. El usuario puede ver la barra de navegación superior, pero no el contenido de la página.

+++

+++**Actualización de mantenimiento del 9 de junio de 2022**

**No se pueden seleccionar objetos para filtrar [!UICONTROL Optimizador de Portfolio] preferencias**

*Portafolios*

Cuando un usuario está en la [!UICONTROL Optimizador de Portfolio] y visualiza el [!UICONTROL Filtros del proyecto] en la ficha [!UICONTROL Preferencias] , las casillas de verificación situadas junto a los objetos no están presentes. El usuario no puede marcar ni desmarcar casillas y, por lo tanto, no puede seleccionar objetos para filtrar.

**No se puede cambiar [!UICONTROL Fecha de inicio planeada] o [!UICONTROL Fecha de finalización planeada] cuando &quot;[!UICONTROL Programar desde]&quot; no está marcado**

*Proyectos*

Cuando un usuario intenta editar la variable [!UICONTROL Fecha de inicio planeada] o [!UICONTROL Fecha de finalización planeada] de un proyecto, y[!UICONTROL Programar desde]&quot; para ese proyecto no está activada, la opción [!UICONTROL Fecha de inicio planeada] y [!UICONTROL Fecha de finalización planeada] las áreas están deshabilitadas y el usuario no puede editar esas fechas.

**No se puede editar el nivel de acceso de los usuarios**

*Usuarios*

Cuando un usuario con acceso de Planificador que incluye el acceso de Administración de usuarios (Usuarios del grupo) intenta editar a los usuarios del grupo para el que son administradores, se muestra la variable [!UICONTROL Acceso] el campo level está desactivado y el usuario no puede editar el nivel de acceso.

+++

+++**[!DNL Workfront Scenario Planner]Actualización de mantenimiento del 9 de junio de 2022**

**Se puede cambiar el tamaño del panel izquierdo en el[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Ahora puede cambiar el tamaño del panel izquierdo en un plan, en la [!DNL Scenario Planner]. Esto permite que los nombres de iniciativa más largos se muestren completamente. Antes de esta actualización, los nombres de iniciativas más largos se truncaban.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento del 9 de junio de 2022**

**Los datos de los formularios personalizados no están disponibles en [!DNL Workfront Fusion] [!DNL Workfront] módulos**

*[!DNL Workfront Fusion]*

Cuando un usuario está configurando un [!DNL Workfront] módulo en [!DNL Workfront Fusion], e intenta seleccionar salidas para el módulo, los campos de los formularios personalizados no están visibles. Esto ocurre cuando el formulario personalizado se creó para un tipo de [!DNL Workfront] y luego se le agregó otro tipo. [!DNL Workfront Fusion] sólo muestra los campos de los formularios personalizados creados originalmente para el tipo de objeto seleccionado.

**No se puede desplazar para ver todas las ejecuciones de escenario**

*[!DNL Workfront Fusion]*

Cuando un usuario está viendo el historial de ejecución de un escenario e intenta desplazarse hacia abajo para ver más ejecuciones, el usuario deja de cargarse y no puede verlo. Además, el usuario no puede volver a desplazarse hasta las ejecuciones más recientes.

+++

+++**Actualización de mantenimiento del 2 de junio de 2022**

**[!UICONTROL Optimizador de Portfolio] muestra una puntuación de 0 cuando se usa un idioma distinto del inglés**

*Portafolios*

Cuando un usuario utiliza [!DNL Workfront] en un idioma distinto del inglés y visualiza la variable [!UICONTROL Optimizador de Portfolio], la puntuación se muestra como 0. Esto puede ocurrir incluso cuando no se ha completado el caso empresarial.

**Valores de campo calculados incorrectos al crear un proyecto a partir de una plantilla**

*Proyectos*

Cuando un usuario crea un proyecto a partir de una plantilla que incluye campos calculados, los valores de campo que aparecen en el nuevo proyecto son incorrectos.

**No se puede editar [!UICONTROL Condiciones] en [!UICONTROL Preferencias de proyecto] área de [!UICONTROL Configuración]**

*[!UICONTROL Configurar]*

Cuando un usuario intenta editar [!UICONTROL Condiciones] en el [!UICONTROL Preferencias de proyecto] área de [!UICONTROL Configuración], la página está en blanco.

**Nueva limitación al número de caracteres de una actualización en Vista previa**

*[!UICONTROL Distribuidor de cargas de trabajo]*

>[!NOTE]
>
>Esta actualización solo se aplica al entorno de Vista previa.

Para mejorar el rendimiento del área Actualizaciones , hemos introducido un nuevo límite en el número de caracteres que puede introducir en una actualización o en una respuesta a una actualización existente. El nuevo límite es de 15 000 caracteres. Esta actualización no cambió el número de caracteres permitidos al utilizar la API. El límite de caracteres de la API para las actualizaciones es de 4000. Actualizaciones Compatibilidad con campos personalizados de tipo Typehead en los filtros del equilibrador de carga de trabajo

Ahora se admiten filtros basados en la variable [!UICONTROL Typeforward] escriba campos personalizados en el equilibrador de carga de trabajo. Antes de este parche, el filtrado para este tipo de campos personalizados no era posible en Workload Balancer.

**No se pueden editar permisos en la función de un usuario**

*[!DNL Workfront Proof]*

Cuando un usuario intenta editar el[!UICONTROL Resuelva comentarios y aplique acciones]&quot; o &quot;[!UICONTROL Compartir una prueba mediante el etiquetado]&quot; en la función de un usuario en [!DNL Workfront Proof], los cambios no se guardarán. El usuario recibe una notificación de que la plantilla se ha actualizado, pero si el usuario vuelve a abrir los permisos de funciones, puede ver que los cambios no se guardaron.

+++


## Actualizaciones de mayo de 2022

+++**Actualización de mantenimiento del 26 de mayo de 2022**

Estos problemas se solucionaron solo en la nueva [!DNL Workfront] experiencia. [!DNL Adobe Workfront Classic] ya no es compatible.

Todo [!DNL Workfront Classic] se eliminará en julio de 2022. Por favor, pase a la nueva experiencia lo antes posible.

**Separadores de rutas de exploración actualizados**

*[!DNL Workfront]*

NOTA: Esta actualización se publicó el 24 de mayo de 2022.

Hemos actualizado los separadores de rutas de exploración en todas las áreas donde hay disponibles rutas de exploración. Ahora, los objetos de las rutas de exploración están separados por barras verticales (|). Antes de esta actualización, estaban separados por barras inclinadas (/).

**No se pueden editar formularios personalizados con saltos de sección**

*Formularios personalizados*

Cuando un usuario intenta editar un formulario personalizado que tiene un salto de sección, no puede editar el formulario y ve el siguiente mensaje:

[!UICONTROL La seguridad de salto de sección especificada no se puede aplicar en todos los tipos de objetos]

**Problemas al imprimir los tableros en el PDF**

*Paneles*

Se han notificado los siguientes problemas al imprimir un tablero en un PDF: El PDF no imprime todas las filas del informe. Cuando faltan líneas, solo se muestra espacio en blanco.
El PDF incluye espacios en blanco entre los encabezados de columna y la primera fila del informe.

**[!DNL Portfolio Optimizer]muestra una puntuación de 0 cuando se usa un idioma distinto del inglés**

*Portafolios*

Cuando un usuario utiliza [!DNL Workfront] en un idioma distinto del inglés y visualiza la variable [!UICONTROL Optimizador de Portfolio], la puntuación se muestra como 0. Esto puede ocurrir incluso cuando no se ha completado el caso empresarial.

**Algunos formularios personalizados no se muestran al editar una plantilla**

*Plantillas*

Cuando un usuario intenta editar los formularios personalizados en una plantilla haciendo clic en [!UICONTROL Editar] en el encabezado de la plantilla, la variable [!UICONTROL Editar plantilla] solo muestra uno de los formularios personalizados adjuntos a la plantilla.

**El vínculo compartido a Workload Balancer muestra el trabajo asignado incorrectamente**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario ve la variable [!UICONTROL Equilibrador de carga de trabajo] mediante un vínculo compartido, la variable [!DNL Workload Balancer] incluye [!UICONTROL Trabajo asignado] en el [!UICONTROL Trabajo no asignado] para obtener más información. [!UICONTROL Trabajo asignado] no tiene una sección separada. Cuando el usuario ve la variable [!UICONTROL Equilibrador de carga de trabajo] sin usar el vínculo compartido, [!UICONTROL Trabajo asignado] se muestra como se espera.

+++

+++**Actualización de mantenimiento el 19 de mayo de 2022**

**No se puede crear una prueba a partir de un[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Cuando un usuario intenta crear una prueba a partir de un [!DNL PowerPoint] que incluye un gráfico, la creación de la prueba falla.

**No se puede crear una prueba a partir de un [!UICONTROL Word] documento**

*[!DNL Workfront Proof]*

Cuando un usuario intenta crear una prueba a partir de un [!DNL Word] documento que incluye un gráfico, la creación de la prueba falla.

**No se puede agregar un mensaje personalizado al compartir una prueba**

*[!DNL Workfront Proof]*

Cuando un usuario está viendo una prueba, abre el [!UICONTROL Prueba de uso compartido] y selecciona el [!UICONTROL Añadir mensaje personalizado] , el usuario no puede escribir en el cuadro de texto que se abre. Cuando el usuario intenta escribir en este cuadro, el cuadro desaparece inmediatamente.

**No se puede cerrar la prueba**

*[!DNL Workfront Proof]*

Cuando un usuario está viendo una prueba e intenta cerrarla, falta la X para cerrar la prueba en la esquina superior derecha de la misma.

**No se puede agregar ni quitar el administrador del grupo**

*Grupos*

Si un usuario está viendo una [!UICONTROL Grupo] e intenta agregar o quitar un administrador de grupo mediante la [!UICONTROL Administradores de grupo] en el encabezado, los cambios no se guardan y el usuario ve el siguiente error:

[!UICONTROL Error Whoops! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]

**Elemento de bloques de barras de desplazamiento horizontal al final de la lista**

*Proyectos*

Cuando un usuario está viendo una lista con una vista que se extiende fuera de la pantalla, la barra de desplazamiento horizontal bloquea la vista del usuario del último elemento de la lista.

**&quot;[!UICONTROL Error inesperado]&quot; al convertir un problema en un proyecto mediante una plantilla**

*Listas*

Cuando un usuario intenta convertir un problema en un proyecto mediante una plantilla, el problema no se convierte y el usuario ve el siguiente mensaje:

[!UICONTROL Se produjo un error inesperado]

**La variable [!UICONTROL Estado] en una vista de hoja de horas es ahora de solo lectura**

*Hojas de horas*

Hemos cambiado el [!UICONTROL Estado] en una vista de hoja de horas como de solo lectura. Antes de este cambio, los usuarios podían editar en línea el estado de un parte de horas, lo que les permitía anular la decisión de los aprobadores de parte de horas.

+++

+++**Actualización de mantenimiento el 12 de mayo de 2022**

**[!UICONTROL Guardar] no deja de cargarse al editar un proyecto**

*Proyectos*

Cuando un usuario está editando un proyecto e intenta guardarlo, observa que la variable [!UICONTROL Guardar] muestra la palabra &quot;[!UICONTROL Carga].&quot; Si el usuario hace clic en este botón para guardar los cambios en el proyecto, el botón no responde y los cambios no se guardan.

**Las etiquetas de campo no aparecen al ver un objeto en [!UICONTROL Página principal]**

*Página de inicio*

Cuando el usuario selecciona un objeto de su [!UICONTROL Lista de trabajo en el hogar], el área a la derecha del [!UICONTROL Lista de trabajo en el hogar] que muestra el objeto no incluye etiquetas de campo. Los valores de campo están presentes.

**El filtro rápido no se centra automáticamente en la barra de búsqueda**

*Listas*

Cuando un usuario está en una lista y hace clic en la lupa para filtrar rápidamente y, a continuación, empieza a escribir, el texto no aparece. Esto se debe a que el foco permanece en el icono de lupa en lugar de transferirse a la barra de búsqueda.

Al hacer clic en la barra de búsqueda, se transfiere el enfoque y se permite al usuario introducir el texto de la búsqueda.

**Los usuarios no pueden insertar campos de edición en un informe**

*Informes*

Cuando un usuario intenta editar un campo de un informe y este se extrae de un formulario personalizado, no puede editar el campo. Esto ocurre cuando el formulario personalizado se creó originalmente para un tipo de objeto distinto del objeto al que está adjunto.

**Texto de etiqueta y botón que no está visible al crear una prueba**

*[!DNL Workfront Proof]*

NOTA: Este problema solo existe en el entorno de Vista previa.

Cuando un usuario intenta crear una prueba, el texto no está visible para las opciones o los botones. Por lo tanto, el usuario no sabe qué representa cada opción o botón y no puede configurar la prueba.

+++

+++**Actualización de mantenimiento el 5 de mayo de 2022**

**No se puede agregar un nuevo registro de facturación**

*Proyectos*

Cuando un usuario está en la [!UICONTROL Registros de facturación] área de un proyecto y está usando la variable [!UICONTROL Nuevo registro de facturación] Ver, si el usuario intenta agregar un nuevo registro de facturación, los campos de un nuevo registro de facturación no aparecen y no se puede crear el registro de facturación.

**Error al realizar una asignación masiva en [!UICONTROL Equilibrador de carga de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario intenta realizar asignaciones en la variable [!DNL Workload Balancer] de un proyecto, se redirige al usuario a una página con el siguiente mensaje:

&quot;[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]&quot;

El usuario no puede salir de esta página hasta que actualice la página.

**Se ha actualizado la navegación para abrir el [!UICONTROL Resumen] panel para tareas y problemas en el [!UICONTROL Equilibrador de carga de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Ahora, solo tiene que hacer clic en una tarea o en la barra de problemas de [!UICONTROL Equilibrador de carga de trabajo] abre el panel Resumen. Antes de esta actualización, tenía que hacer clic en el botón [!UICONTROL Abrir resumen] en la barra de herramientas y, a continuación, haga clic en la tarea o el problema. Esto había demostrado ser una experiencia confusa que ahora se corrige. También puede hacer clic en el botón [!UICONTROL Más] junto al nombre de la tarea o del problema y, a continuación, haga clic en [!UICONTROL Abrir resumen].

**El administrador del grupo no puede ver los detalles de los usuarios del grupo**

*Usuarios*

Cuando un usuario asignado a un nivel de acceso que incluya la variable [!UICONTROL Administración de usuarios (usuarios del grupo)] la configuración de acceso intenta ver los detalles de un usuario en su grupo, y aparece el siguiente error:

&quot;[!UICONTROL Intentemos de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

**No se puede eliminar el estado del grupo personalizado**

*Grupos*

Cuando un usuario intenta eliminar un estado de grupo personalizado del [!UICONTROL Grupo] , la página se queda en blanco y el estado no se elimina.

**La configuración de alertas por correo electrónico no es coherente entre el área Contactos y los Detalles del usuario**

*[!DNL Workfront Proof]*

La configuración de alerta de correo electrónico se muestra en la sección [!UICONTROL Contactos] área de [!DNL Workfront Proof] para un usuario determinado son diferentes de la configuración de alerta de correo electrónico establecida en el [!UICONTROL Detalles del usuario].

**No se puede utilizar la herramienta Texto al realizar un comentario en una prueba**

*[!DNL Workfront Proof]*

Cuando un usuario realiza un comentario sobre una prueba e intenta abrir el [!UICONTROL Texto] , la herramienta no se abre y el usuario ve el siguiente mensaje:

&quot;[!UICONTROL Los datos de texto de esta página se siguen descargando. Espere.]&quot;

**Los correos electrónicos de prueba irán al correo electrónico principal del usuario**

*[!DNL Workfront Proof]*

Estamos realizando ajustes en la forma en que se envían las notificaciones de prueba por correo electrónico. Ahora, las notificaciones irán a la dirección de correo electrónico principal del usuario en lugar del correo electrónico de alias generado por el sistema.

Para obtener más información sobre por qué el sistema genera correos electrónicos con alias, consulte Sincronización de usuarios entre Adobes [!DNL Workfront] y [!DNL Workfront Proof].

+++

## Actualizaciones de abril de 2022

+++**Actualización de mantenimiento del 28 de abril de 2022**

**No se puede desplazar hasta [!UICONTROL Guardar] al editar una hoja de horas**

*Hojas de horas*

Cuando un usuario está editando un parte de horas, no puede desplazarse por la ventana de edición lo suficientemente lejos como para ver la [!UICONTROL Guardar] y, por lo tanto, no puede editar el parte de horas.

**La firma electrónica ahora comprueba el ID de federación**

*Pruebas*

Al firmar una prueba electrónicamente, el sistema comprueba ahora el ID de federación si tiene SSO configurado en [!DNL Workfront Proof], además del correo electrónico en [!DNL Workfront].

Anteriormente, el sistema solo comprobaba el correo electrónico en Workfront.

+++

+++**Actualización de mantenimiento (corrección) el 25 de abril de 2022**

**[!UICONTROL Equilibrador de carga de trabajo] no se carga**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario intenta abrir el [!UICONTROL Equilibrador de carga de trabajo], el encabezado y la carga de navegación izquierda, pero el contenido del equilibrador de carga de trabajo no se carga. El usuario ve cuadrados grises parpadeantes en lugar de datos. En ocasiones, parte del contenido se carga, pero el usuario sigue viendo cuadrados grises parpadeantes en los que faltarían datos.

+++

+++**Actualización de mantenimiento el 21 de abril de 2022**

**Añadir una tarea hace que la página salte hacia abajo**

*Tareas*

Cuando un usuario agrega una tarea debajo de una tarea existente en una lista, la página salta a la parte inferior de la lista. Aunque la nueva tarea se encuentra en el lugar correcto, el usuario debe desplazarse hacia atrás para localizarla.

**Los usuarios agregados a una prueba no pueden acceder al elemento de trabajo de la prueba en[!DNL Workfront]**

*Pruebas*

Si se agrega un usuario a un escenario en el flujo de trabajo de una prueba, este no se agrega al uso compartido de documentos y no obtiene permisos para el elemento de trabajo de la prueba en [!DNL Workfront]. Cuando el usuario se encuentra en [!DNL Workfront] e intenta abrir el elemento de trabajo al que está adjunta la prueba, verán el siguiente mensaje:

&quot;[!UICONTROL No tiene acceso suficiente para ver este (objeto)]&quot;

Este problema es específico de las pruebas ya creadas y de los usuarios que se agregan después del hecho. Agregar usuarios al flujo de trabajo antes de la creación de la prueba funciona según lo esperado.

**No se puede enviar el correo electrónico de restablecimiento de contraseña desde[!DNL Workfront]**

*Usuarios*

Cuando un usuario intenta enviar un correo electrónico de restablecimiento de contraseña desde una lista de usuarios en [!DNL Workfront], la opción para enviar el correo electrónico no está disponible.

**El botón muestra &quot;[!UICONTROL Iniciar problema]&quot; en lugar de &quot;[!UICONTROL Iniciar solicitud]&quot;**

*Solicitudes*

Cuando un usuario ve una solicitud asignada a su equipo, ve un &quot;[!UICONTROL Iniciar problema]&quot; en el encabezado en lugar de &quot;[!UICONTROL Iniciar solicitud]&quot;.

**&quot;[!UICONTROL Deshacer comentario]&quot; elimina los usuarios etiquetados**

*Actualizaciones*

Cuando un usuario etiqueta a otro usuario en un comentario, publica el comentario y, a continuación, selecciona la opción[!UICONTROL Deshacer comentario]&quot;, el comentario aparece en un cuadro de actualización como de costumbre, pero el usuario etiquetado no está en el [!UICONTROL Usuarios etiquetados] en la ventana

**No se puede desplazar al usar [!UICONTROL Milestone] ver en un informe**

*Informes*

Cuando un usuario está viendo un informe, selecciona la variable [!UICONTROL Milestone] vista, la página muestra la vista Milestone pero ya no se desplaza y el usuario no puede ver ningún Milestones que estuvieran más abajo en la página.

**Moneda incorrecta cuando el informe se muestra en el panel**

*Informes*

Cuando un usuario ve un informe en un tablero, la moneda utilizada en el informe es incorrecta. Cuando el usuario ve el informe fuera del panel, la moneda es correcta.

**El filtro completado no muestra el elemento de trabajo completado**&#x200B; s

*[!UICONTROL Página de inicio]*

Cuando un usuario ve sus [!UICONTROL Lista de trabajo en el hogar] con la variable [!UICONTROL Completado] los elementos de trabajo completados no se muestran en la lista. Cuando la variable [!UICONTROL Todo] está seleccionado, los elementos completados se incluyen en la lista, lo que muestra que los elementos completados existen.

**[!DNL Workfront]no se carga**

*[!DNL Workfront]*

Cuando un usuario intenta iniciar sesión [!DNL Workfront], la página parece atascada en un bucle de redirecciones o actualizaciones, y no se carga.

+++

+++**Actualización de mantenimiento el 14 de abril de 2022**

**No se puede agregar una tarea desde un informe en una sección personalizada de una tarea**

*Tareas*

Cuando un usuario está viendo una sección personalizada en una tarea y la sección contiene un informe de tareas, el usuario no puede agregar una tarea desde ese informe. La variable [!UICONTROL Agregar tarea] resalta el informe, pero no abre una ventana para que el usuario añada una tarea.

**Botón Listo en una ubicación incorrecta al editar una vista**

*Vistas*

Cuando un usuario está editando una vista, la variable [!UICONTROL Listo] aparece en la parte superior de la pantalla y puede superponerse al texto.

El usuario puede editar la vista como de costumbre. La funcionalidad no se ve afectada.

**No se puede desplazar al usar [!UICONTROL Milestone] ver en un informe**

*Informes*

Cuando un usuario está viendo un informe, selecciona la variable [!UICONTROL Milestone] vista, la página muestra la vista Milestone pero ya no se desplaza y el usuario no puede ver ningún Milestones que estuvieran más abajo en la página.

**Pantalla en blanco al ver las actualizaciones**

*Actualizaciones*

Cuando un usuario está viendo actualizaciones y desplaza la pantalla para ver actualizaciones más abajo, la pantalla se queda en blanco y el usuario no puede ver ninguna actualización.

**Error al asignar de forma masiva al usuario a una tarea que no está asignada a la función del usuario**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario de la variable [!UICONTROL Equilibrador de carga de trabajo] intenta asignar tareas a un usuario cuya función de trabajo no coincide con la función de trabajo asignada a las tareas, el usuario ve un mensaje que indica que la tarea se asignará mediante la función de trabajo principal del usuario asignado. Sin embargo, cuando el usuario hace clic en &quot;[!UICONTROL Asignar],&quot; las tareas no están asignadas y el usuario ve el siguiente error:

&quot;[!UICONTROL Error. El servidor ha encontrado un error desconocido.]&quot;

+++

+++**Actualización de mantenimiento el 7 de abril de 2022**

**Los usuarios agregados a las pruebas tienen funciones incorrectas**

*Pruebas*

Cuando un usuario agrega otro usuario a una prueba, la función de ese usuario en la prueba se establece como &quot;[!UICONTROL Solo lectura]&quot; a pesar de la función de prueba real del usuario.

**No se puede enviar el correo electrónico de restablecimiento de contraseña al usuario**

*Usuarios*

Cuando un usuario intenta enviar un restablecimiento de contraseña a otro usuario, ve que la variable [!UICONTROL Enviar correo electrónico de contraseña olvidada] no está disponible en la [!UICONTROL Más] para abrir el Navegador.

**[!UICONTROL Actualizar todo] envía actualizaciones a perfiles de usuario en lugar de a proyecto**

*Actualizaciones*

Cuando un usuario está viendo la variable [!UICONTROL People] del área de un proyecto y selecciona el [!UICONTROL Actualizar todo] , luego introduce una actualización, la actualización no se anuncia en el propio proyecto. En su lugar, se publica en los perfiles de usuario individuales de cada usuario del proyecto.

**Número excesivo de páginas al imprimir actualizaciones**

*Actualizaciones*

Cuando un usuario está viendo un flujo de actualización que sería más de una página impresa e intenta imprimir la página, la pantalla de impresión muestra que el número de páginas es muy superior al número real de páginas necesarias para imprimir las actualizaciones. Si el usuario intenta imprimir en el PDF, se producirá un error en la creación del PDF.

**Los usuarios no pueden ver la lista completa de entidades compartidas con un informe cuando el[!UICONTROL Visible en todo el sistema]&quot; está activada**

*Informes*

Al compartir informes con varias entidades que se muestran en la variable [!UICONTROL Acceso a informes] , los usuarios no pueden desplazarse hasta la parte inferior de la lista para ver la lista completa cuando[!UICONTROL Visible en todo el sistema]&quot; activada.

**Moneda incorrecta usada en los informes**

*Informes*

Si un usuario establece que la moneda de un proyecto es diferente a la moneda predeterminada y, a continuación, visualiza un informe de ese proyecto, la moneda aparecerá como la moneda predeterminada en lugar de la moneda del proyecto.

**La información vista por última vez no se actualiza en [!UICONTROL Uso del informe] informes**

*Informes*

Cuando un usuario está viendo un informe que muestra información relativa a la última vez que se vio el informe, esa información puede estar en blanco o ser datos antiguos. Este problema afecta a los campos, incluidos los siguientes:

* [!UICONTROL Última visualización por]
* [!UICONTROL Últimos datos vistos]
* [!UICONTROL Últimos visualizadores X]
* [!UICONTROL Vistas este mes/trimestre/año]

**Tareas completadas que se muestran en [!UICONTROL Lista de trabajo en el hogar]**

*[!UICONTROL Página de inicio]*

Cuando un usuario está viendo su [!UICONTROL Lista de trabajo en el hogar], verán Completar tareas en la lista, incluso cuando la opción para mostrar Tareas completadas no esté seleccionada.

**Botón Programar no visible para programar la actualización del Simulador para pruebas**

*Entorno de espacio aislado*

La variable [!UICONTROL Programación] el botón utilizado para programar una actualización de entorno limitado no está visible en el banner superior del entorno de entorno limitado.

**Los cambios en un campo calculado afectan a todos los campos calculados de un formulario**

*Formularios personalizados*

Cuando un usuario se encuentra en el Generador de formularios personalizados y cambia el valor de un formulario calculado, todos los campos calculados del formulario muestran el nuevo valor. Esto puede afectar a los campos calculados nuevos o existentes.

**Colores que parpadean en el creador de formularios personalizado**

*Formularios personalizados*

Cuando un usuario trabaja con campos calculados en el generador de formularios personalizado, los colores de los campos y las expresiones parpadean.

**[!UICONTROL No se puede rechazar una aprobación]**

*Rutas de aprobación*

Cuando un usuario intenta rechazar una aprobación, la variable [!UICONTROL Rechazar] no responde y la aprobación no se rechaza.

**[!UICONTROL Proyectos] La pestaña tiene el valor predeterminado Toda la sección del proyecto a pesar de la selección anterior**

*Proyectos*

Cuando un usuario va a una página Proyectos a través de una pestaña que se ha incrustado como parte de la plantilla de diseño, la página toma el valor predeterminado [!UICONTROL Todos los proyectos] del panel de navegación izquierdo. Esto ocurre incluso cuando el usuario elige otro área de navegación izquierda y luego sale de la página Proyectos y vuelve.

+++


## Actualizaciones en marzo de 2022

+++**Actualización de mantenimiento del 31 de marzo de 2022**

**Zonas horarias no coherentes entre [!DNL Workfront] y[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Cuando el perfil de un usuario está establecido en una zona horaria específica en [!DNL Workfront], la zona horaria del usuario en [!DNL Workfront Proof] está configurada en una zona horaria diferente.

**El vínculo para enviar un documento solicitado lleva a una página en blanco**

*Documentos*

Cuando un usuario recibe una solicitud para enviar un documento y hace clic en el vínculo al objeto en el que se solicitó el documento, el vínculo lleva a una página en blanco. Esto puede ocurrir al hacer clic en un vínculo de un correo electrónico o en una notificación interna de la aplicación.

**El grupo se asigna incorrectamente al convertir el problema en proyecto**

Grupos

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, la funcionalidad es:

* Si la plantilla tiene un grupo asignado, ese grupo se muestra en la ventana de conversión de problemas como el grupo para el nuevo proyecto.
* Si la plantilla no tiene ningún grupo asignado, el grupo predeterminado del usuario que está convirtiendo el problema se muestra en la ventana de conversión del problema como el grupo para el nuevo proyecto.
* Si la plantilla no tiene grupo, el nuevo proyecto debe heredar el grupo del proyecto del problema.

**No se puede adjuntar un formulario personalizado de objeto cruzado a la cola de solicitud**

Solicitudes

Cuando un usuario intenta agregar un formulario personalizado de objetos cruzados a la página de detalles de una cola, el formulario de objetos cruzados no aparece en la lista desplegable de formularios disponibles y el usuario no puede seleccionarlo para agregarlo a los detalles de la cola.

**Los usuarios no pueden tener asignada una función de trabajo secundario en [!UICONTROL Equilibrador de carga de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario intenta asignar otro usuario a una tarea de la [!UICONTROL Equilibrador de carga de trabajo], y la tarea se asigna a una función de trabajo que no sea la función de trabajo principal del usuario asignado, el usuario se asigna a la tarea por su función de trabajo principal y se muestra el siguiente mensaje:

&quot;\&lt;name> no coincide con la función de \&lt;task role=&quot;&quot; assignment=&quot;&quot;>. 1 elemento de trabajo asignado actualmente a la función &lt;\Asignación de rol de tarea\> se asignará a \&lt;name> en el papel de \&lt;primary job=&quot;&quot; role=&quot;&quot;>.&quot;

Esto ocurre incluso si el usuario tiene la función de trabajo de la asignación de funciones de tarea como rol secundario.

**Problema con la placa de depuración &quot;Mostrar más elementos de trabajo&quot; b**&#x200B;

*Agile*

Cuando un usuario hace clic en el botón [!UICONTROL Mostrar más elementos de trabajo] en un tablero de exploración, luego se desplaza para ver los nuevos artículos, la variable [!UICONTROL Mostrar más elementos de trabajo] la barra se fija a la placa de desplazamiento y se mueve con ella al desplazarse. Esto puede hacer que las cartas sean difíciles de leer.

**Aparecen puntos rojos en los campos obligatorios en los formularios personalizados**

Formularios personalizados

Cuando un usuario ve un campo obligatorio en un formulario personalizado, ve dos puntos rojos debajo del asterisco que indican que el campo es obligatorio.

**Menú desplegable de tiempo cortado en mensajes**

*Informes*

Cuando un usuario está rellenando las solicitudes de un informe y encuentra un selector de fechas, el selector de horas situado en la parte inferior del selector de fechas no muestra las horas posteriores a las 2 y el usuario no puede seleccionar ningún valor de hora que no sea 1 o 2.

+++

+++**Actualización de mantenimiento (corrección) el 29 de marzo de 2022**

**No se pueden modificar ni guardar cálculos en el Creador de formularios personalizados**

*Formularios personalizados de mi grupo*

Si un usuario introduce manualmente un cálculo en un campo de cálculo del Creador de formularios personalizados y lo guarda, el cálculo no se guarda. Si el usuario vuelve a abrir el formulario personalizado, ese campo está en blanco.

Si un usuario introduce un cálculo en un campo de cálculo del Creador de formularios personalizados mediante los menús desplegables y guarda el formulario, se guarda ese valor. Sin embargo, si el usuario vuelve a abrir el formulario personalizado, no puede editar este campo ni quitar el valor, ni manualmente ni con la lista desplegable.

NOTA: Esta corrección del problema incluye funcionalidad adicional. Ahora, cuando empieza a escribir en un campo calculado, las posibles expresiones o cálculos se muestran en un menú desplegable inferior, del mismo modo que en el Editor de cálculos. Haga clic en un elemento de la lista desplegable para agregarlo al campo calculado.

+++

+++**Actualización de mantenimiento del 24 de marzo de 2022**

**Zonas horarias no coherentes entre [!DNL Workfront] y[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Cuando el perfil de un usuario está establecido en una zona horaria específica en [!DNL Workfront], la zona horaria del usuario en [!DNL Workfront Proof] está configurada en una zona horaria diferente.

**Error de campo obligatorio para campos personalizados rellenados al adjuntar una plantilla**

*Proyectos*

Al adjuntar una plantilla con campos personalizados requeridos a un proyecto en el que el campo ya existe y está rellenado, los usuarios ven el siguiente error: &quot;[!UICONTROL Hay campos incompletos. Introduzca valores para los campos obligatorios antes de continuar.]&quot; Haciendo clic en &quot;[!UICONTROL Llévame allí]&quot; les permite ver que los campos están rellenados y que pueden adjuntar la plantilla correctamente.

**La variable [!UICONTROL Equilibrador de carga de trabajo] parpadea al alternar entre fechas**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Las horas del usuario que aparece primero en la sección [!UICONTROL Equilibrador de carga de trabajo] no se muestra al actualizar la línea de tiempo. El usuario y sus horas se muestran con todos los cuadros grises que parpadean. Esto sucede si se mueve hacia adelante y hacia atrás en la cronología.

La actualización del filtro parece restablecer la visualización. Sin embargo, al moverse hacia atrás y hacia adelante en la línea de tiempo, se vuelve a mostrar el flash y no se muestran las horas del usuario.

**La terminología personalizada no es coherente**

*Plantillas de diseño*

Los usuarios informan de que cuando la variable [!DNL Workfront] El administrador personaliza la terminología de algunos objetos mediante una plantilla de diseño; el nuevo nombre de objeto aparece de forma incoherente en la interfaz.

Por ejemplo, en la [!UICONTROL Proyectos] , puede ver el título de la página como &quot;[!UICONTROL Proyectos]&quot;, aunque la variable [!DNL Workfront] el administrador ha cambiado el nombre de &quot;[!UICONTROL Proyectos]&quot; a otra cosa.

Esto causa confusión para los usuarios finales.

+++

+++**Actualización de mantenimiento del 17 de marzo de 2022**

**Las miniaturas y las imágenes principales están en blanco al ver archivos de varias páginas mediante [!DNL Safari] explorador**

*[!DNL Workfront Proof]*

Cuando un usuario intenta ver un archivo con varias páginas en la variable [!DNL Safari] explorador, las imágenes de página en miniatura están en blanco. En ocasiones, la imagen principal también puede estar en blanco.

**Lista de usuarios incorrecta al realizar asignaciones masivas en el [!UICONTROL Equilibrador de carga de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario realiza una asignación masiva en la [!UICONTROL Equilibrador de carga de trabajo] y selecciona un proyecto y una función de trabajo, la lista de usuarios disponibles es incorrecta. Puede mostrar usuarios sin la función de trabajo o los permisos del proyecto, y los usuarios con la función de trabajo y los permisos del proyecto no aparecen en la lista.

**[!UICONTROL La ordenación no funciona en los informes]**

*Informes*

Cuando un usuario hace clic en una columna para ordenarla, la clasificación parece funcionar, pero instantáneamente los resultados vuelven a la clasificación original tal como se muestra antes de hacer clic en la columna. No se conserva la ordenación de ninguna columna.

**Seleccionar &quot;[!UICONTROL Nada]&quot; vuelve al [!UICONTROL Informe predeterminado] agrupación**

*Informes*

Cuando un informe tiene una agrupación integrada y el usuario intenta seleccionar &quot;[!UICONTROL Nada]&quot; en el [!UICONTROL Agrupación] menú desplegable, el informe se muestra en breve sin agrupar y, a continuación, vuelve al [!UICONTROL Informe predeterminado] agrupación.

**Se ha eliminado &quot;[!UICONTROL Acceso a modelos]&quot; pestaña de las preferencias de modelos**

*Modelos*

NOTA: Este problema solo existe en el entorno de Vista previa.

La variable [!UICONTROL Acceso a modelos] se ha eliminado del modal de preferencias de modelos. No se ha eliminado ninguna funcionalidad de las preferencias de modelos.

+++

+++**Actualización de mantenimiento (corrección) el 14 de marzo de 2022**

**No se puede desplazar hacia abajo en la lista de usuarios al realizar la asignación en el panel Kanban**

*Águila*

Cuando un usuario está viendo un [!DNL Kanban] tablero e intenta realizar una asignación, la lista de usuarios que aparece cuando escriben continúa saltando hacia arriba a medida que se desplazan hacia abajo. El usuario no puede seleccionar un usuario que no esté cerca de la parte superior de la lista y no puede guardar el cambio de asignación.

**[!UICONTROL Milestone] Ver en el informe de proyecto causa un error**

*Informes*

Al mostrar un informe de proyecto con la variable [!UICONTROL Milestone] Ver, los usuarios reciben un &quot;[!UICONTROL APIModel INTERNAL no admite namedQuery TILE:milestone-view (UIVW)]&quot; error.

**La terminología personalizada no es coherente**

*Plantillas de diseño*

Los usuarios informan de que cuando la variable [!DNL Workfront] El administrador personaliza la terminología de algunos objetos mediante una plantilla de diseño; el nuevo nombre de objeto aparece de forma incoherente en la interfaz.

Por ejemplo, en la [!UICONTROL Proyectos] , puede ver el título de la página como &quot;[!UICONTROL Proyectos]&quot;, aunque la variable [!DNL Workfront] el administrador ha cambiado el nombre de &quot;[!UICONTROL Proyectos]&quot; a otra cosa.

Esto causa confusión para los usuarios finales.

**No se pueden actualizar los cálculos para campos calculados existentes**

*Formularios personalizados*

Los usuarios no pueden actualizar o cambiar los cálculos en los campos calculados. Si el campo se ha creado y guardado con sin cálculo, cada vez que intente agregar una expresión y guardar/aplicar, el generador vuelve a estar en blanco.

Si crea un campo calculado con una expresión determinada y la guarda, cada vez que intenta cambiar el cálculo, vuelve a su valor anterior.

**[!UICONTROL Parámetro no válido] error al restablecer contraseñas**

*Inicio de sesión*

Los usuarios no pueden restablecer sus contraseñas en ningún entorno. Cuando escriben su correo electrónico e intentan continuar, ven un error.

[!UICONTROL Error: Parámetro no válido: Valor del parámetro de búsqueda &quot;domain&quot;].

+++

+++**Actualización de mantenimiento del 10 de marzo de 2022**

**Problemas al iniciar sesión en el entorno de vista previa**

*Inicio de sesión*

Se han notificado los siguientes problemas con el inicio de sesión en el entorno de vista previa.

Cuando un usuario intenta iniciar sesión en el entorno de vista previa, aparece un mensaje que indica que ha introducido el ID o la contraseña incorrectos.

Cuando un usuario intenta restablecer su contraseña, aparece el error &quot;[!UICONTROL ?Se encontraron varios usuarios con la dirección de correo electrónico <example@example.com>?]&quot;

**Los formularios personalizados se cargan lentamente en [!UICONTROL Detalles del proyecto] area**

*Proyectos*

Cuando un usuario intenta ver el [!UICONTROL Detalles del proyecto] , los formularios personalizados que estén adjuntos al proyecto se cargarán solo después de un retraso de 15 segundos o más. La variable [!UICONTROL Agregar formularios personalizados] también se ve afectada por este retraso.

**Los valores de los campos de formulario personalizados no se guardan en el panel de resumen del documento**

*Documentos*

Cuando un usuario actualiza los campos de formulario personalizados en el panel de resumen del documento y uno o más de ellos es un campo de tipo &quot;delante&quot;, y luego guarda los cambios y se desplaza fuera del panel de resumen, las actualizaciones no se guardan. Esto solo se produce cuando se edita un campo typeforward, aunque todos los campos se ven afectados.

**Datos que no se conservan al convertir plantillas debido a niveles de acceso de uso compartido de plantillas**

*Proyectos*

Cuando un usuario que tiene acceso a Vista en una plantilla compartida intenta convertir un problema en un proyecto, cualquier dato de secciones de formulario personalizadas que requiera [!UICONTROL Contribución] o el acceso superior a la vista no se transfiere al proyecto creado.

**Error al cargar la nueva versión del documento**

*Documentos*

Cuando un usuario intenta cargar una nueva versión de un documento desde la lista de documentos, el documento no se carga y el usuario ve el siguiente error:

[!UICONTROL Error No se puede invocar &quot;com.attask.boz.Document.getCurrentVersion()&quot; porque &quot;documento&quot; es nulo]

**No se pueden editar las tasas de facturación**

*Proyectos*

Cuando un usuario intenta editar una tasa de facturación en la variable [!UICONTROL Tasas de facturación] de un proyecto, haga clic en la pestaña [!UICONTROL Editar] abre [!UICONTROL Editar] se cierra brevemente antes de que el usuario pueda editar la tasa de facturación. Al volver a hacer clic en el botón no se abre la ventana de edición.

**El vínculo público para el documento lleva a una página en blanco**

*Documentos*

Cuando un usuario intenta abrir un documento mediante un vínculo público, el vínculo lleva a una página en blanco. Esto ocurre cuando el vínculo se abre en una ventana en la que una [!DNL Workfront] la sesión está abierta.

**Error Whops al añadir tarea o problema a la lista**

*Tareas y problemas*

Cuando un usuario que no es administrador intenta agregar una tarea o problema a una lista y rellena campos personalizados, la tarea o el problema no se crea y el usuario ve el siguiente error:

[!UICONTROL Error Whoops! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]

**Si se deja una actualización después de un cambio de estado, el objeto se convierte en un estado anterior**

Proyectos, tareas y problemas

Si se cambia el estado de un proyecto, tarea o problema y se empieza inmediatamente a escribir una actualización sin actualizar la página, el cuadro de actualización muestra el estado anterior. Si se publica la actualización, el objeto vuelve al estado anterior.

**Los usuarios agregados a las pruebas tienen funciones incorrectas**

*Pruebas*

Cuando un usuario agrega otro usuario a una prueba, la función de ese usuario en la prueba se establece como &quot;[!UICONTROL Solo lectura]&quot; a pesar de la función de prueba real del usuario.

Solución alternativa: Establezca la función de prueba del usuario en su perfil en otra cosa y, a continuación, restablezca la función correcta.

**El formulario personalizado no se carga al convertir un problema a un proyecto mediante una plantilla**

*Formularios personalizados de mi grupo*

Cuando un usuario intenta convertir un problema en un proyecto mediante una plantilla, es posible que uno o más de los formularios personalizados adjuntos a la plantilla no se carguen. Cuando el usuario configura la plantilla para el nuevo proyecto, en lugar de los formularios personalizados, ve el siguiente mensaje:

&quot;[!UICONTROL Se ha producido un error, no se pudo cargar el formulario].&quot;

**El usuario no puede agregar problemas en línea con el campo desplegable personalizado que se muestra en la vista**

*Listas*

Cuando un usuario añade un problema desde línea y hay una vista personalizada con campos desplegables personalizados aplicados a la lista, se produce un error cuando solo rellenan el campo desplegable. El usuario tiene acceso para editar formularios personalizados y es el propietario del proyecto con derechos de administración del proyecto.

[!UICONTROL Error: ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] ¡así que podemos averiguar qué salió mal y arreglarlo!]

**Los permisos para agregar tareas a un proyecto no son necesarios para mover o copiar una tarea al proyecto**

*Tareas*

Ahora puede mover o copiar una tarea a otra tarea de un proyecto sin tener permisos para agregar tareas al proyecto de destino. Debe tener permisos para agregar tareas al menos a una de las tareas del proyecto de destino. Antes de esta actualización, era necesario tener permisos para agregar tareas al proyecto para mover o copiar una tarea al proyecto o a cualquiera de sus tareas.  Esta actualización ya está disponible en el entorno de producción. Ha estado disponible en el entorno de vista previa a partir de la actualización de mantenimiento del 24 de marzo de 2022.

NOTA: Esta actualización estará disponible en el entorno Producción al copiar o mover problemas después de la versión de Producción 22.2. Para obtener más información sobre la versión actual, consulte workfront.com/release.

**El menú desplegable Preguntar está desactivado**

*Informes*

Cuando se utiliza una solicitud en un informe, se cortan los menús desplegables que permiten seleccionar los criterios de filtrado para el informe. Como resultado, no se muestran los criterios de la parte inferior del menú desplegable de selección.

**El elemento de trabajo vuelve al estado anterior cuando se realiza una actualización**

*Actualizaciones*

Cuando un usuario cambia el estado de un elemento de trabajo en el encabezado, el estado no se actualiza en la variable [!UICONTROL Actualizar] . Si el usuario realiza una actualización, la lista desplegable sigue mostrando el estado anterior. Cuando se guarda la actualización, este estado anterior e incorrecto sobrescribe el estado establecido en el encabezado.

+++

+++**Actualización de mantenimiento el 3 de marzo de 2022**

**No se puede agregar el documento desde[!DNL Google Drive]**

*Documentos*

Cuando un usuario intenta agregar un documento desde [!DNL Google Drive], la selección no responde y el usuario no puede seleccionar documentos para agregar.

**Los usuarios etiquetados no se agregan al subproceso de actualización**

*Actualizaciones*

Cuando se etiqueta a un usuario en una actualización, no se muestra en el[!UICONTROL Hasta]&quot; de la actualización o de sus respuestas.

**El usuario de prueba tiene dos cuentas de prueba independientes**

*[!DNL Workfront Proof]*

Una dirección de correo electrónico del usuario en [!DNL Workfront Proof] puede estar en dos cuentas independientes con ID distintos, lo que proporciona al usuario dos cuentas. Esto puede dificultar la localización de la cuenta correcta.

**Se muestra el error Whops en los encabezados de los informes**

*Informes*

Cuando un usuario ve un informe, aparece el siguiente error en el encabezado del informe:

&quot;[!UICONTROL Intentemos de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]&quot;

Si el usuario está viendo un tablero, el error puede aparecer en el encabezado de todos los informes del tablero.

**Los datos de los campos Solo edición de administración de formulario personalizado no se conservan al convertir problemas en proyectos**

*Proyectos*

Cuando un usuario no administrador intenta convertir un problema a un proyecto mediante una plantilla y el problema contiene datos en campos que solo un administrador puede editar, los datos de esos campos no se transfieren al nuevo proyecto.

Cuando un administrador convierte el problema, los datos se transmiten al nuevo proyecto según lo esperado.

**[!DNL XLS]y [!DNL XLSX] el límite de tamaño de archivo disminuyó temporalmente a 100 MB para pruebas**

*Revisión*

Para solucionar un problema de seguridad, hemos limitado temporalmente el tamaño máximo de archivo para [!DNL XLS] y [!DNL XLSX] a 100 MB al crear una prueba.

NOTA: Esta actualización se realizó en el entorno de vista previa el 24 de febrero y estará en el entorno de producción el 3 de marzo.

**Actualización a Workfront Search**

Buscar

Esta semana comenzó un despliegue gradual para actualizar la infraestructura de [!DNL Workfront] Funcionalidad de búsqueda. La actualización hará que las futuras mejoras en Buscar sean más sencillas y fiables. Con estos cambios, los elementos se agregaron a [!DNL Workfront] se indexarán más rápido y, por lo tanto, regresarán antes en los resultados de búsqueda.

La implementación por fases continuará durante 2 semanas.

**Barras de herramientas actualizadas para informes dentro de tableros**

Informes

Los informes incluidos en los tableros ahora muestran una nueva barra de herramientas. Esta barra de herramientas forma parte de las actualizaciones a listas e informes que se producen a lo largo de [!DNL Workfront].

+++


## Actualizaciones en febrero de 2022

+++**Actualización de mantenimiento (corrección) el 24 de febrero de 2022**

**Datos que no se conservan al convertir problemas en proyectos si el campo está oculto en la plantilla**

*Proyectos*

Cuando un usuario convierte un problema en una plantilla y esta incluye un formulario personalizado que muestra u oculta campos basados en los valores de otros campos, cualquier dato de los campos que esté oculto en la plantilla (sin datos) en el momento de la conversión no se lleva al nuevo proyecto.

**No se puede exportar el planificador de recursos por función**

*Planificador de recursos*

Cuando un usuario intenta exportar la variable [!DNL Resource Planner] al usar la variable [!UICONTROL Ver por función] , la exportación no se realiza correctamente y el usuario recibe un correo electrónico con el siguiente mensaje:

Error al exportar su [!DNL Resource Planner] datos.

**El botón Copiar solicitud no funciona**

*Solicitudes*

Cuando un usuario intenta copiar una solicitud, la variable [!UICONTROL Copiar solicitud] no funciona si el usuario no tiene acceso de visualización al tema de la cola.

+++

+++**Actualización de mantenimiento del 24 de febrero de 2022**

**Los datos de formulario personalizados desaparecen cuando se rellenan otros campos de formulario**

*Formularios personalizados de mi grupo*

Cuando un usuario rellena un formulario personalizado como parte de la conversión de un problema a un proyecto, rellenar un campo personalizado puede hacer que desaparezcan los datos de otro campo personalizado. Si el usuario vuelve a introducir los datos que faltan, cuando intenta crear el proyecto, verá el siguiente mensaje de error:

&quot;[!UICONTROL Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado]&quot;

**&quot;[!UICONTROL Este proceso de aprobación puede ser utilizado por...]&quot; campo no disponible**

*Rutas de aprobación*

Cuando un usuario está creando o editando un proceso de aprobación en la [!UICONTROL Configuración] , la variable[!UICONTROL Este proceso de aprobación puede ser utilizado por...]Falta el campo &quot;. Esto puede ocurrir al crear un proceso de aprobación o al editar uno existente.

**El administrador del sistema no puede reasignar usuarios al eliminar un grupo**

*Grupos*

Cuando un administrador del sistema elimina un grupo, solo tendrá la opción de reasignar los usuarios de ese grupo a grupos para los que el administrador del sistema sea un administrador de grupo. Otros grupos no aparecen en la lista desplegable y el administrador no puede seleccionarlos.

**Error al convertir un problema en un proyecto**

*Proyectos*

Cuando un usuario intenta convertir un problema en un proyecto mediante una plantilla y agrega o quita formularios personalizados de la plantilla, el problema no se convierte y el usuario ve el siguiente mensaje:

[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]

**No se puede abrir la prueba; actualizaciones de página**

*Pruebas*

Cuando un usuario intenta abrir una prueba, esta no se puede abrir. Finalmente, la página se actualiza.

**[!DNL XLS]y [!DNL XLSX] el límite de tamaño de archivo disminuyó temporalmente a 100 MB para pruebas**

*Revisión*

Para solucionar un problema de seguridad, hemos limitado temporalmente el tamaño máximo de archivo para [!DNL XLS] y [!DNL XLSX] a 100 MB al crear una prueba.

NOTA: Esta actualización se realizará en el entorno de vista previa el 24 de febrero y en el entorno de producción el 3 de marzo.

**Los permisos para agregar tareas o problemas a un proyecto no son necesarios para mover o copiar una tarea o un problema en el proyecto**

*Proyectos*

Ahora puede mover o copiar una tarea o un problema en otra tarea de un proyecto sin tener permisos para agregar tareas o problemas al proyecto de destino. Debe tener permisos para agregar tareas o problemas al menos a una de las tareas del proyecto de destino. Antes de esta actualización, era necesario tener permisos para agregar tareas o problemas al proyecto para mover o copiar una tarea o un problema al proyecto o a cualquiera de sus tareas. Esta actualización solo está disponible en el entorno de Vista previa.

NOTA: Esta actualización estará disponible en el entorno Producción al realizar o mover tareas el 10 de marzo. Esta actualización estará disponible en el entorno Producción al copiar o mover problemas con la versión Producción 22.2. Para obtener más información sobre la versión actual, consulte workfront.com/release.

**Actualización a Workfront Search**

*Buscar*

Esta semana comenzó un despliegue gradual para actualizar la infraestructura de [!DNL Workfront] Funcionalidad de búsqueda. La actualización hará que las futuras mejoras en Buscar sean más sencillas y fiables. Con estos cambios, los elementos se agregaron a [!DNL Workfront] se indexarán más rápido y, por lo tanto, regresarán antes en los resultados de búsqueda.

La implementación por fases continuará durante 2 semanas.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 18 de febrero de 2022**

**Se agregó la validación de tipo de valor de campo a [!DNL Anaplan] propiedades de elementos de lista**

*[!DNL Adobe Workfront Fusion]*

Se ha corregido un problema que permitía a los usuarios colocar el tipo de datos incorrecto en campos para las propiedades de elementos de lista. La validación del tipo de propiedad permite [!DNL Fusion] para garantizar que se envía a Anaplan el tipo de datos correcto, se eliminan los errores causados por tipos de datos incorrectos.

+++

+++**Actualización de mantenimiento el 17 de febrero de 2022**

**Error al eliminar el predecesor de la pestaña Predecesores**

*Tareas*

Cuando un usuario intenta eliminar un predecesor del [!UICONTROL Predecesores] en una tarea, la tarea no se elimina y el usuario ve el siguiente error:

[!UICONTROL No se encuentra la tarea con los valores de clave principal &quot;&quot;]

**Error al abrir la página de usuarios**

*Usuarios*

Cuando un usuario intenta abrir el [!UICONTROL Usuarios] , la página no se abre y el usuario ve el siguiente error:

[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] podemos averiguar qué salió mal y arreglarlo.]

**Superposición de elementos en el encabezado de un informe en un tablero**

*Paneles*

Cuando un usuario ve un informe en un tablero, ve que el icono de agrupación y la etiqueta se superponen con los vínculos a [!UICONTROL Detalles] y [!UICONTROL Resumen].

**Problemas con &quot;[!UICONTROL Más]&quot; para documentos y pruebas**

*Documentos*

Cuando un usuario selecciona un documento o una prueba en un [!DNL Workfront Classic] lista de documentos y, a continuación, hace clic en &quot;[!UICONTROL Más],&quot; pueden ver uno de los siguientes problemas: El botón no responde Todas las opciones bajo el botón están etiquetadas como &quot;[!UICONTROL objeto]&quot; y no se pueden usar.

**Error &quot;Debe ser administrador del sistema&quot; al crear un proyecto**

*Proyectos*

Cuando un usuario que no es administrador intenta crear un proyecto y adjunta un formulario personalizado que tiene una sección disponible solo para los administradores, no puede crear el proyecto y verá el siguiente error:

&quot;Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado&quot;

**Los datos de la sección de solo administración del formulario personalizado no se conservan al convertir problemas en proyectos**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto mediante una plantilla que tiene un formulario personalizado con una sección de solo administración, los datos de la sección de solo administración no se transfieren al nuevo proyecto. Esto ocurre incluso si un administrador está convirtiendo el problema.

+++

+++**Actualización de mantenimiento el 10 de febrero de 2022**

**&quot;[!UICONTROL Debe ser administrador del sistema]&quot; error al crear un proyecto**

*Proyectos*

Cuando un usuario que no es administrador intenta crear un proyecto y adjunta un formulario personalizado que tiene una sección disponible solo para los administradores, no puede crear el proyecto y verá el siguiente error:

&quot;[!UICONTROL Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado]&quot;

**Los usuarios desactivados y reactivados no aparecen en [!UICONTROL Probar contactos]**

*[!DNL Workfront Proof]*

Cuando un usuario ve su lista de contactos en [!DNL Workfront Proof], los usuarios desactivados y reactivados no aparecen en la lista.

**Mensaje &quot;Se ha producido un error&quot; al convertir un problema en un proyecto mediante una plantilla**

*Proyectos*

Cuando un usuario que no es administrador intenta convertir un problema en un proyecto mediante una plantilla, los campos de formulario personalizados que solo son visibles para los administradores muestran el siguiente mensaje:

&quot;[!UICONTROL Se ha producido un error, no se pudo cargar el formulario]&quot;

**Error &quot;No se puede cargar el contenido de la página&quot; al ver las preferencias del proyecto**

*Configurar*

Cuando un usuario administrador intenta ver proyectos, tareas o problemas en [!UICONTROL Preferencias de proyecto] en el [!UICONTROL Configuración] , la página no se carga y el usuario ve el siguiente error:

&quot;[!UICONTROL No se puede cargar el contenido de la página. Pruebe a actualizar la página.]&quot;

+++

+++**Actualización de mantenimiento el 3 de febrero de 2022**

**[!UICONTROL BizContext] error al iniciar sesión**

*Inicio de sesión*

Cuando un usuario intenta iniciar sesión en [!DNL Workfront], el inicio de sesión no se ha realizado correctamente y aparece el siguiente mensaje:

&quot;[!UICONTROL Intentemos de nuevo. Error de base de datos: Error en la confirmación de BizContext.]&quot;

Esto se ha informado en el entorno de vista previa.

**El flujo de actualización del problema desaparece si el problema está pendiente de aprobación**

*Actualizaciones*

Cuando un usuario hace clic en el [!UICONTROL Nueva actualización] en el flujo de actualización de un problema que está pendiente de aprobación, desaparece todo el flujo de actualización.

**Error al cargar la nueva versión de un documento**

*Documentos*

Cuando un usuario intenta cargar una nueva versión de un documento, la nueva versión no se carga y el usuario ve uno de los siguientes errores:

* [!UICONTROL documentID no puede ser nulo]
* [!UICONTROL Error: Parámetro no válido: valor &quot;undefined&quot; de documentID]

**El vínculo público para el documento lleva a una página en blanco**

*Documentos*

Cuando un usuario intenta abrir un documento mediante un vínculo público, el vínculo lleva a una página en blanco. Esto ocurre cuando el vínculo se abre en una ventana en la que una [!DNL Workfront] la sesión está abierta.

**Los controles de lista no funcionan en los informes de los tableros**

*Paneles*

Cuando un usuario está viendo un informe en un tablero e intenta cambiar el filtro, la agrupación o la vista del informe, el filtro, la agrupación o la vista no cambian.

**&quot;[!UICONTROL Debe ser administrador del sistema]&quot; error al crear un proyecto**

*Proyectos*

Cuando un usuario que no es administrador intenta crear un proyecto y adjunta un formulario personalizado que tiene una sección disponible solo para los administradores, no puede crear el proyecto y verá el siguiente error:

&quot;[!UICONTROL Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado]&quot;

**Los datos personalizados no se conservan al convertir un problema en un proyecto**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, los datos de un formulario personalizado sobre el problema no se transfieren al formulario personalizado comparable del proyecto. Esto sucede con los datos de campos personalizados que pueden estar ocultos en función de los valores de otros campos personalizados.

**Error al convertir el problema al proyecto**

*Proyectos*

Cuando un usuario intenta convertir un problema en un proyecto, el problema no se convierte y ve el siguiente error:

&quot;[!UICONTROL Se produjo un error inesperado]&quot;

+++


## Actualizaciones de enero de 2022

+++**Actualización de mantenimiento el 27 de enero de 2022**

**Los datos personalizados no se conservan al convertir un problema en un proyecto**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, los datos de un formulario personalizado sobre el problema no se transfieren al formulario personalizado comparable del proyecto. Esto sucede con los datos de campos personalizados que pueden estar ocultos en función de los valores de otros campos personalizados.

**La lista de usuarios en el tablero ágil no es alfabética**

*Águila*

Cuando un usuario ve la lista de usuarios en un tablero ágil, los usuarios no se muestran en orden alfabético. En su lugar, se muestran primero los usuarios con la mayor cantidad de asignaciones.

**Vínculos actualizados para copiar y mover problemas**

*Problemas*

En el entorno de Vista previa, los vínculos para copiar y mover problemas se han actualizado a &quot;[!UICONTROL Copiar en]&quot; y &quot;[!UICONTROL Mover a]&quot; tanto en la página de problemas como en una lista de problemas.

**Añada hasta 45 direcciones IP a su [!DNL Workfront] lista de permitidos**

*Configurar*

El límite de direcciones IP agregadas a su [!DNL Workfront] La lista de permitidos ha aumentado de 30 a 45.

+++

+++**Actualización de mantenimiento el 20 de enero de 2022**

**&quot;[!UICONTROL Parámetro no válido]&quot; error al crear el proyecto a partir de la plantilla**

*Proyectos*

Cuando un usuario intenta crear un proyecto a partir de una plantilla y quita un formulario personalizado de la plantilla al crear el proyecto, el proyecto no se crea y el usuario ve un &quot;[!UICONTROL Parámetro no válido]&quot; mensaje de error que menciona un campo obligatorio en el formulario personalizado eliminado.

**La lista de usuarios no se carga en [!DNL Safari] explorador**

*Usuarios*

Cuando un usuario va al [!UICONTROL Usuarios] , aparece el encabezado pero la lista de usuarios no se carga.

**El retraso al arrastrar tareas en una lista hace que la tarea se mueva a una ubicación incorrecta**

*Listas*

Cuando un usuario intenta mover una tarea a una lista arrastrándola, la línea azul que indica a dónde se moverá la tarea se mueve mucho más lentamente que el cursor. Cuando el usuario libera la tarea, esta se mueve a donde está la línea azul, incluso si el cursor señala a una ubicación diferente en la lista.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 14 de enero de 2022**

**Algunos campos asignados se restablecen al seleccionar [!UICONTROL nuevo campo para asignar]**

*[!DNL Workfront Fusion]*

Cuando al menos un campo de la sección [!DNL Workfront] [!UICONTROL Crear] o [!UICONTROL Actualizar] Los módulos tienen habilitada la asignación y un usuario selecciona un nuevo campo para asignar, los campos asignados anteriormente que están habilitados para la asignación pierden valores de asignación.

+++

+++**Actualización de mantenimiento el 13 de enero de 2022**

**No se puede agregar un hipervínculo a un comentario en el panel Resumen**

*Tareas*

Cuando un usuario realiza un comentario en el panel de resumen de una tarea e intenta agregar un hipervínculo al comentario, la ventana de hipervínculo se abre, pero en cuanto el usuario hace clic en la ventana, se cierra y el usuario no puede agregar un hipervínculo. Si un usuario se desplaza por la ventana, puede escribir o pegar un vínculo en el campo, pero el hipervínculo no se guarda. En ambos casos, la tarea deja de estar seleccionada.

**La página Editar equipo no se cierra**

*Equipos*

Cuando un usuario intenta editar un equipo, la variable [!DNL Edit team] no se cierra. El usuario no puede cerrar la página haciendo clic en ninguno de los botones, haciendo clic en la X ni saliendo de la página.

**Las notificaciones por correo electrónico y en la aplicación no se envían**

*Notificaciones*

Cuando se produce un evento que debería generar el déclencheur de una notificación, esta no se envía. Esto puede ocurrir en el caso de las notificaciones por correo electrónico o en la aplicación, y puede ocurrir aunque se envíen otras notificaciones.

**[!UICONTROL Mi trabajo] la lista aparece vacía**

*[!UICONTROL Mi trabajo]*

Cuando un usuario ve sus [!UICONTROL Mi trabajo] y la plantilla de diseño para su [!UICONTROL Mi trabajo] incluye un valor numérico como [!UICONTROL Porcentaje completado], el [!UICONTROL Mi trabajo] no se muestra la lista.

**[!UICONTROL Porcentaje completado] y [!UICONTROL Horas de finalización] no se puede modificar en el tablero Agile**

*Águila*

Cuando el usuario selecciona &quot;[!UICONTROL Mostrar más elementos de trabajo]&quot; en el tablero Agile, luego intenta cambiar el [!UICONTROL Porcentaje completado] o [!UICONTROL Horas de finalización] en uno de los elementos de trabajo recién cargados, no pueden cambiar el porcentaje completado o la hora de finalización. La variable [!UICONTROL Porcentaje completado] también está en gris, lo que indica que está inactivo.

+++

+++**Actualización de mantenimiento el 6 de enero de 2022**

**&quot;[!UICONTROL Parámetro no válido]&quot; error al adjuntar plantillas o formularios personalizados a proyectos**

*Proyectos*

Cuando un usuario intenta adjuntar un formulario personalizado o una plantilla a un proyecto existente, rellena los campos obligatorios en el formulario o plantilla personalizados y guarda los cambios en el proyecto, los cambios no se guardan y el usuario ve un &quot;[!UICONTROL Parámetro no válido]&quot; error en la parte superior de la página de detalles del proyecto.

**Los comentarios de prueba no se muestran en las actualizaciones de documentos**

*Pruebas*

Cuando un usuario ve una prueba en la variable [!UICONTROL Documentos] , los comentarios realizados en la prueba no se muestran en la [!UICONTROL actualizaciones] del documento.

**[!UICONTROL Distribuidor de cargas de trabajo]: &quot;[!UICONTROL ?[objeto]?]&quot; aparece en la información de sobreasignación**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Si un usuario se muestra como sobreasignado en la variable [!UICONTROL Equilibrador de carga de trabajo] debido a que una tarea se superpone con el tiempo de espera del usuario y otro usuario ve su sobreasignación, la variable &quot;[!UICONTROL Capacidad]&quot; de la información de sobreasignación se muestra &quot;[!UICONTROL ?[objeto]?]&quot; en lugar de la capacidad real del usuario.

+++

## Actualizaciones de mantenimiento anteriores

La información sobre actualizaciones de mantenimiento anteriores está disponible aquí:

* [[!DNL Workfront] Archivo de actualizaciones de mantenimiento - 2021](2021-updates.md)
