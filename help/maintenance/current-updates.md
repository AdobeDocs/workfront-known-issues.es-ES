---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 7bb0987beff9127e4f5ebf82401f5243712f45f0
workflow-type: tm+mt
source-wordcount: '16738'
ht-degree: 97%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2022 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront]le avisará cuando haya solucionado un problema enviado por usted.

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

## Actualizaciones en diciembre de 2022

+++**Actualización de mantenimiento el 15 de diciembre de 2022**

**Actualizaciones de accesibilidad en listas**

*Listas*

Las siguientes funciones de accesibilidad ya están disponibles en listas:

* Las casillas de verificación de las listas ahora tienen un indicador de enfoque visible cuando se les aplica la tabulación. Esto facilita visualmente la navegación mediante el teclado de los elementos de una lista.
* Ahora, todos los botones de las barras de herramientas de la lista tienen estados coherentes de enfoque y desplazamiento, con un fondo gris al pasar el ratón y un fondo gris y un contorno azul al enfocar.
* Anteriormente, al abrir un menú desplegable en una lista con la tecla Espacio, se abría el menú y la página también se desplazaría hacia abajo un poco, lo que no estaba previsto. Ahora la página ya no se desplaza al pulsar Espacio en una lista desplegable, que es el comportamiento deseado correcto.
* Al ver una lista con la casilla de verificación de fila seleccionada, ahora puede tabular cada elemento editable y, a continuación, presionar la tecla Espacio para cambiar al modo de edición y comenzar a editar esa celda en la fila. Anteriormente, estos elementos no eran navegables mediante el teclado y requerían el uso de un ratón. Ahora, cambiar al modo de edición es fácil para el ratón y el teclado.

**&quot;[!UICONTROL Whoops]&quot; error al crear un proyecto a partir de una plantilla**

*Proyectos*

Cuando un usuario intenta crear un proyecto a partir de una plantilla, el proyecto no se crea y el usuario ve el error siguiente:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo]”.

**El gráfico de combinación muestra los mismos datos dos veces**

*Informes*

Cuando un usuario ve un gráfico combinado, este muestra un conjunto de valores dos veces en lugar de comparar dos conjuntos de valores diferentes. Los conjuntos de valores correctos están en los detalles del informe.

**Se ha añadido información sobre herramientas para celdas de hora atenuadas en hojas de horas**

*Plantillas de horas*

Se han añadido informaciones de objeto para explicar el motivo por el que una celda de hora puede estar atenuada en un parte de horas. Por ejemplo, algunas de las razones podrían deberse a que el parte de horas está cerrado o a que el proyecto se ha completado.

**Usuarios desactivados disponibles al seleccionar el aprobador de plantillas de horas**

*Plantillas de horas*

Cuando un usuario está creando una plantilla de horas e intenta asignar un aprobador, la lista desplegable incluye a los usuarios desactivados. Si se selecciona un usuario desactivado, la plantilla de horas no se guarda y el usuario ve el siguiente mensaje:

“[!UICONTROL Error. Lo sentimos, solo los usuarios con licencia de Plan pueden aprobar o rechazar plantillas de horas. Póngase en contacto con el administrador del sistema]”.

Dado que el usuario desactivado no se puede asignar, el usuario debe seleccionar un usuario activado. Por lo tanto, la plantilla de horas funciona según lo esperado, pero los usuarios desactivados de la lista pueden causar confusión o inconvenientes al usuario.

**No se puede introducir la hora en el parte de horas**

*Plantillas de horas*

Cuando un usuario intenta agregar las horas en una plantilla de horas, observa que las casillas para las horas de cualquier columna de Hora de proyecto u Hora de tarea aparecen atenuadas y no puede introducir las horas en estas casillas. Solo puede introducir las horas en el área de la Hora general.

+++

+++**Actualización de mantenimiento el 8 de diciembre de 2022**

**Selección inteligente del usuario al añadir aprobadores a una ruta de aprobación**

*Rutas de aprobación*

Hemos mejorado la forma en que se muestran los usuarios al agregarlos al [!UICONTROL Aprobadores] de una nueva aprobación.

Ahora, cuando agregue un usuario al [!UICONTROL Aprobadores] de una aprobación de un solo uso o nivel de sistema, además de su nombre y avatar, también se muestran su función principal y su correo electrónico. Esto ayuda a distinguir entre varios usuarios con nombres similares o idénticos.

**El estado del proyecto no sigue las preferencias del proyecto de grupo**

*Proyectos*

Cuando un usuario crea un proyecto a partir de una plantilla, el nuevo proyecto no obtiene el estado establecido en las preferencias del proyecto de grupo. Si se crea un proyecto sin plantilla, el estado refleja las preferencias del proyecto de grupo según lo esperado.

**No se puede agregar la subtarea**

*Tareas*

Cuando un usuario intenta agregar una subtarea utilizando el botón “[!UICONTROL +Nueva]”, no aparece ninguna opción en la ventana [!UICONTROL Nueva tarea] y el usuario ve el mensaje siguiente:

“[!UICONTROL No se pueden leer las propiedades de indefinido (leer validaciones)]”

**Errores al cerrar o guardar plantillas de horas**

*Plantillas de horas*

Cuando un usuario intenta agregar horas en una plantilla de horas o cerrar dicha plantilla, la plantilla de horas no se guarda y el usuario ve los errores siguientes:

* Error de la base de datos debido a una instrucción SQL no válida.
* No se han guardado sus cambios recientes. Actualice la página para ver los últimos cambios guardados.

+++

+++**Actualización de mantenimiento (Hot Fix) el 1 de diciembre de 2022**

**Los errores de edición en línea producidos por el usuario no causan mensajes de error**

*Listas*

Cuando un usuario está editando en línea un objeto y produce un error que debería crear un mensaje de error, no aparece ningún mensaje de error. El error en sí no se guarda en Workfront, por lo que los datos no se ven afectados, pero la falta de un mensaje de error puede causar confusión.

Se ha informado de este problema para las siguientes situaciones:

* Predecesores: Se crea un bucle predecesor, como, por ejemplo, la asignación de una tarea a sí misma
* Fechas: Se establece una fecha imposible, como, por ejemplo, una fecha de finalización anterior a la fecha de inicio o posterior a la fecha de finalización del proyecto

**La opción “Mover a” no está disponible en los informes de problemas**

*Informes*

Cuando un usuario está viendo un informe de problemas e intenta mover un problema, la opción “Mover a” no está disponible en el menú Más (tres puntos).


**No se puede cerrar la tarjeta de usuario en el flujo de actualización del estado**

*Actualizaciones*

Cuando un usuario está viendo las actualizaciones y pasa el ratón por encima de un nombre, se abre una tarjeta con detalles sobre el usuario del que se trata y no se cierra automáticamente. La página no responde hasta que se cierra manualmente la tarjeta haciendo clic en la X de la esquina superior derecha.


+++

+++**Actualización de mantenimiento el 1 de diciembre de 2022**

**La tarea tiene un registro de asuntos pendientes de Kanban de 0**

*Agile*

Cuando un usuario está viendo el registro de asuntos pendientes de un equipo de Kanban, una o más de las tareas muestran un registro de asuntos pendientes de 0.

**Mensaje de “[!UICONTROL Expresión personalizada no válida]” al añadir una referencia al “[!UICONTROL propietario]” en un campo calculado**

*Formularios personalizados*

Cuando un usuario añade un campo calculado a un formulario personalizado de nivel de problema e intenta añadir referencias a un “[!UICONTROL propietario]” (como “`ownerID`”), el campo no se guarda y el usuario ve el siguiente mensaje:

“[!UICONTROL La expresión personalizada no es válida, inténtelo de nuevo.]”

Esto ocurre incluso cuando la expresión es válida.

**No se puede acceder a los elementos de la integración de [!DNL Workfront for Jira]**

*Integraciones*

Actualmente no se puede acceder a los siguientes elementos de la integración de [!DNL Workfront for Jira] para [!DNL Jira Cloud]:

* La página [!UICONTROL Configuración]
* El botón “[!UICONTROL Abrir Workfront]” en un problema de [!DNL Jira]

**Al añadir un mensaje personalizado, se producen problemas en el visualizador de pruebas**

*Pruebas*

Cuando un usuario comparte una prueba e intenta añadir un mensaje personalizado, ocurre lo siguiente:

* El visualizador aumenta el tamaño de la prueba.
* La zona de navegación izquierda deja de responder.

**Usuarios desactivados disponibles al seleccionar el aprobador de plantillas de horas**

*Plantillas de horas*

Cuando un usuario está creando una plantilla de horas e intenta asignar un aprobador, la lista desplegable incluye a los usuarios desactivados. Si se selecciona un usuario desactivado, la plantilla de horas no se guarda y el usuario ve el siguiente mensaje:

“[!UICONTROL Error. Lo sentimos, solo los usuarios con licencia de Plan pueden aprobar o rechazar plantillas de horas. Póngase en contacto con el administrador del sistema]”.

Dado que el usuario desactivado no se puede asignar, el usuario debe seleccionar un usuario activado. Por lo tanto, la plantilla de horas funciona según lo esperado, pero los usuarios desactivados de la lista pueden causar confusión o inconvenientes al usuario.

**La plantilla de horas no se genera**

*Plantillas de horas*

Las plantillas de horas no se generan a pesar de la configuración del perfil de la plantilla de horas. Como la plantilla de horas nunca se genera, no está disponible para que el usuario introduzca la hora y no está visible en las listas.

+++

## Actualizaciones en noviembre de 2022

+++**Actualización de mantenimiento del 17 de noviembre de 2022**

**Documentos colocados en la [!UICONTROL Papelera de reciclaje] si no están seleccionados al mover una tarea o un problema**

*Documentos*

Ahora, cuando anula la selección de la opción [!UICONTROL Documentos] en el proceso de mover una tarea o un problema, los documentos adjuntos a la tarea o el problema se colocarán en la [!UICONTROL Papelera de reciclaje] durante 30 días. Un administrador puede restaurarlos, si es necesario. El usuario que anule la selección de Documentos en el proceso de movimiento recibirá una advertencia sobre este comportamiento en la ventana [!UICONTROL Mover tarea] o [!UICONTROL Mover problema]. Antes de esta mejora, los documentos se eliminaban permanentemente.

**Al ocultar un elemento, se oculta el elemento incorrecto**

*Plantillas de diseño*

Cuando un usuario cambia si se oculta o se muestra un elemento, los cambios se aplican a un elemento diferente de la plantilla de diseño.


+++

+++**Actualización de mantenimiento del 10 de noviembre de 2022**

**Las tareas de edición masiva cambian las asignaciones de tareas**

*Tareas*

Cuando un usuario edita masivamente cualquier campo en un conjunto de tareas, las Asignaciones de la primera tarea se aplican a todas las tareas. Esto elimina las asignaciones anteriores.

**No se puede abrir una prueba interactiva**

*Revisión de Workfront*

Cuando un usuario intenta abrir una prueba interactiva, la prueba no se carga y el usuario ve el siguiente mensaje:

“[!UICONTROL Prueba no cargada (501) Inténtelo de nuevo]”

+++

+++**Actualización de mantenimiento (Hot Fix) el 4 de noviembre de 2022**

**Problemas con las tareas agregadas a una iteración**

*Agile*

Se han notificado los siguientes problemas en relación con adiciones a una iteración:

* Algunas subtareas de una tarea agregadas a una iteración no aparecen en la página [!UICONTROL Iteración].
* Cuando un usuario intenta agregar un tarea que falta a la iteración, la tarea no se agrega y el usuario recibe el siguiente mensaje:

   “[!UICONTROL Se produjo el siguiente error: No se pudo mover ninguno de los elementos seleccionados porque no se han asignado a un equipo Agile o no son elementos Agile]”

**Las tareas asignadas mediante la edición masiva no aparecen en el registro de asuntos pendientes del equipo**

*Agile*

Cuando un usuario asigna tareas a un equipo de Scrum utilizando la edición masiva, esas tareas no aparecen en el registro de asuntos pendientes del equipo.

Los equipos de Kanban no se ven afectados por este problema.

**El cuadro de texto “[!UICONTROL Nuevos destinatarios de prueba]” es demasiado pequeño**

*Pruebas*

Cuando un usuario está viendo una prueba e intenta compartirla desde la pestaña [!UICONTROL Uso compartido], el cuadro de texto “[!UICONTROL Nuevos destinatarios de prueba]” es muy pequeño. El usuario puede escribir un nombre, pero como el cuadro es tan pequeño, el texto se ajusta de una manera difícil de leer.

**La información de uso del informe no se actualiza**

*Informes*

Cuando un usuario ve un informe, la información que vio por última vez, como la fecha de la última visualización y la última visualización de la visita, no se actualiza. Esto significa que cualquier información de uso puede ser incorrecta.

Se ha notificado este comportamiento cuando el usuario accede al informe de las siguientes maneras:

* Buscar
* Fijadores
* Favoritos
* Recientes

El acceso a los informes a través de un panel sí actualiza la información de la última visualización.

**[!DNL Workfront]: Error 500 al realizar cambios en un objeto [!DNL Workfront]**+

*[!DNL Workfront]*

Cuando un usuario intenta realizar cambios en un objeto [!DNL Workfront], los cambios no se guardan y el usuario ve el siguiente error:

“[!UICONTROL 500: Error de la base de datos debido a una instrucción SQL no válida.]”

Se ha informado de este problema en las siguientes situaciones:

* Cambiar el estado de un objeto
* Calcular de nuevo la cronología
* Adjuntar una plantilla
* Registrar la hora

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 3 de noviembre de 2022**

**Error sobre la [!UICONTROL apiKey] en el módulo [!DNL Workfront] > [!UICONTROL Ver eventos]**

*[!DNL Workfront Fusion]*

Cuando un usuario intenta agregar un webhook al módulo [!DNL Workfront] > [!UICONTROL Ver eventos] recibe el siguiente error:

“[!UICONTROL La apiKey proporcionada estaba vacía o se consideró no válida.]”

+++

+++**Actualización de mantenimiento del 3 de noviembre de 2022**

**Cambie el nombre de las secciones “Programar” y “Programación” para equipos y proyectos en la plantilla de diseño**

*Plantillas de diseño*

Se ha cambiado el nombre de las pestañas “Programar” y “Programación” disponibles para agregar en una plantilla de diseño al panel izquierdo de un equipo o proyecto a “Distribuidor de cargas de trabajo”.

**Errores al acceder a la configuración de las notificaciones por correo electrónico**

*Notificaciones*

>[!NOTE]
>
>Este problema existe tanto en los entornos de producción como de vista previa.

Cuando un usuario intenta cambiar la configuración de las notificaciones por correo electrónico, puede que vea alguno de los errores siguientes:

* “[!UICONTROL Intentémoslo de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]”

* “[!UICONTROL No se pudo recuperar la notificación por correo electrónico]”

Se ha informado de este problema en las siguientes áreas:

* [!UICONTROL Configuración] > [!UICONTROL Notificaciones por correo electrónico]
* [!UICONTROL Usuario] > [!UICONTROL Editar usuario]
* [!UICONTROL Grupos]

**Nuevos iconos de información para hojas de horas, perfiles de hojas de horas y preferencias de hojas de horas**

*Workfront*

>[!NOTE]
>
>Esta actualización solo se ha publicado en el entorno de vista previa. Se lanzará a Producción con la versión 23.1.

Hemos añadido varios iconos de información a la siguiente configuración:

* Casilla de verificación &quot;Puede editar el tiempo&quot; al crear o editar un perfil de parte de horas o de parte de horas para indicar que, cuando está activado, los aprobadores también pueden enviar, volver a abrir o editar el parte de horas, a menos que el administrador restrinja estas acciones en el área Preferencias de parte de horas de Configuración.
* &quot;Restringir la edición de parte de horas a propietarios y administradores&quot; en el área Preferencias de parte de horas y hora del programa de instalación para indicar que, cuando está desactivado, los siguientes usuarios también pueden editar las partes de horas: usuarios con acceso administrativo a hojas de horas y horas, aprobadores de hojas de horas permitidos para editar la hora y administradores de propietarios de hojas de horas.

Tenga en cuenta que la funcionalidad de estos ajustes no ha cambiado y que solo se han añadido los iconos de información para aclarar el ámbito de los ajustes.

+++

## Actualizaciones en octubre de 2022

+++**Actualización de mantenimiento del 27 de octubre de 2022**

La función **[!UICONTROL HOUR] de los campos calculados utiliza UTC**

*Formularios personalizados*

Cuando un campo calculado incluye la función [!UICONTROL HOUR], la función devuelve valores basados en UTC en lugar de la zona horaria esperada. Por lo tanto, cualquier cálculo basado en la función HOUR es incorrecto.

El **[!UICONTROL Filtro rápido] no devuelve resultados al buscar equipos**

*Listas*

Cuando un usuario intenta utilizar el [!UICONTROL Filtro rápido] en una lista para buscar un equipo, al introducir el nombre del equipo no se obtienen resultados, aunque el equipo esté visible en la lista (como en el campo [!UICONTROL Asignado a]). Al buscar la palabra “[!UICONTROL equipo]”, tampoco se obtienen resultados.

**No se puede volver a anclar una página tras haber eliminado su fijador**

*Exploración*

>[!NOTE]
>
>Este problema se solucionó en la versión de vista previa del 13 de octubre de 2022. Se solucionó en el entorno de producción el 27 de octubre de 2022.

Cuando un usuario selecciona la opción “[!UICONTROL Eliminar fijador]” en un fijador, recibe un mensaje sobre la eliminación e intenta reemplazar el fijador haciendo clic en “[!UICONTROL Deshacer]” en el mensaje, el fijador no se reemplaza en la barra de navegación superior, ni se añade a la lista de fijadores de la sección [!UICONTROL Más fijadores] (el menú de tres puntos del área [!UICONTROL Fijadores]).

Si un usuario intenta volver a anclar la página accediendo a ella y anclándola, no se creará el fijador y el usuario no podrá anclar la página.

**Todos los usuarios enumerados en el [!UICONTROL Distribuidor de cargas de trabajo] al utilizar un vínculo compartible en el [!DNL Safari] explorador**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario sigue un vínculo compartible que le lleva al [!UICONTROL Distribuidor de cargas de trabajo] mientras utiliza un [!DNL Safari] explorador, ve a todos los usuarios, no solo a los miembros del equipo que aparecen en la lista.

+++

+++**Actualización de mantenimiento del 20 de octubre de 2022**

**Error al asignar un equipo por lotes**

*Asignaciones*

Cuando un usuario edita por lotes tareas o problemas y asigna un equipo después de asignar un individuo, las asignaciones no se guardan y el usuario recibe el siguiente error:

“[!UICONTROL Intentémoslo de nuevo - Se produjo el siguiente error: teamAssignments debe ser una lista de objetos o una lista de ID]”

**Error de tipo “[!UICONTROL No se pudo cargar el archivo]”**

*Documentos*

Cuando un usuario intenta cargar un archivo en el área [!UICONTROL Documentos], el archivo no se carga y el usuario recibe el error “[!UICONTROL No se pudo cargar el archivo]”.

Esto se ha notificado al intentar cargar archivos MP4.

**El recuento de problemas en la navegación izquierda de la tarea es incorrecto**

*Problemas*

Cuando un usuario está viendo una tarea, el número que se muestra en la sección [!UICONTROL Problemas] de la navegación izquierda no representa con precisión el número real de problemas asociados a la tarea.


El icono **[!UICONTROL Predecesor] no se encuentra en el encabezado de la tarea**

*Tareas*

Cuando un usuario está viendo una tarea, el icono del predecesor de la tarea no aparece en el encabezado.

+++

+++**Actualización de mantenimiento del 13 de octubre de 2022**

**No se puede volver a anclar una página tras haber eliminado su fijador**

*Exploración*

>[!NOTE]
>
>Este problema se solucionará en la versión de vista previa del 13 de octubre de 2022. Se solucionará en el entorno de producción el 27 de octubre de 2022.

Cuando un usuario selecciona la opción “[!UICONTROL Eliminar fijador]” en un fijador, recibe un mensaje sobre la eliminación e intenta reemplazar el fijador haciendo clic en “[!UICONTROL Deshacer]” en el mensaje, el fijador no se reemplaza en la barra de navegación superior, ni se añade a la lista de fijadores de la sección [!UICONTROL Más fijadores] (el menú de tres puntos del área [!UICONTROL Fijadores]).

Si un usuario intenta volver a anclar la página accediendo a ella y anclándola, no se creará el fijador y el usuario no podrá anclar la página.

**No se pueden asignar nombres ni guardar los filtros recién creados**

*[!UICONTROL Planificador de recursos]*

Cuando un usuario intenta dar un nombre a un nuevo filtro en la [!UICONTROL Planificador de recursos], el cuadro del nombre permanece en blanco. Además, si el usuario ha presionado la barra espaciadora, el botón [!UICONTROL Guardar] se desactiva.

**No se puede editar el nombre o el porcentaje completado de una tarea o un problema**

*Tareas y problemas*

Los usuarios con acceso de tipo [!UICONTROL Contribuir] a una tarea o un problema no pueden editar el nombre de la tarea o el problema en el encabezado. Además, los usuarios con acceso de tipo [!UICONTROL Contribuir] no pueden editar el porcentaje completado de una tarea o problema.

**Los solicitantes y revisores se contabilizan en el recuento de licencias de una organización**

*[!DNL Workfront Proof]*

Cuando un usuario se agrega a una prueba como revisor o solicitante, obtiene un perfil de permisos como “[!UICONTROL Visitante]” que no debería utilizar una licencia de [!DNL Workfront Proof]. Sin embargo, cuando se añade el usuario, se incrementa el recuento de licencias de [!DNL Workfront Proof] utilizadas.

+++

+++**Actualización de mantenimiento el 11 de octubre de 2022**

**No se puede volver a anclar una página tras haber eliminado su fijador**

*Exploración*

>[!NOTE]
>
>Este problema se solucionó en la versión de vista previa del 13 de octubre de 2022. Se solucionará en el entorno de producción el 27 de octubre de 2022.

Cuando un usuario selecciona la opción “[!UICONTROL Eliminar fijador]” en un fijador, recibe un mensaje sobre la eliminación e intenta reemplazar el fijador haciendo clic en “[!UICONTROL Deshacer]” en el mensaje, el fijador no se reemplaza en la barra de navegación superior, ni se añade a la lista de fijadores de la sección [!UICONTROL Más fijadores] (el menú de tres puntos del área [!UICONTROL Fijadores]).

Si un usuario intenta volver a anclar la página accediendo a ella y anclándola, no se creará el fijador y el usuario no podrá anclar la página.

+++

+++**Actualización de mantenimiento del 6 de octubre de 2022**

**Nuevo tipo de modelo**

*Modelos*

El tipo de modelo “Tablero” se ha agregado al catálogo de modelos. Anteriormente, solo estaban disponibles los modelos Plantilla de proyecto y Estructura organizativa.

**Elementos superpuestos en el panel izquierdo**

*Formularios personalizados*

Cuando un usuario trabaja en el generador de formularios y el formulario tiene más de 100 campos, el mensaje que notifica al usuario sobre el límite de campos hace que los elementos del panel izquierdo se superpongan.

**El selector de fechas ya no se abre automáticamente al focalizar la entrada o hacer clic en ella**

*Exploración*

Cuando un usuario navega mediante el teclado, los selectores de fechas ya no se abren automáticamente cuando el teclado se focaliza en la entrada de fecha. Alternativamente, los usuarios del teclado deben pulsar el tabulador hasta llegar el icono del selector de fechas y pulsar Intro para abrir el selector de fechas. Cuando un usuario navega mediante el ratón, los selectores de fechas ya no se abren automáticamente hasta que se hace clic en la entrada de fecha. Alternativamente, los usuarios del ratón deben hacer clic en el icono del selector de fechas para abrir el selector de fechas.

Este cambio se realizó para ajustarse mejor a los patrones de experiencia de usuario del selector de fechas estándar y para crear una experiencia más accesible para los usuarios del teclado y del lector de pantalla.

**Asignar varios resultados de equipos solo genera un equipo asignado**

*Equipos*

>[!NOTE]
>
>Esta actualización solo existe en el entorno de vista previa.

Cuando un usuario asigna varios equipos a una tarea o problema, solo aparece un equipo en la lista de asignaciones. Este problema también afecta a la creación de informes. Los informes que muestran asignaciones de equipo son inexactos porque solo aparece un equipo como asignado a la tarea o al problema.

Error de tipo **“[!UICONTROL Los cambios recientes no se han guardado]” al guardar automáticamente los cambios en una plantilla de horas**

*Plantillas de horas*

Cuando un usuario intenta editar una plantilla de horas de forma que se active un guardado automático, los cambios no se guardan y el usuario ve el siguiente mensaje:

“[!UICONTROL No se han guardado sus cambios recientes. Actualice la página para verlos.]”

Se ha informado de esto al editar lo siguiente:

* Horas
* Tareas

**Las notificaciones por correo electrónico se retrasan**

*Revisión de Workfront*

Cuando se produce un evento en [!DNL Workfront Proof] que desencadena una notificación por correo electrónico, el usuario no recibe la notificación inmediatamente. La notificación puede retrasarse varias horas.

+++

+++**Actualización de mantenimiento del 3 de octubre de 2022**

**Guarde manualmente su plantilla de horas cuando las funciones de trabajo anteriores hayan cambiado**

*Plantillas de horas*

Si la función de trabajo para la que ha registrado tiempo ha cambiado y la opción [!UICONTROL Asignar roles de trabajo a las entradas de hora manualmente] se ha desactivado, debe guardar manualmente las entradas de tiempo hasta que no se registren las horas para la función de trabajo que ha cambiado.

+++

## Actualizaciones en septiembre de 2022

+++**Actualización de mantenimiento del 29 de septiembre de 2022**

**El usuario no vuelve a la página anterior al cerrar la prueba**

*Pruebas*

Cuando un usuario que está viendo una prueba en [!DNL Workfront] cierra la prueba, no se devuelve la página en la que se encontraba antes de abrirla. Alternativamente, se le redirige a otra página de [!DNL Workfront].

**No se puede abrir la prueba en[!DNL Workfront]**

*Pruebas*

Cuando un usuario está viendo un documento en [!DNL Workfront] e intenta abrir la prueba, la prueba no se abre y el usuario vuelve a la página [!UICONTROL Detalles del documento].

**Las horas no se guardan al utilizar el [!UICONTROL tabulador]**

*Plantillas de horas*

Cuando un usuario está rellenando una plantilla de horas y navega entre celdas con el [!UICONTROL tabulador], las horas no se guardan. La notificación de [!UICONTROL guardado automático] no aparece en la parte inferior de la pantalla, y si el usuario actualiza la página, puede ver que las horas no se han guardado.

**Páginas en blanco al ver una prueba con varias páginas**

*[!DNL Workfront Proof]*

Cuando un usuario ve una prueba con varias páginas, puede ver miniaturas de las páginas, pero estas no se abren en el visor principal.



+++

+++**Actualización de mantenimiento del 22 de septiembre de 2022**

**No se puede cerrar la tarjeta de usuario en el flujo de actualización del estado**

*Actualizaciones*

Cuando un usuario está viendo las actualizaciones y pasa el ratón por encima de un nombre, se abre una tarjeta con detalles sobre el usuario del que se trata y no se cierra automáticamente. La página no responde hasta que se cierra manualmente la tarjeta haciendo clic en la X de la esquina superior derecha.

+++

+++**Actualización de mantenimiento del 15 de septiembre de 2022**

**Aparece el error “[!UICONTROL Alguien más intentó guardar este proyecto]” al introducir horas**

*Plantillas de horas*

Cuando un usuario intenta registrar horas en una tarea de su plantilla de horas, las horas no se guardan automáticamente y ve el siguiente error:

“[!UICONTROL Lo lamentamos, no se pudo guardar debido a que otro usuario intentó guardar el proyecto al mismo tiempo. Intente guardar de nuevo.]”

**No se puede cerrar la tarjeta de usuario en el flujo de actualización del estado**

*Actualizaciones*

Cuando un usuario está viendo las actualizaciones y pasa el ratón por encima de un nombre, se abre una tarjeta con detalles sobre el usuario del que se trata y no se cierra automáticamente. La página no responde hasta que se cierra manualmente la tarjeta haciendo clic en la X de la esquina superior derecha.

**El nombre del campo “[!UICONTROL Asignación de funciones de tarea]” se ha cambiado a “[!UICONTROL Asignación de funciones]” al asignar trabajo por lotes mediante el [!UICONTROL Distribuidor de cargas de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Para reflejar la nueva funcionalidad de poder asignar tareas y problemas por lotes desde el área de [!UICONTROL Trabajo no asignado], se ha cambiado el nombre del campo “[!UICONTROL Asignación de funciones de tarea]” a “[!UICONTROL Asignación de funciones]” en el [!UICONTROL Distribuidor de cargas de trabajo]. El campo hace referencia a las funciones que se han asignado a tareas o problemas y se muestra al asignar usuarios a elementos en la ventana [!UICONTROL Asignaciones por lotes].

+++

+++**[!DNL Workfront Scenario Planner]Actualización de mantenimiento el 15 de septiembre de 2022**

**El filtro compartido con un Grupo ahora se muestra en la lista de [!UICONTROL Importar proyectos] de [!DNL Scenario Planner] para los miembros de todos los subgrupos**

*[!DNL Workfront Scenario Planner]*

Ahora, cuando comparte un filtro de proyecto con un grupo que tiene subgrupos adicionales, el filtro es visible para todos los miembros de grupo y del subgrupo que ven proyectos en la ventana [!UICONTROL Importar proyectos] de un plan en el [!DNL Scenario Planner].

+++

+++**Actualización de mantenimiento del 8 de septiembre de 2022**

**Nombres actualizados revertidos para los campos de asignación de usuarios y funciones**

*Asignaciones*

Los campos de asignación cuyos nombres se cambiaron temporalmente la semana pasada se han devuelto a sus denominaciones originales:

* [!UICONTROL Usuarios de asignación]
* [!UICONTROL Roles de asignación]

**Error al eliminar el Propietario del proyecto del encabezado**

*Proyectos*

Cuando un usuario intenta eliminar un [!UICONTROL Propietario del proyecto] del encabezado de un proyecto, el [!UICONTROL Propietario del proyecto] no se elimina y el usuario ve el siguiente mensaje de error:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**La ventana [!UICONTROL Descripción] cuyo tamaño se modificó vuelve a su tamaño original**

*Proyectos, tareas y problemas*

Cuando un usuario cambia el tamaño de la ventana [!UICONTROL Descripción] en el área de detalles de un elemento de trabajo para agrandarla y a continuación empieza a escribir en la ventana, esta vuelve a su tamaño original. El usuario puede seguir escribiendo en la ventana y el contenido se guardará según lo esperado

**Salida involuntaria al crear tareas o problemas**

*Tareas y problemas*

Cuando un usuario crea una tarea o un problema en un proyecto y hace clic fuera de la ventana emergente de creación, la ventana emergente se cierra sin previo aviso y se pierde toda la información introducida anteriormente.

**Se ha eliminado la capacidad de enviar una prueba por correo electrónico a una Dropzone**

*[!DNL Workfront Proof]*

El jueves 8 de septiembre de 2022 eliminamos la capacidad de enviar una prueba por correo electrónico a una Dropzone en el producto [!DNL Workfront Proof] independiente.

Puede seguir utilizando las Dropzones de otros modos para enviar nuevas pruebas y nuevas versiones de pruebas a su cuenta sin tener que iniciar sesión en su cuenta. Consulte [La Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html?lang=es) para obtener más información.

+++

+++**Actualización de mantenimiento del 6 de septiembre de 2022**

**Fechas de proyecto agregadas a la lista de campos para encabezados de proyecto personalizables**

*Proyectos*

Hemos añadido los campos [!UICONTROL Fecha inicial prevista] y [!UICONTROL Fecha de finalización prevista] a la lista de campos para encabezados de proyecto personalizables al utilizar una plantilla de diseño.

**Nuevo límite con un mensaje de confirmación que muestra el número de elementos agregados a una plantilla de horas**

*Plantillas de horas*

Cuando selecciona más de 50 elementos para agregarlos a una plantilla de horas, ahora recibe un mensaje de confirmación que muestra el número de elementos que se agregarán a la plantilla de horas y le permite cambiar de idea y no agregar todos los elementos. Todos los elementos añadidos se anclan automáticamente en la plantilla de horas y deberán eliminarse manualmente de las plantillas de horas actuales y futuras.

+++

+++**Actualización de mantenimiento del 2 de septiembre de 2022**

Agregue el campo [!UICONTROL Integraciones] al encabezado del proyecto personalizado

*Integraciones*

Ahora puede agregar el campo [!UICONTROL Integraciones] al encabezado personalizado de un proyecto cuando se utiliza una plantilla de diseño. Una vez añadido, el campo muestra un vínculo a un elemento externo vinculado al proyecto que se encuentra en [!DNL Salesforce] o [!DNL Anaplan], dependiendo de su integración.

>[!NOTE]
>
>Esta actualización de mantenimiento se publicó anteriormente en el entorno de vista previa el 25 de agosto de 2022 y ahora se encuentra en producción.

+++

+++**Actualización de mantenimiento del 1 de septiembre de 2022**

**Elementos completados eliminados de las delegaciones**

*Delegaciones*

Ahora solo los elementos incompletos cuyas fechas coincidan con las fechas de una delegación se delegarán a otros usuarios cuando se inicie la delegación de elementos de trabajo. Si los elementos se completaron antes de que comenzara la delegación, no se delegarán. Los elementos que se completen durante el período de tiempo de delegación permanecerán en la Lista de trabajos del área de Inicio durante dos semanas, tanto para el delegado como para el asignatario antes de que se eliminen automáticamente si la delegación no ha finalizado durante esas semanas.

**Actualizaciones de metadatos para [!DNL Adobe Workfront] para [!DNL Experience Manager Assets] e integraciones de [!DNL Assets Essentials]**

*Integraciones*

Los metadatos se insertan automáticamente al agregar un recurso a una carpeta vinculada.

Antes los metadatos solo se insertaban cuando se agregaba un recurso mediante la función de menú desplegable [!UICONTROL Agregar nuevo].

**No se pueden aprobar ni rechazar horas en un problema**

*Problemas*

Cuando un usuario intenta aprobar o rechazar horas en la pestaña [!UICONTROL Horas] de un problema, faltan los botones de [!UICONTROL Aprobar] y [!UICONTROL Rechazar].

**La conversión de un problema en un proyecto mediante una plantilla muestra un mensaje de error incorrecto**

*Problemas*

Cuando se convierte un problema en un proyecto mediante una plantilla y se produce un error, se muestra al usuario una página con el mensaje “[!UICONTROL El proyecto ya no existe]” en lugar del mensaje de error correcto que explica la causa de la conversión fallida.

**No se puede crear la prueba para archivos de más de 1,5 GB**

*[!DNL Workfront Proof]*

Al crear una prueba nueva, si un usuario carga un archivo de más de 1,5 GB, el nombre del archivo se pondrá rojo y no se podrá crear la prueba.

+++

## Actualizaciones en agosto de 2022

+++**Actualización de mantenimiento del 25 de agosto de 2022**

**Los vínculos del Distribuidor de cargas de trabajo se muestran incorrectamente en los paneles**

*Paneles*

Los vínculos compartibles del Distribuidor de cargas de trabajo se muestran incorrectamente cuando se añaden a un panel como una página externa. En lugar de utilizar la vista o los filtros únicos asociados al vínculo, el panel utiliza la vista o los filtros aplicados más recientemente al Distribuidor de cargas de trabajo.

**Agregue el campo [!UICONTROL Integraciones] al encabezado del proyecto personalizado**

*Proyectos*

Ahora puede agregar el campo [!UICONTROL Integraciones] al encabezado personalizado de un proyecto cuando se utiliza una plantilla de diseño. Una vez añadido, el campo muestra un vínculo a un elemento externo vinculado al proyecto que se encuentra en [!DNL Salesforce] o [!DNL Anaplan], dependiendo de su integración.

>[!NOTE]
>
>Actualmente esta actualización de mantenimiento solo se encuentra en el entorno de vista previa. Se lanzará al entorno de producción una semana después del lanzamiento de la vista previa.

**Los datos personalizados no se conservan al convertir un problema en un proyecto en blanco**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto en blanco (sin plantilla), los datos de los campos calculados no se transfieren al nuevo proyecto.

**Error de “Modo de planificación de la cronología” al cambiar una fecha de un proyecto**

*Proyectos*

Cuando un usuario intenta cambiar una fecha en un proyecto que tiene el [!UICONTROL modo de planificación] establecido en [!UICONTROL Guardar de forma manual] > [!UICONTROL Planificación de cronología], la fecha no cambia y el usuario ve un error.

“[!UICONTROL El modo de planificación de la cronología solo está disponible cuando timelineDate está cargado. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]”

**Coherencia al abrir el Distribuidor de cargas de trabajo mediante la vista Mes**

*Distribuidor de cargas de trabajo*

Ahora el Distribuidor de cargas de trabajo muestra los elementos asignados de los usuarios expandidos al mostrarlos en las vistas [!UICONTROL Día], [!UICONTROL Semana] o [!UICONTROL Mes]. Antes de esta actualización, los elementos asignados se mostraban expandidos en las vistas [!UICONTROL Día] y [!UICONTROL Semana] y contraídos en la vista [!UICONTROL Mes].


+++

+++**Actualización de mantenimiento del 18 de agosto de 2022**

**Las opciones “[!UICONTROL Agregar a iteración]” y “[!UICONTROL Agregar a panel Kanban]” no están disponibles cuando se editan en línea tareas en un informe**

*Informes*

Cuando un usuario está viendo una lista de tareas en un informe y abre el menú [!UICONTROL Más] (tres puntos), las opciones “[!UICONTROL Añadir a la iteración]” y “[!UICONTROL Añadir al panel Kanban]” no están disponibles en el desplegable. Si el informe se visualiza en un panel, las opciones “[!UICONTROL Añadir a la iteración]” y “[!UICONTROL Añadir al panel Kanban]” están disponibles en el desplegable.

**Los informes de matriz se muestran de forma incorrecta al desplazarse**

*Informes*

Cuando un usuario está viendo un informe de matriz y se desplaza por la pantalla, algunos elementos visuales del informe pueden superponerse o duplicarse.

Vista de **[!UICONTROL Hito] eliminada de la lista de proyectos de Plantillas de horas**

*Plantillas de horas*

La vista de [!UICONTROL Hito] se ha eliminado de la lista de proyectos de la plantilla de horas al agregar un proyecto.

**Los hipervínculos de una prueba interactiva no están activos**

*[!DNL Workfront Proof]*

Cuando un usuario está viendo una prueba interactiva y hace clic en un vínculo o en un botón que contiene un vínculo, no se le redirige a la página a la que está vinculado el vínculo o el botón.

**Nuevos campos de texto que faltan en la página de prueba**

*[!DNL Workfront Proof]*

En la página [!DNL New Proof] no se muestran muchos campos de texto (incluidas etiquetas de campo, opciones desplegables y nombres de las casillas de verificación).

**Los usuarios no reciben notificaciones cuando se les etiqueta en una prueba**

*[!DNL Workfront Proof]*

Un usuario que está etiquetado en un comentario de una prueba no recibe la notificación por correo electrónico sobre el comentario.

+++

+++**Actualización de mantenimiento del 12 de agosto de 2022**

**Nuevo campo de encabezado personalizable añadido al principio del encabezado**

*Encabezados*

Cuando se agrega un nuevo campo a un encabezado personalizable, el campo ahora se agrega como el primer campo a la izquierda en el encabezado o inmediatamente después de la ventana [!UICONTROL Buscar] dentro de la plantilla de diseño. Antes de este cambio, el campo se añadía como el último campo del encabezado.

+++

+++**Actualización de mantenimiento del 11 de agosto de 2022**

**No se pueden editar los formularios personalizados debido a un límite de caracteres incorrecto en los campos de texto descriptivo**

*Formularios personalizados*

Cuando un usuario intenta editar un formulario personalizado con un campo de [!UICONTROL texto descriptivo] con más de 512 caracteres, el usuario no puede guardar las ediciones en el formulario personalizado y ve el siguiente error:

“Los campos siguientes no son válidos: (Campo) es demasiado largo, máximo 512”

Esto afecta a los campos de [!UICONTROL texto descriptivo] que anteriormente funcionaban correctamente a pesar de tener más de 512 caracteres.

**Los datos de los campos ocultos por un salto de sección no se conservan al convertir un problema en un proyecto**

*Formularios personalizados*

Cuando un usuario está convirtiendo un problema en un proyecto, y el problema incluye un formulario personalizado con datos en un salto de sección que puede ocultarse mediante la lógica de visualización, los datos de esa sección no se trasladan al nuevo proyecto.

**Los datos de los campos ocultos por un salto de sección no se conservan al convertir una solicitud en un proyecto**

*Formularios personalizados*

Cuando un usuario está convirtiendo una solicitud en un proyecto, y la solicitud incluye un formulario personalizado con datos en un salto de sección que puede ocultarse mediante la lógica de visualización, los datos de esa sección no se trasladan al nuevo proyecto.

**No se pueden editar formularios personalizados debido al campo de Texto descriptivo**

*Formularios personalizados*

Cuando un usuario intenta editar un formulario personalizado que incluye un campo Texto descriptivo, la etiqueta del campo no se rellena. El usuario ve el error “[!UICONTROL Este campo es obligatorio]” bajo el campo de la etiqueta y no puede editar el formulario personalizado debido a este error.

**No se pueden quitar instrucciones de un campo personalizado en el generador de formularios personalizados**

*Formularios personalizados*

Cuando un usuario está editando un campo personalizado e intenta eliminar el texto existente en el área de [!UICONTROL Instrucciones], este no se elimina cuando se guarda el campo. El usuario puede editar el texto, pero no puede eliminarlo por completo.

**La asignación de equipo al crear una solicitud no aparece en una nueva solicitud**

*Solicitudes*

Cuando un usuario crea una solicitud, le asigna un equipo, y luego la envía, el equipo no se asigna a la solicitud creada. Esto solo afecta a la asignación de equipos. Las asignaciones de los usuarios funcionan según lo esperado.

+++

+++**Actualización de mantenimiento del 4 de agosto de 2022**

Estos problemas se solucionaron solo en la nueva experiencia de [!DNL Workfront].

Toda la funcionalidad de [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Error al cambiar la Fecha planificada de finalización en el encabezado de una tarea o problema**

*Tareas y problemas*

Cuando un usuario intenta cambiar la [!UICONTROL fecha planificada de finalización] en la cabecera de una tarea o problema, la fecha no cambia y el usuario ve un error similar al siguiente:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Actualizaciones en julio de 2022

+++**Actualización de mantenimiento del 28 de julio de 2022**

Estos problemas se solucionaron solo en la nueva experiencia de [!DNL Workfront].

Toda la funcionalidad de [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Error al abrir un elemento desde la [!UICONTROL Lista de trabajos en Inicio]**

*[!UICONTROL Página de inicio]*

Cuando un usuario intenta abrir un elemento en su [!UICONTROL Lista de trabajos en Inicio], el elemento no se abre y el usuario ve el siguiente mensaje:

“[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando actualizar esta página de explorador.]”

**Las tareas y los problemas delegados a un usuario no aparecen en la Lista de trabajos en Inicio del usuario**

*[!UICONTROL Página de inicio]*

Cuando el usuario ve sus [!UICONTROL Lista de trabajos en Inicio], las tareas o problemas delegados al usuario no aparecen en la lista y es posible que el usuario no tenga conocimiento de las delegaciones.

**Los informes programados no se envían a todos los destinatarios**

*Informes*

Cuando se envía un informe programado, no se envía a todos los usuarios en la sección “[!UICONTROL Enviar a]”. Los usuarios omitidos son aleatorios y pueden variar cada vez que se envía el informe.

**[!UICONTROL No se puede anular la selección de tareas al adjuntar una plantilla]**

*Plantillas*

Cuando un usuario adjunta y personaliza una plantilla, se le pide que anule la selección de tareas que no desee incluir. Sin embargo, ninguna de las tareas se muestra como seleccionadas y el usuario no puede anular la selección.

**Los campos “Configuración regional” ahora tienen etiquetas más específicas**

*Terminología*

Para que la función de los campos de la “[!UICONTROL Configuración regional]” sea más clara, hemos actualizado sus etiquetas.

* El campo “[!UICONTROL Configuración regional]” en el perfil de usuario ahora se denomina “[!UICONTROL Configuración regional de correo electrónico]”
* El campo “[!UICONTROL Configuración regional]” encontrado en la zona de [!UICONTROL Configuración] > [!UICONTROL Sistema] > [!UICONTROL Información del cliente] ahora está etiquetada como “[!UICONTROL Configuración regional de correo electrónico predeterminada]”

La funcionalidad de estos campos no ha cambiado.

**Problemas al crear plantillas de horas**

*Plantillas de horas*

Se han comunicado los siguientes problemas con respecto a la creación de plantillas de horas:

* Cuando un usuario intenta crear una plantilla de horas para una función, la plantilla no se crea y el usuario ve el error “[!UICONTROL No se encuentra el usuario con valores de clave principal ‘XXXXXXXXXXX’]”.
* Cuando un usuario intenta crear una plantilla de horas para un equipo, el campo de [!UICONTROL escritura anticipada] no se rellena con los equipos y el botón [!UICONTROL Crear plantilla de horas] está desactivado.


**Las zonas de [!DNL Workfront Proof] no se actualizan cuando se crea, mueve o archiva una prueba**

*[!DNL Workfront]Proof*

Proof está experimentando retrasos en la indexación. Esto puede afectar a la experiencia del usuario de las siguientes maneras:

* Los paneles no muestran el número correcto de pruebas
* Las carpetas no se actualizan cuando se crea o mueve una prueba
* Las pruebas archivadas permanecen en listas de pruebas activas.

+++

+++**Actualización de mantenimiento (Hot Fix) el 26 de julio de 2022**

Estos problemas se solucionaron solo en la nueva experiencia de [!DNL Workfront].

Toda la funcionalidad de [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Las horas mostradas en la plantilla de horas son diferentes a las de la lista de Plantillas de horas**

*Plantillas de horas*

Cuando un usuario abre una plantilla de horas para verla, las horas mostradas son diferentes a las que el usuario ve para esa misma plantilla en una lista de plantilla de horas.


**La solicitud convertida a un proyecto con plantilla muestra el grupo de la cola de solicitudes, no el grupo de la plantilla**

*Solicitudes*

Cuando un usuario convierte una solicitud en un proyecto mediante una plantilla, el proyecto recién creado se asocia al grupo propietario de la cola de solicitudes, no al grupo asignado en la plantilla. Esto ocurre a pesar de que cuando se está creando el proyecto, el grupo asociado a la plantilla se rellene en el campo [!UICONTROL Grupo].

+++

+++**Actualización de mantenimiento del 21 de julio de 2022**

Estos problemas se solucionaron solo en la nueva experiencia de [!DNL Workfront].

Toda la funcionalidad de [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**El estado de rechazo asociado con una aprobación respeta el flujo de trabajo de aprobación**

**NOTA: Esta funcionalidad se publicó el 22 de julio de 2022.**

*Rutas de aprobación*

Si selecciona un estado asociado a un proceso de aprobación como estado de rechazo de una ruta de aprobación, el objeto rechazado pasa al estado seleccionado y se marcará como “[!UICONTROL Pendiente de aprobación]”. Por ejemplo, si selecciona [!UICONTROL En espera] para el estado de rechazo y el estado de [!UICONTROL En espera] está asociado a un proceso de aprobación, el objeto rechazado se coloca en el estado de “[!UICONTROL En espera: pendiente de aprobación]”, que requiere la aprobación.

Antes de esta actualización, el objeto omitió el proceso de aprobación para el estado de rechazo y se colocó en el estado de [!UICONTROL En espera].

**Configuración de una dirección URL de ayuda personalizada**

*[!UICONTROL Menú principal]*

Si su organización tiene un sitio de ayuda interno personalizado, puede configurar el icono de [!UICONTROL Menú principal] [!UICONTROL Ayuda] para ir a ese sitio. Esto resulta útil si el sitio de ayuda contiene información sobre cómo su organización utiliza [!DNL Workfront].
Esta dirección URL personalizada no afecta al vínculo de Ayuda principal del área superior de [!DNL Workfront], ni tampoco a los vínculos de ayuda contextual por todo [!DNL Workfront] que llevan a los usuarios al [!DNL Workfront] sitio de Ayuda.

**No se puede seleccionar el tiempo transcurrido al editar en línea la [!UICONTROL Duración de la tarea]**

*Tareas*

Cuando un usuario está viendo una lista de tareas e intenta editar la [!UICONTROL Duración de la tarea], no están disponibles las siguientes unidades de tiempo:

* [!UICONTROL Minutos transcurridos]
* [!UICONTROL Horas transcurridas]
* [!UICONTROL Días transcurridos]
* [!UICONTROL Semanas transcurridas]
* [!UICONTROL Meses transcurridos]

La página de **[!UICONTROL Mis actualizaciones] está en blanco**

*Actualizaciones*

Cuando un usuario intenta ver su página de [!UICONTROL Mis actualizaciones], la página no se carga. El usuario solo puede ver el encabezado de navegación de [!DNL Workfront].

**Falta la configuración de “[!UICONTROL Permitir solo la autenticación SAML 2.0]” al copiar un usuario**

*Usuarios*

Cuando un administrador de grupo copia un usuario y anula la selección de la opción de “[!UICONTROL Enviar un correo electrónico de invitación a esta persona]”, la casilla de “[!UICONTROL Permitir solo la autenticación SAML 2.0]” no aparece como según lo esperado. Esto puede ocurrir incluso aunque se cumplan todos los requisitos de acceso y permiso para esta acción.

+++

+++**Actualización de mantenimiento del 14 de julio de 2022**

Estos problemas se solucionaron solo en la nueva experiencia de [!DNL Workfront].

Toda la funcionalidad de [!DNL Workfront Classic] se eliminó el 14 de julio de 2022.

**Error al restablecer la contraseña**

*Inicio de sesión*

Cuando un usuario intenta restablecer su contraseña, no puede hacerlo y ve un mensaje que le dice que no tiene acceso. El usuario no puede iniciar sesión en Workfront.

**No se puede solicitar más acceso a un informe**

*Informes*

Cuando un usuario con acceso limitado a un informe intenta solicitar más acceso a un informe, la opción no está disponible en menú de [!UICONTROL acciones del informe].

**Se ha actualizado el mensaje de confirmación al eliminar un borrador de solicitud**

*Solicitudes*

Cuando se descarta un borrador de solicitud, en el mensaje de confirmación que aparece después de hacer clic en “[!UICONTROL Descartar borrador]” se muestra lo siguiente:

* [!UICONTROL Borrador descartado] (se trata de una notificación para informarle de que su borrador se descartó)
* [!UICONTROL Deshacer] (se trata de un vínculo en el que puede hacer clic para revertir la acción de eliminar el borrador. Esto conservará el borrador en lugar de eliminarlo).

Antes de este cambio, las opciones eran:

* [!UICONTROL El borrador se descartará]
* [!UICONTROL Cancelar]

**Los valores de fecha de los campos Entrada de cuaderno son incorrectos cuando se accede a ellos a través de la API**

*Actualizaciones*

Cuando un usuario cambia un valor de fecha en un objeto y, a continuación, se accede a la Entrada de cuaderno que representa ese cambio de fecha a través de la API, los valores de fecha para [!UICONTROL oldDateVal] y [!UICONTROL newDateVal] que devuelve la API son incorrectos.

**Error al intentar deshacer el comentario**

*Actualizaciones*

Cuando un usuario intenta deshacer un comentario, el comentario no se deshace y el usuario ve el siguiente error:

[!UICONTROL Error 403: No tiene acceso suficiente para eliminar esta Nota /attask/api-internal/NOTE]

**Nueva limitación al número de caracteres de una actualización en vista previa**

*Actualizaciones*

Para mejorar el rendimiento del área de [!UICONTROL Actualizaciones], se ha introducido un nuevo límite en el número de caracteres que se pueden introducir en una actualización o en una respuesta a una actualización existente. El nuevo límite es de 15 000 caracteres. Esta actualización no cambió el número de caracteres permitidos al utilizar la API. El límite de caracteres de la API para las actualizaciones es de 4000.

**Error al cargar adjuntos desde [!DNL Workfront] para la integración con Outlook**

*Integraciones de Workfront*

Cuando un usuario intenta cargar un archivo adjunto mediante la integración de [!DNL Workfront for Outlook], el adjunto no se carga y el usuario ve el siguiente mensaje:

[!UICONTROL Algunos archivos adjuntos no se han cargado. Motivo: Se ha producido un error al cargar archivos adjuntos.]

**Actualización de la notificación de prueba por correo electrónico**

*[!DNL Workfront]Proof*

A principios de este mes, como parte de un parche para el entorno de producción de [!DNL Workfront], hemos corregido un error en el sistema de notificación de prueba por correo electrónico. Este cambio no se comunicó en la actualización de mantenimiento cuando se publicó. Hemos añadido la siguiente información a la [Actualización de mantenimiento del 2 de junio de 2022](#maintenance-update-on-june-2-2022):

Como resultado de estas correcciones de errores, la dirección de correo electrónico que se utiliza para enviar notificaciones de prueba ha cambiado.

Anteriormente, las direcciones de correo electrónico de prueba contenían el subdominio de la organización. Por ejemplo, notifications@[dominio organizativo].my.workfront.com

Ahora, la identificación de direcciones de correo electrónico ya no contiene un subdominio de organización. Todas las notificaciones de prueba por correo electrónico provienen de la siguiente dirección: notification@my.workfront.com

Como resultado, le recomendamos que realice las siguientes acciones si aún no lo ha hecho:

* Actualice los filtros de correo no deseado para aceptar correos electrónicos de notification@my.workfront.com
* Actualice sus listas de permitidos para aceptar correos electrónicos de notification@my.workfront.com

**Las opciones de usuario no se pueden modificar después de la configuración inicial en las Plantillas de flujo de trabajo**

*[!DNL Workfront Proof]*

Cuando un usuario agrega un usuario a una Plantilla de flujo de trabajo, puede configurar opciones. Sin embargo, una vez completada la configuración inicial, el usuario ya no puede modificar lo siguiente:

* Capacidad de “[!UICONTROL Resolver comentarios y aplicar acciones]”
* Capacidad de [!UICONTROL “Compartir la prueba mediante etiquetado]”
* Función de prueba ([!UICONTROL Revisor], [!UICONTROL Aprobador], etc.)

**El filtro de “[!UICONTROL Elementos de trabajo de este proyecto]” se ha restaurado en el proyecto [!UICONTROL Distribuidor de cargas de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Hemos restaurado el filtro de “Elementos de trabajo de este proyecto” en el área [!UICONTROL Asignada] al acceder al [!UICONTROL Distribuidor de cargas de trabajo] de un proyecto.

Este filtro ahora aparece en la sección “[!UICONTROL Sugeridos]” de los filtros para el área de [!UICONTROL Trabajo asignado] del [!UICONTROL Distribuidor de cargas de trabajo] de un proyecto.

+++

## Actualizaciones en junio de 2022

+++**Actualización de mantenimiento del 30 de junio de 2022**

**Visualice el [!UICONTROL Distribuidor de cargas de trabajo] para una semana**

*[!UICONTROL Distribuidor de cargas de trabajo]*

A raíz de los comentarios que hemos recibido de muchos clientes, ahora hemos añadido una opción para visualizar el [!UICONTROL Distribuidor de cargas de trabajo] para una semana. Antes de esta actualización, se podía visualizar el [!UICONTROL Distribuidor de cargas de trabajo] para 4, 6 y 12 semanas. Con esta actualización, también hemos cambiado la opción de 12 semanas a 3 meses.

**El panel de Delegar ya está disponible en el Distribuidor de cargas de trabajo**

*[!UICONTROL Distribuidor de cargas de trabajo]*

NOTA: Esta actualización solo existe en el entorno de vista previa. La funcionalidad asociada con esta actualización estará disponible en el entorno de producción con la versión 22.3.

Ahora puede ver los delegados de una tarea o problema desde el Distribuidor de cargas de trabajo. Al asignar una tarea o un problema desde el Distribuidor de cargas de trabajo, puede ver una lista de asignaciones, así como una lista de delegados para la tarea o el problema, si están delegados actualmente.

**No se puede abrir la información de extremo en el Explorador de API**

*API*

Cuando un usuario está viendo [!DNL API Explorer] y hace clic en un extremo, la información del extremo no se muestra.

**Problemas con el botón [!UICONTROL Detalles] al usar el [!UICONTROL Calendario de Inicio]**

*Página de inicio*

Cuando un usuario utiliza el [!UICONTROL Calendario de Inicio] y hace clic en una tarea, puede producirse una de las siguientes situaciones:

* El botón [!UICONTROL Detalles] aparece brevemente y desaparece. El usuario no puede acceder a los detalles.
* El botón [!UICONTROL Detalles] no aparece. El usuario no puede acceder a los detalles.
* El botón [!UICONTROL Detalles] aparece, pero no está en la ubicación correcta. El usuario puede hacer clic en el botón para acceder a los detalles.

+++

+++**Actualización de mantenimiento (Hot Fix) el 24 de junio de 2022**

**El selector de fechas no se cierra al editar Formulario personalizado**

*Formularios personalizados*

Cuando un usuario está editando un formulario personalizado e intenta cambiar una fecha, el selector de fechas no se cierra cuando se selecciona la fecha. El usuario no puede cerrar el selector de fechas guardando, cancelando o haciendo clic fuera del selector de fechas.

Se ha informado de este problema en las siguientes áreas:

* Área de [!UICONTROL Actualizaciones]
* [!UICONTROL Página de inicio]

**El usuario no puede pasar a otra fase de una prueba**

*Pruebas*

Cuando un usuario está viendo el [!UICONTROL Flujo de trabajo de prueba] de una prueba e intenta arrastrarse a un paso diferente de la prueba, el nombre del usuario se queda en el escenario original y no se añade al escenario deseado.

+++

+++**Actualización de mantenimiento del 23 de junio de 2022**

**[!UICONTROL No se puede agregar una nueva solicitud a través del panel]**

*Paneles*

Cuando un usuario está viendo un panel en un proyecto e intenta agregar una nueva solicitud haciendo clic en el botón [!UICONTROL +Nueva solicitud], el botón no responde y el usuario no puede agregar una solicitud nueva.

**Error al ver elementos en la Lista de trabajos de Inicio**

*[!UICONTROL Página de inicio]*

Cuando un usuario está viendo su [!UICONTROL Lista de trabajos en Inicio] y hace clic en un elemento de la sección [!UICONTROL Aprobaciones enviadas], la página muestra el siguiente error:

“[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]”

Si el usuario actualiza la página y luego hace clic en cualquier elemento de la sección [!UICONTROL Lista de trabajos], aparece el error. El problema ya no afecta solo a los elementos de la sección [!UICONTROL Aprobaciones enviadas].

**La sección personalizada sobre un objeto incluye resultados que no están en ese objeto**

*Objetos*

Cuando un usuario está viendo una sección [!UICONTROL personalizada] sobre un objeto, la sección personalizada muestra elementos que no forman parte de ese objeto. Esto se ha informado cuando la sección personalizada se agrega directamente al objeto y cuando se agrega una sección personalizada a través de una plantilla de diseño.

**Las tareas se mueven a un proyecto incorrecto**

*Tareas*

Cuando un usuario mueve tareas del proyecto A al proyecto B y, a continuación, mueve más tareas del proyecto A al proyecto C, las tareas que se movieron originalmente al proyecto B aparecen en el proyecto C.

**Algunos botones o iconos no funcionan al acceder al [!UICONTROL Distribuidor de cargas de trabajo] desde un vínculo o panel compartido**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario va al [!UICONTROL Distribuidor de cargas de trabajo] a través de un vínculo compartido o un vínculo en un panel e intenta utilizar el elemento en la parte superior de la pantalla, los elementos no funcionan. Se ha informado de este problema en los siguientes elementos:

* [!UICONTROL Hoy]
* Flechas atrás y adelante
* [!UICONTROL Semanas]
* Icono de calendario (selector de fechas)

+++

+++Actualización de mantenimiento de **[!DNL Workfront]Scenario Planner del 23 de junio de 2022**

**Los usuarios con permisos de [!UICONTROL Administración] de un plan pueden compartirlos con otros**

Como usuario con permisos de [!UICONTROL Administración] de un plan de [!DNL Scenario Planner], ahora puede compartirlos con otros usuarios. Antes de esta actualización, solo el creador del plan podía compartir el plan con otros usuarios.

+++

+++**Actualización de mantenimiento del 16 de junio de 2022**

**El administrador del grupo no puede agregar miembros al grupo**

*Grupos*

Cuando un administrador de grupo intenta agregar un usuario a un grupo, la lista desplegable para seleccionar el usuario no se completa. El administrador del grupo no puede seleccionar ningún usuario y, por lo tanto, no puede agregar ningún usuario al grupo.

**Los trimestres personalizados no aparecen al configurar un filtro**

*Filtros*

Cuando un usuario crea un filtro y filtra por un campo de fecha, la lista desplegable de operadores disponibles para el campo de fecha no incluye ningún trimestre personalizado agregado recientemente.

**Error “¡Uy!” al convertir un problema en un proyecto mediante una plantilla**

*Proyectos*

Cuando un usuario intenta convertir un problema en un proyecto a través de una plantilla y el problema tiene un formulario personalizado que contiene una sección de solo administración, el problema no se convierte y el usuario ve el siguiente error:

“[!UICONTROL Intentémoslo de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]”

**Las solicitudes se envían sin haber rellenado los campos obligatorios**

*Solicitudes*

Cuando un usuario crea una solicitud y no rellena los campos obligatorios y luego envía la solicitud, esta se envía sin datos en los campos obligatorios. El comportamiento esperado es que la solicitud no se envíe y que se notifique al usuario que debe rellenar los campos obligatorios antes de enviar la solicitud.

**Los nuevos trimestres personalizados no parecen guardarse**

*Configurar*

Cuando un usuario agrega un nuevo trimestre personalizado desde el área de Proyectos de Configuración y hace clic en [!UICONTROL Guardar], no hay ninguna indicación visual de que se haya guardado. El usuario no ve un mensaje de confirmación y el botón [!UICONTROL Guardar] todavía se encuentra presente y activo. Sin embargo, si el usuario actualiza la página, puede ver que los trimestres nuevos aparecen en la lista de trimestres personalizados.

Si el usuario agrega un trimestre nuevo, hace clic en [!UICONTROL Guardar], no recibe ninguna confirmación de haberlo guardado, agrega otro trimestre sin actualizar la página y hace clic en [!UICONTROL Guardar] de nuevo, es posible que el segundo trimestre añadido no se guarde.

**[!UICONTROL La página de Solicitudes de trabajo del equipo] está en blanco**

*Equipos*

NOTA: Este problema solo se produce en el entorno de vista previa.

Cuando un usuario intenta abrir el área de [!UICONTROL Solicitudes de trabajo] en una página de equipo, la página está en blanco. El usuario puede ver la barra de navegación superior, pero no el contenido de la página.

+++

+++** Actualización de mantenimiento del 9 de junio de 2022**

**No se pueden seleccionar objetos que filtrar en las preferencias del [!UICONTROL Optimizador de portafolios]**

*Portafolios*

Cuando un usuario está en el [!UICONTROL Optimizador de portafolios] y visualiza la pestaña de los [!UICONTROL Filtros del proyecto] en el área de [!UICONTROL Preferencias], las casillas de verificación situadas junto a los objetos no están presentes. El usuario no puede marcar ni desmarcar casillas y, por lo tanto, no puede seleccionar objetos que filtrar.

**No se puede cambiar la [!UICONTROL Fecha planificada de inicio] o la [!UICONTROL Fecha planificada de finalización] cuando “[!UICONTROL Programar desde]” no está marcado**

*Proyectos*

Cuando un usuario intenta editar la [!UICONTROL Fecha planificada de inicio] o [!UICONTROL Fecha planificada de finalización] de un proyecto y la opción de “[!UICONTROL Programar desde]” para ese proyecto no está activada, las áreas de [!UICONTROL Fecha planificada de inicio] y [!UICONTROL Fecha planificada de finalización] están deshabilitadas y el usuario no puede editar esas fechas.

**No se puede editar el nivel de acceso de los usuarios**

*Usuarios*

Cuando un usuario con acceso de Planificador que incluye el acceso de Administración de usuarios (Usuarios del grupo) intenta editar a los usuarios del grupo para el que son administradores, se muestra el campo [!UICONTROL Nivel de acceso] desactivado y el usuario no puede editar el nivel de acceso.

+++

+++**[!DNL Workfront Scenario Planner] Actualización de mantenimiento el 9 de junio de 2022**

**Tamaño del panel izquierdo modificable en [!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Ahora puede cambiar el tamaño del panel izquierdo en un plan, en [!DNL Scenario Planner]. Esto permite que los nombres de iniciativa más largos se muestren completamente. Antes de esta actualización, los nombres de iniciativas más largos se cortaban.

+++

+++**[!DNL Workfront Fusion] Actualización de mantenimiento el 9 de junio de 2022**

**Los datos de los formularios personalizados no están disponibles en los módulos [!DNL Workfront Fusion] [!DNL Workfront]**

*[!DNL Workfront Fusion]*

Cuando un usuario está configurando un módulo de [!DNL Workfront] en [!DNL Workfront Fusion] e intenta seleccionar salidas para el módulo, los campos de los formularios personalizados no están visibles. Esto ocurre cuando el formulario personalizado se creó para un tipo de objeto [!DNL Workfront] y luego se le agregó otro tipo. [!DNL Workfront Fusion] solo muestra los campos de los formularios personalizados creados originalmente para el tipo de objeto seleccionado.

**No es posible desplazarse por la pantalla para ver todas las ejecuciones de escenario**

*[!DNL Workfront Fusion]*

Cuando un usuario está viendo el historial de ejecución de un escenario e intenta desplazarse hacia abajo para ver más ejecuciones, el usuario deja de cargarse y no puede verlas. Además, el usuario no puede volver a desplazarse hasta las ejecuciones más recientes.

+++

+++**Actualización de mantenimiento del 2 de junio de 2022**

**[!UICONTROL Optimizador de portafolios] muestra una puntuación de 0 cuando se usa un idioma distinto del inglés**

*Portafolios*

Cuando un usuario utiliza [!DNL Workfront] en un idioma distinto del inglés y visualiza el [!UICONTROL Optimizador de portafolios], la puntuación se muestra como 0. Esto puede ocurrir incluso cuando no se ha completado el caso empresarial.

**Valores de campo calculados incorrectos al crear un proyecto a partir de una plantilla**

*Proyectos*

Cuando un usuario crea un proyecto a partir de una plantilla que incluye campos calculados, los valores de campo que aparecen en el nuevo proyecto son incorrectos.

**No se pueden editar las [!UICONTROL Condiciones] en el área de [!UICONTROL Preferencias de proyecto] de [!UICONTROL Configuración]**

*[!UICONTROL Configurar]*

Cuando un usuario intenta editar las [!UICONTROL Condiciones] en el área de [!UICONTROL Preferencias de proyecto] de [!UICONTROL Configuración], la página está en blanco.

**Nueva limitación al número de caracteres de una actualización en vista previa**

*[!UICONTROL Distribuidor de cargas de trabajo]*

>[!NOTE]
>
>Esta actualización solo se aplica al entorno de vista previa.

Para mejorar el rendimiento del área de Actualizaciones, se ha introducido un nuevo límite en el número de caracteres que se pueden introducir en una actualización o en una respuesta a una actualización existente. El nuevo límite es de 15 000 caracteres. Esta actualización no cambió el número de caracteres permitidos al utilizar la API. El límite de caracteres de la API para las actualizaciones es de 4000. Actualizaciones
Compatibilidad con campos personalizados de tipo Escritura anticipada en los filtros del Distribuidor de cargas de trabajo

Ahora se admiten filtros basados en los campos personalizados de tipo [!UICONTROL Escritura anticipada] en el Distribuidor de cargas de trabajo. Antes de este parche, el filtrado para este tipo de campos personalizados no era posible en el Distribuidor de cargas de trabajo.

**No se pueden editar permisos en la función de un usuario**

*[!DNL Workfront Proof]*

Cuando un usuario intenta editar los permisos de “[!UICONTROL Resolver comentarios y aplicar acciones]” o “[!UICONTROL Compartir una prueba mediante el etiquetado]” en la función de un usuario en [!DNL Workfront Proof], los cambios no se guardan. El usuario recibe una notificación de que la plantilla se ha actualizado, pero si el usuario vuelve a abrir los permisos de funciones, puede ver que los cambios no se guardaron.

+++


## Actualizaciones en mayo de 2022

+++**Actualización de mantenimiento del 26 de mayo de 2022**

Estos problemas se solucionaron solo en la nueva experiencia de [!DNL Workfront]. [!DNL Adobe Workfront Classic] ya no es compatible.

Todas las funcionalidades de [!DNL Workfront Classic] se eliminarán en julio de 2022. Por favor, pase a la nueva experiencia lo antes posible.

**Separadores de rutas de exploración actualizados**

*[!DNL Workfront]*

NOTA: Esta actualización se publicó el 24 de mayo de 2022.

Hemos actualizado los separadores de rutas de exploración en todas las áreas donde hay disponibles rutas de exploración. Ahora, los objetos de las rutas de exploración están separados por barras verticales (|). Antes de esta actualización, estaban separados por barras inclinadas (/).

**No se pueden editar formularios personalizados con saltos de sección**

*Formularios personalizados*

Cuando un usuario intenta editar un formulario personalizado que tiene un salto de sección, no puede editar el formulario y ve el siguiente mensaje:

[!UICONTROL La seguridad de salto de sección especificada no se puede aplicar en todos los tipos de objetos]

**Problemas al imprimir los paneles en el PDF**

*Paneles*

Se han notificado los siguientes problemas al imprimir un panel en un PDF:
El PDF no imprime todas las filas del informe. Cuando faltan líneas, solo se muestra espacio en blanco.
El PDF incluye espacios en blanco entre los encabezados de columna y la primera fila del informe.

**[!DNL Portfolio Optimizer] muestra una puntuación de 0 cuando se usa un idioma distinto del inglés**

*Portafolios*

Cuando un usuario utiliza [!DNL Workfront] en un idioma distinto del inglés y visualiza el [!UICONTROL Optimizador de portafolios], la puntuación se muestra como 0. Esto puede ocurrir incluso cuando no se ha completado el caso empresarial.

**Algunos formularios personalizados no se muestran al editar una plantilla**

*Plantillas*

Cuando un usuario intenta editar los formularios personalizados en una plantilla haciendo clic en [!UICONTROL Editar] en el encabezado de la plantilla, la ventana [!UICONTROL Editar plantilla] solo muestra uno de los formularios personalizados adjuntos a la plantilla.

**El vínculo compartido al Distribuidor de cargas de trabajo muestra el trabajo asignado incorrectamente**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario ve el [!UICONTROL Distribuidor de cargas de trabajo] mediante un vínculo compartido, el [!DNL Workload Balancer] incluye [!UICONTROL Trabajo asignado] en la sección [!UICONTROL Trabajo no asignado]. [!UICONTROL Trabajo asignado] no tiene una sección aparte. Cuando el usuario ve el [!UICONTROL Distribuidor de cargas de trabajo] sin usar el vínculo compartido, el [!UICONTROL Trabajo asignado] se muestra según lo esperado.

+++

+++**Actualización de mantenimiento del 19 de mayo de 2022**

**No se puede crear una prueba a partir de un [!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Cuando un usuario intenta crear una prueba a partir de un [!DNL PowerPoint] que incluye un gráfico, la creación de la prueba falla.

**No se puede crear una prueba a partir de un documento [!UICONTROL Word]**

*[!DNL Workfront Proof]*

Cuando un usuario intenta crear una prueba a partir de un [!DNL Word] documento que incluye un gráfico, la creación de la prueba falla.

**No se puede agregar un mensaje personalizado al compartir una prueba**

*[!DNL Workfront Proof]*

Cuando un usuario está viendo una prueba, abre el área de [!UICONTROL Compartir prueba] y selecciona el botón [!UICONTROL Añadir mensaje personalizado], el usuario no puede escribir en el cuadro de texto que se abre. Cuando el usuario intenta escribir en este cuadro, este desaparece inmediatamente.

**No se puede cerrar la prueba**

*[!DNL Workfront Proof]*

Cuando un usuario está viendo una prueba e intenta cerrarla, falta la X para cerrar la prueba en la esquina superior derecha de la misma.

**No se puede agregar ni quitar el administrador del grupo**

*Grupos*

Si un usuario está viendo una página de [!UICONTROL Grupo] e intenta agregar o quitar un administrador de grupo mediante el área de [!UICONTROL Administradores de grupo] en el encabezado, los cambios no se guardan y el usuario ve el siguiente error:

[!UICONTROL Error ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]

**La barra de desplazamiento horizontal bloquea un elemento al final de la lista**

*Proyectos*

Cuando un usuario está viendo una lista con una vista que se extiende más allá de la pantalla, la barra de desplazamiento horizontal impide la vista del usuario del último elemento de la lista.

**“[!UICONTROL Error inesperado]” al convertir un problema en un proyecto mediante una plantilla**

*Listas*

Cuando un usuario intenta convertir un problema en un proyecto mediante una plantilla, el problema no se convierte y el usuario ve el siguiente mensaje:

[!UICONTROL Se produjo un error inesperado]

**El campo [!UICONTROL Estado] en una vista de plantilla de horas es ahora de solo lectura**

*Plantillas de horas*

Hemos cambiado el campo [!UICONTROL Estado] en una vista de plantilla de horas como de solo lectura. Antes de este cambio, los usuarios podían editar en línea el estado de una plantilla de horas, lo que les permitía anular la decisión de los aprobadores de las plantillas de horas.

+++

+++**Actualización de mantenimiento del 12 de mayo de 2022**

**[!UICONTROL El botón Guardar] no deja de cargarse al editar un proyecto**

*Proyectos*

Cuando un usuario está editando un proyecto e intenta guardarlo, observa que el botón [!UICONTROL Guardar] muestra la palabra “[!UICONTROL Cargando].” Si el usuario hace clic en este botón para guardar los cambios en el proyecto, el botón no responde y los cambios no se guardan.

**Las etiquetas de campo no aparecen al ver un objeto en [!UICONTROL Inicio]**

*Página de inicio*

Cuando el usuario selecciona un objeto de su [!UICONTROL Lista de trabajos en Inicio], el área a la derecha de la [!UICONTROL Lista de trabajos en Inicio] que muestra el objeto no incluye etiquetas de campo. Los valores de campo están presentes.

**El filtro rápido no se centra automáticamente en la barra de búsqueda**

*Listas*

Cuando un usuario está en una lista y hace clic en la lupa para filtrar rápidamente y, a continuación, empieza a escribir, el texto no aparece. Esto se debe a que el foco permanece en el icono de lupa en lugar de transferirse a la barra de búsqueda.

Al hacer clic en la barra de búsqueda, se traslada el foco y se permite al usuario introducir el texto de la búsqueda.

**Los usuarios no pueden editar en línea los campos en un informe**

*Informes*

Cuando un usuario intenta editar un campo de un informe y este se extrae de un formulario personalizado, no puede editar el campo. Esto ocurre cuando el formulario personalizado se creó originalmente para un tipo de objeto distinto del objeto al que está adjunto.

**Texto de etiqueta y de botón que no está visible al crear una prueba**

*[!DNL Workfront Proof]*

NOTA: Este problema solo se produce en el entorno de vista previa.

Cuando un usuario intenta crear una prueba, el texto no está visible para las opciones o los botones. Por lo tanto, el usuario no sabe qué representa cada opción o botón y no puede configurar la prueba.

+++

+++**Actualización de mantenimiento del 5 de mayo de 2022**

**No se puede agregar un nuevo Registro de facturación**

*Proyectos*

Cuando un usuario está en el área de [!UICONTROL Registros de facturación] de un proyecto y está usando la vista de [!UICONTROL Nuevo registro de facturación], si el usuario intenta agregar un nuevo registro de facturación, los campos de un nuevo registro de facturación no aparecen y no se puede crear el registro.

**Error al realizar una asignación por lotes en el [!UICONTROL Distribuidor de cargas de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario intenta realizar asignaciones en el [!DNL Workload Balancer] de un proyecto, se redirige al usuario a una página con el siguiente mensaje:

“[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]”

El usuario no puede salir de esta página hasta que actualice la página.

**Se ha actualizado la navegación para abrir el panel de [!UICONTROL Resumen] para tareas y problemas en el [!UICONTROL Distribuidor de cargas de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Ahora solo tiene que hacer clic en una tarea o en la barra de problemas del [!UICONTROL Distribuidor de cargas de trabajo] para abrir el panel Resumen. Antes de esta actualización, tenía que hacer clic en el icono de [!UICONTROL Abrir resumen] en la barra de herramientas y, a continuación, hacer clic en la tarea o el problema. Esto resultó ser una experiencia confusa que ahora se corrige. También puede hacer clic en el menú [!UICONTROL Más] junto al nombre de la tarea o del problema y, a continuación, hacer clic en [!UICONTROL Abrir resumen].

**El administrador del grupo no puede ver los detalles de los usuarios del grupo**

*Usuarios*

Cuando un usuario asignado a un nivel de acceso que incluya la configuración de acceso a [!UICONTROL Administración de usuarios (usuarios del grupo)] intenta ver los detalles de un usuario en su grupo y aparece el siguiente error:

“[!UICONTROL Intentémoslo de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]”

**No se puede eliminar el estado del grupo personalizado**

*Grupos*

Cuando un usuario intenta eliminar un estado de grupo personalizado de la página de [!UICONTROL Grupo], la página se queda en blanco y el estado no se elimina.

**La configuración de alertas por correo electrónico no es coherente entre el área de Contactos y los Detalles del usuario**

*[!DNL Workfront Proof]*

La configuración de alertas de correo electrónico que se muestra en la sección [!UICONTROL Contactos] de [!DNL Workfront Proof] para un usuario determinado son diferentes de la configuración de alertas de correo electrónico establecida en los [!UICONTROL Detalles del usuario].

**No se puede utilizar la herramienta Texto al realizar un comentario en una prueba**

*[!DNL Workfront Proof]*

Cuando un usuario realiza un comentario sobre una prueba e intenta abrir la herramienta [!UICONTROL Texto], esta no se abre y el usuario ve el siguiente mensaje:

“[!UICONTROL Los datos de texto de esta página se siguen descargando. Por favor, espere.]”

**Los correos electrónicos de prueba irán al correo electrónico principal del usuario**

*[!DNL Workfront Proof]*

Estamos realizando ajustes en la forma en que se envían las notificaciones de prueba por correo electrónico. Ahora, las notificaciones irán a la dirección de correo electrónico principal del usuario en lugar del correo electrónico de alias generado por el sistema.

Para obtener más información sobre por qué el sistema genera correos electrónicos con alias, consulte Sincronización de usuarios entre Adobe [!DNL Workfront] y [!DNL Workfront Proof].

+++

## Actualizaciones en abril de 2022

+++**Actualización de mantenimiento del 28 de abril de 2022**

**No es posible desplazarse hasta [!UICONTROL Guardar] al editar una plantilla de horas**

*Plantillas de horas*

Cuando un usuario está editando una plantilla de horas, no puede desplazarse por la ventana de edición lo suficientemente lejos como para ver el botón [!UICONTROL Guardar] y, por lo tanto, no puede editar la plantilla de horas.

**La firma electrónica ahora comprueba el ID de federación**

*Pruebas*

Al firmar una prueba electrónicamente, el sistema comprueba ahora el ID de federación si tiene SSO configurado en [!DNL Workfront Proof], además del correo electrónico en [!DNL Workfront].

Antes el sistema solo comprobaba el correo electrónico en Workfront.

+++

+++**Actualización de mantenimiento (Hot Fix) el 25 de abril de 2022**

**[!UICONTROL El Distribuidor de cargas de trabajo] no se carga**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario intenta abrir el [!UICONTROL Distribuidor de cargas de trabajo], el encabezado y la navegación izquierda se cargan, pero no así el contenido del Distribuidor de cargas de trabajo. El usuario ve cuadrados grises parpadeantes en lugar de datos. En ocasiones, parte del contenido se carga, pero el usuario sigue viendo cuadrados grises parpadeantes en los que faltarían datos.

+++

+++**Actualización de mantenimiento del 21 de abril de 2022**

**Añadir una tarea hace que la página salte hacia abajo**

*Tareas*

Cuando un usuario agrega una tarea debajo de una tarea existente en una lista, la página salta a la parte inferior de la lista. Aunque la nueva tarea se encuentra en el lugar correcto, el usuario debe desplazarse hacia atrás para localizarla.

**Los usuarios agregados a una prueba no pueden acceder al elemento de trabajo de la prueba en [!DNL Workfront]**

*Pruebas*

Si se agrega un usuario a un escenario en el flujo de trabajo de una prueba, este no se agrega al uso compartido de documentos y no obtiene permisos para el elemento de trabajo de la prueba en [!DNL Workfront]. Cuando el usuario se encuentra en [!DNL Workfront] e intenta abrir el elemento de trabajo al que está adjunta la prueba, verá el siguiente mensaje:

“[!UICONTROL No cuenta con acceso suficiente para ver este (objeto)]”

Este problema es específico de las pruebas ya creadas y de los usuarios que se agregan después del hecho. Agregar usuarios al flujo de trabajo antes de la creación de la prueba funciona según lo esperado.

**No se puede enviar el correo electrónico de restablecimiento de contraseña desde [!DNL Workfront]**

*Usuarios*

Cuando un usuario intenta enviar un correo electrónico de restablecimiento de contraseña desde una lista de usuarios en [!DNL Workfront], la opción para enviar el correo electrónico no está disponible.

**El botón muestra “[!UICONTROL Iniciar problema]” en lugar de “[!UICONTROL Iniciar solicitud]”**

*Solicitudes*

Cuando un usuario ve una solicitud asignada a su equipo, ve un “[!UICONTROL Iniciar problema]” en el encabezado en lugar de “[!UICONTROL Iniciar solicitud]”.

**“[!UICONTROL Deshacer comentario]” elimina los usuarios etiquetados**

*Actualizaciones*

Cuando un usuario etiqueta a otro usuario en un comentario, publica el comentario y, a continuación, selecciona la opción “[!UICONTROL Deshacer comentario]”, el comentario aparece en un cuadro de actualización como de costumbre, pero el usuario etiquetado no está en el [!UICONTROL Usuarios etiquetados] en la ventana

**No se puede desplazar al usar la vista de [!UICONTROL Hito] en un informe**

*Informes*

Cuando un usuario que está viendo un informe selecciona la vista de [!UICONTROL Hito], la página muestra la vista de Hito pero ya no se desplaza y el usuario no puede ver ningún Hito que esté más abajo en la página.

**Moneda incorrecta cuando el informe se muestra en el panel**

*Informes*

Cuando un usuario ve un informe en un panel, la moneda utilizada en el informe es incorrecta. Cuando el usuario ve el informe fuera del panel, la moneda es correcta.

**El filtro completado no muestra el elemento de trabajo completado**&#x200B;

*[!UICONTROL Página de inicio]*

Cuando un usuario ve su [!UICONTROL Lista de trabajos en Inicio] con el filtro de [!UICONTROL Completados] seleccionado, los elementos de trabajo completados no se muestran en la lista. Cuando el filtro de [!UICONTROL Todo] está seleccionado, los elementos completados se incluyen en la lista, lo que muestra que existen elementos completados.

**[!DNL Workfront]no se carga**

*[!DNL Workfront]*

Cuando un usuario intenta iniciar sesión en [!DNL Workfront], la página parece atascada en un bucle de redirecciones o actualizaciones, y no se carga.

+++

+++**Actualización de mantenimiento del 14 de abril de 2022**

**No se puede agregar una tarea desde un informe en una sección personalizada de una tarea**

*Tareas*

Cuando un usuario está viendo una sección personalizada en una tarea y la sección contiene un informe de tareas, el usuario no puede agregar una tarea desde ese informe. El botón [!UICONTROL Agregar tarea] resalta el informe, pero no abre una ventana para que el usuario añada una tarea.

**Botón Listo en una ubicación incorrecta al editar una vista**

*Vistas*

Cuando un usuario está editando una vista, el botón [!UICONTROL Listo] aparece en la parte superior de la pantalla y puede superponerse al texto.

El usuario puede editar la vista como de costumbre. La funcionalidad no se ve afectada.

**No se puede desplazar al usar la vista de [!UICONTROL Hito] en un informe**

*Informes*

Cuando un usuario que está viendo un informe selecciona la vista de [!UICONTROL Hito], la página muestra la vista de Hito pero ya no se desplaza y el usuario no puede ver ningún Hito que esté más abajo en la página.

**Pantalla en blanco al ver las actualizaciones**

*Actualizaciones*

Cuando un usuario está viendo actualizaciones y desplaza la pantalla para ver actualizaciones más abajo, la pantalla se queda en blanco y el usuario no puede ver ninguna actualización.

**Error al asignar por lotes al usuario a una tarea que no está asignada a la función del usuario**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario del [!UICONTROL Distribuidor de cargas de trabajo] intenta asignar tareas a un usuario cuya función de trabajo no coincide con la función de trabajo asignada a las tareas, el usuario ve un mensaje que indica que la tarea se asignará mediante la función de trabajo principal del usuario asignado. Sin embargo, cuando el usuario hace clic en “[!UICONTROL Asignar]”, las tareas no están asignadas y el usuario ve el siguiente error:

“[!UICONTROL Error. El servidor ha encontrado un error desconocido.]”

+++

+++**Actualización de mantenimiento del 7 de abril de 2022**

**Los usuarios agregados a las pruebas tienen funciones incorrectas**

*Pruebas*

Cuando un usuario agrega otro usuario a una prueba, la función de ese usuario en la prueba se establece como de “[!UICONTROL Solo lectura]” a pesar de la función de prueba real del usuario.

**No se puede enviar el correo electrónico de restablecimiento de contraseña al usuario**

*Usuarios*

Cuando un usuario intenta enviar un restablecimiento de contraseña a otro usuario, ve que la opción de [!UICONTROL Enviar correo electrónico de contraseña olvidada] no está disponible en el menú de [!UICONTROL Más].

**[!UICONTROL Actualizar todo] envía actualizaciones a perfiles de usuario en lugar de a proyecto**

*Actualizaciones*

Cuando un usuario está viendo el área de [!UICONTROL Personas] de un proyecto y selecciona la opción de [!UICONTROL Actualizar todo] y luego introduce una actualización, la actualización no se anuncia en el propio proyecto. En su lugar, se publica en los perfiles de usuario individuales de cada usuario del proyecto.

**Número excesivo de páginas al imprimir actualizaciones**

*Actualizaciones*

Cuando un usuario está viendo un flujo de actualización que sería más de una página impresa e intenta imprimir la página, la pantalla de impresión muestra que el número de páginas es muy superior al número real de páginas necesarias para imprimir las actualizaciones. Si el usuario intenta imprimir en el PDF, se producirá un error en la creación del PDF.

**Los usuarios no pueden ver la lista completa de entidades compartidas con un informe cuando la opción “[!UICONTROL Visible en todo el sistema]” está activada**

*Informes*

Al compartir informes con varias entidades que se muestran en la ventana [!UICONTROL Acceso a informes], los usuarios no pueden desplazarse hasta la parte inferior de la lista para ver la lista completa cuando la configuración de “[!UICONTROL Visible en todo el sistema]” está activada.

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

**Tareas completadas que se muestran en [!UICONTROL Lista de trabajos en Inicio]**

*[!UICONTROL Página de inicio]*

Cuando un usuario está viendo su [!UICONTROL Lista de trabajos en Inicio], verá Tareas completadas en la lista, incluso cuando la opción para mostrar Tareas completadas no esté seleccionada.

**El botón Programar no está visible para programar la actualización de la zona protegida**

*Entorno de zona protegida*

El botón [!UICONTROL Programar] utilizado para programar una actualización de zona protegida no está visible en el titular superior del entorno de entorno de zona protegida.

**Los cambios en un campo calculado afectan a todos los campos calculados de un formulario**

*Formularios personalizados*

Cuando un usuario se encuentra en el Generador de formularios personalizados y cambia el valor de un formulario calculado, todos los campos calculados del formulario muestran el nuevo valor. Esto puede afectar a los campos calculados nuevos o existentes.

**Colores que parpadean en el creador de formularios personalizado**

*Formularios personalizados*

Cuando un usuario trabaja con campos calculados en el generador de formularios personalizado, los colores de los campos y las expresiones parpadean.

**[!UICONTROL No se puede rechazar una aprobación]**

*Rutas de aprobación*

Cuando un usuario intenta rechazar una aprobación, el botón [!UICONTROL Rechazar] no responde y la aprobación no se rechaza.

**[!UICONTROL La pestaña Proyectos] tiene el valor predeterminado de la sección Todos los proyectos a pesar de la selección anterior**

*Proyectos*

Cuando un usuario va a una página de Proyectos a través de una pestaña que se ha incrustado como parte de la plantilla de diseño, la página toma el valor predeterminado del área de [!UICONTROL Todos los proyectos] de la navegación izquierda. Esto ocurre incluso cuando el usuario elige otra área de navegación izquierda y luego sale de la página Proyectos y vuelve.

+++


## Actualizaciones en marzo de 2022

+++**Actualización de mantenimiento del 31 de marzo de 2022**

**Zonas horarias no coherentes entre [!DNL Workfront] y [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Cuando el perfil de un usuario está establecido en una zona horaria específica en [!DNL Workfront], la zona horaria del usuario en [!DNL Workfront Proof] está configurada en una zona horaria diferente.

**El vínculo para enviar un documento solicitado lleva a una página en blanco**

*Documentos*

Cuando un usuario recibe una solicitud de envío de un documento y hace clic en el enlace al objeto donde se solicitó, el enlace dirige a una página en blanco. Esto puede ocurrir al hacer clic en un enlace en un correo electrónico o en una notificación dentro de la aplicación.

**El grupo se asigna incorrectamente al convertir el problema en proyecto**

Grupos

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, la funcionalidad es:

* Si la plantilla tiene un grupo asignado, ese grupo se muestra en la ventana de conversión de problemas como el grupo para el nuevo proyecto.
* Si la plantilla no tiene ningún grupo asignado, el grupo predeterminado del usuario que está convirtiendo el problema se muestra en la ventana de conversión del problema como el grupo para el nuevo proyecto.
* Si la plantilla no tiene grupo, el nuevo proyecto debe heredar el grupo del proyecto del problema.

**No se puede adjuntar un formulario personalizado de objeto cruzado a la cola de solicitud**

Solicitudes

Cuando un usuario intenta agregar un formulario personalizado de objetos cruzados a la página de detalles de una cola, el formulario de objetos cruzados no aparece en la lista desplegable de formularios disponibles y el usuario no puede seleccionarlo para agregarlo a los detalles de la cola.

**Los usuarios no pueden tener asignada una función de trabajo secundario en [!UICONTROL Distribuidor de cargas de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario intenta asignar otro usuario a una tarea de la [!UICONTROL Distribuidor de cargas de trabajo], y la tarea se asigna a una función de trabajo que no sea la función de trabajo principal del usuario asignado, el usuario se asigna a la tarea por su función de trabajo principal y se muestra el siguiente mensaje:

“&lt;Name> no coincide con la función de &lt;Task role assignment>. 1 elemento de trabajo asignado actualmente a la función &lt;Task role assignment> se asignará a &lt;Name> en la función de &lt;Primary job role>.”

Esto ocurre incluso si el usuario tiene la función de trabajo de la asignación de funciones de tarea como rol secundario.

**Problema con la barra del panel de exploración “Mostrar más elementos de trabajo”**&#x200B;

*Agile*

Cuando un usuario hace clic en el barra [!UICONTROL Mostrar más elementos de trabajo] en un panel de exploración y luego se desplaza para ver los nuevos elementos, la barra de [!UICONTROL Mostrar más elementos de trabajo] se fija al panel de exploración y se mueve con él al desplazarse. Esto puede hacer que las tarjetas sean difíciles de leer.

**Aparecen puntos rojos en los campos obligatorios en los formularios personalizados**

Formularios personalizados

Cuando un usuario ve un campo obligatorio en un formulario personalizado, ve dos puntos rojos debajo del asterisco que indican que el campo es obligatorio.

**Menú desplegable de tiempo cortado en mensajes**

*Informes*

Cuando un usuario está rellenando las solicitudes de un informe y encuentra un selector de fechas, el selector de horas situado en la parte inferior del selector de fechas no muestra las horas posteriores a las 2 y el usuario no puede seleccionar ningún valor de hora que no sea 1 o 2.

+++

+++**Actualización de mantenimiento (Hot Fix) el 29 de marzo de 2022**

**No se pueden modificar ni guardar cálculos en el Creador de formularios personalizados**

*Formularios personalizados*

Si un usuario introduce manualmente un cálculo en un campo de cálculo del Creador de formularios personalizados y lo guarda, el cálculo no se guarda. Si el usuario vuelve a abrir el formulario personalizado, ese campo está en blanco.

Si un usuario introduce un cálculo en un campo de cálculo del Creador de formularios personalizados mediante los menús desplegables y guarda el formulario, se guarda ese valor. Sin embargo, si el usuario vuelve a abrir el formulario personalizado, no puede editar este campo ni quitar el valor, ni manualmente ni con la lista desplegable.

NOTA: Esta corrección del problema incluye funcionalidad adicional. Ahora, cuando empieza a escribir en un campo calculado, las posibles expresiones o cálculos se muestran en un menú desplegable inferior, del mismo modo que en el Editor de cálculos. Haga clic en un elemento de la lista desplegable para agregarlo al campo calculado.

+++

+++**Actualización de mantenimiento del 24 de marzo de 2022**

**Zonas horarias no coherentes entre [!DNL Workfront] y [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Cuando el perfil de un usuario está establecido en una zona horaria específica en [!DNL Workfront], la zona horaria del usuario en [!DNL Workfront Proof] está configurada en una zona horaria diferente.

**Error de campo obligatorio para campos personalizados rellenados al adjuntar una plantilla**

*Proyectos*

Al adjuntar una plantilla con campos personalizados requeridos a un proyecto en el que el campo ya existe y está rellenado, los usuarios ven el siguiente error: “[!UICONTROL Hay campos incompletos. Introduzca valores para los campos obligatorios antes de continuar.]”
Hacer clic en “[!UICONTROL Llévame allí]” les permite ver que los campos están rellenados y que pueden adjuntar la plantilla correctamente.

**El [!UICONTROL Distribuidor de cargas de trabajo] parpadea al alternar entre fechas**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Las horas del usuario que aparece primero en la sección [!UICONTROL Distribuidor de cargas de trabajo] no se muestra al actualizar la cronología. El usuario y sus horas se muestran con todos los cuadros grises que parpadean. Esto sucede si se mueve hacia adelante y hacia atrás en la cronología.

La actualización del filtro parece restablecer la visualización. Sin embargo, al moverse hacia atrás y hacia adelante en la cronología, se vuelve a mostrar el flash y no se muestran las horas del usuario.

**La terminología personalizada no es coherente**

*Plantillas de diseño*

Los usuarios informan de que, cuando el administrador de [!DNL Workfront] personaliza la terminología de algunos objetos mediante una plantilla de diseño, el nuevo nombre de objeto aparece de forma incoherente en la interfaz.

Por ejemplo, en la página de [!UICONTROL Proyectos], todavía puede ver el título de la página como “[!UICONTROL Proyectos]”, aunque el administrador de [!DNL Workfront] haya cambiado el nombre de “[!UICONTROL Proyectos]” por otra cosa.

Esto causa confusión para los usuarios finales.

+++

+++**Actualización de mantenimiento del 17 de marzo de 2022**

**Las miniaturas y las imágenes principales están en blanco al ver archivos de varias páginas mediante el [!DNL Safari] explorador**

*[!DNL Workfront Proof]*

Cuando un usuario intenta ver un archivo con varias páginas en el explorador [!DNL Safari], las imágenes de página en miniatura están en blanco. En ocasiones, la imagen principal también puede estar en blanco.

**Lista de usuarios incorrecta al realizar asignaciones por lotes en el [!UICONTROL Distribuidor de cargas de trabajo]**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Cuando un usuario realiza una asignación por lotes en la [!UICONTROL Distribuidor de cargas de trabajo] y selecciona un proyecto y una función de trabajo, la lista de usuarios disponibles es incorrecta. Puede mostrar usuarios sin la función de trabajo o los permisos del proyecto, y los usuarios con la función de trabajo y los permisos del proyecto no aparecen en la lista.

**[!UICONTROL La ordenación no funciona en los informes]**

*Informes*

Cuando un usuario hace clic en una columna para ordenarla, la clasificación parece funcionar, pero instantáneamente los resultados vuelven a la clasificación original tal como se muestra antes de hacer clic en la columna. No se conserva la ordenación de ninguna columna.

**Seleccionar “[!UICONTROL Nada]” revierte a la agrupación de [!UICONTROL Informe predeterminado]**

*Informes*

Cuando un informe tiene una agrupación integrada y el usuario intenta seleccionar “[!UICONTROL Nada]” en el menú desplegable de [!UICONTROL Agrupación], el informe se muestra en breve sin agrupar y, a continuación, revierte a la agrupación de [!UICONTROL Informe predeterminado].

**Se ha eliminado la pestaña “[!UICONTROL Acceso a modelos]” de las preferencias de modelos**

*Modelos*

NOTA: Este problema solo se produce en el entorno de vista previa.

La pestaña [!UICONTROL Acceso a modelos] se ha eliminado del modal de preferencias de modelos. No se ha eliminado ninguna funcionalidad de las preferencias de modelos.

+++

+++**Actualización de mantenimiento (Hot Fix) el 14 de marzo de 2022**

**No se puede desplazar hacia abajo en la lista de usuarios al realizar la asignación en el panel Kanban**

*Agile*

Cuando un usuario está viendo un panel [!DNL Kanban] e intenta realizar una asignación, la lista de usuarios que aparece cuando escriben continúa saltando hacia arriba a medida que se desplazan hacia abajo. El usuario no puede seleccionar un usuario que no esté cerca de la parte superior de la lista y no puede guardar el cambio de asignación.

La vista de **[!UICONTROL Hito] en el informe de proyecto causa un error**

*Informes*

Al mostrar un informe de proyecto con la vista de [!UICONTROL Hito], los usuarios reciben un error de “[!UICONTROL APIModel INTERNAL no admite namedQuery TILE:milestone-view (UIVW)]”.

**La terminología personalizada no es coherente**

*Plantillas de diseño*

Los usuarios informan de que, cuando el administrador de [!DNL Workfront] personaliza la terminología de algunos objetos mediante una plantilla de diseño, el nuevo nombre de objeto aparece de forma incoherente en la interfaz.

Por ejemplo, en la página de [!UICONTROL Proyectos], todavía puede ver el título de la página como “[!UICONTROL Proyectos]”, aunque el administrador de [!DNL Workfront] haya cambiado el nombre de “[!UICONTROL Proyectos]” por otra cosa.

Esto causa confusión para los usuarios finales.

**No se pueden actualizar los cálculos para campos calculados existentes**

*Formularios personalizados*

Los usuarios no pueden actualizar o cambiar los cálculos en los campos calculados. Si el campo se ha creado y guardado con sin cálculo, cada vez que intente agregar una expresión y guardar/aplicar, el generador vuelve a estar en blanco.

Si crea un campo calculado con una expresión determinada y la guarda, cada vez que intenta cambiar el cálculo, vuelve a su valor anterior.

**[!UICONTROL Parámetro no válido] error al restablecer contraseñas**

*Inicio de sesión*

Los usuarios no pueden restablecer sus contraseñas en ningún entorno. Cuando escriben su correo electrónico e intentan continuar, ven un error.

[!UICONTROL Error: Parámetro no válido: Valor del parámetro de búsqueda “domain”].

+++

+++**Actualización de mantenimiento del 10 de marzo de 2022**

**Problemas al iniciar sesión en el entorno de vista previa**

*Inicio de sesión*

Se han notificado los siguientes problemas con el inicio de sesión en el entorno de vista previa.

Cuando un usuario intenta iniciar sesión en el entorno de vista previa, aparece un mensaje que indica que ha introducido el ID o la contraseña incorrectos.

Cuando un usuario intenta restablecer su contraseña, aparece el error “[!UICONTROL Se encontraron varios usuarios con la dirección de correo electrónico <example@example.com>]”

**Los formularios personalizados se cargan lentamente en el área de [!UICONTROL Detalles del proyecto]**

*Proyectos*

Cuando un usuario intenta ver el área de [!UICONTROL Detalles del proyecto], los formularios personalizados que estén adjuntos al proyecto se cargarán solo después de un retraso de 15 segundos o más. La opción de [!UICONTROL Agregar formularios personalizados] también se ve afectada por este retraso.

**Los valores de los campos de formulario personalizados no se guardan en el panel de resumen del documento**

*Documentos*

Cuando un usuario actualiza los campos de formulario personalizados en el panel de resumen del documento y uno o más de ellos es un campo de tipo “delante”, y luego guarda los cambios y se desplaza fuera del panel de resumen, las actualizaciones no se guardan. Esto solo se produce cuando se edita un campo typeforward, aunque todos los campos se ven afectados.

**Datos que no se conservan al convertir plantillas debido a niveles de acceso de uso compartido de plantillas**

*Proyectos*

Cuando un usuario que tiene acceso a Vista en una plantilla compartida intenta convertir un problema en un proyecto, cualquier dato de secciones de formulario personalizadas que requiera [!UICONTROL Contribución] o el acceso superior a la vista no se transfiere al proyecto creado.

**Error al cargar la nueva versión del documento**

*Documentos*

Cuando un usuario intenta cargar una nueva versión de un documento desde la lista de documentos, el documento no se carga y el usuario ve el siguiente error:

[!UICONTROL Error de No se puede invocar “com.attask.boz.Document.getCurrentVersion()” porque “documento” es nulo]

**No se pueden editar las tasas de facturación**

*Proyectos*

Cuando un usuario intenta editar una tasa de facturación en la pestaña [!UICONTROL Tasas de facturación] de un proyecto, al hacer clic en el botón [!UICONTROL Editar] se abre la ventana [!UICONTROL Editar] brevemente antes de que el usuario pueda editar la tasa de facturación. Al volver a hacer clic en el botón, no se abre la ventana de edición.

**El vínculo público para el documento lleva a una página en blanco**

*Documentos*

Cuando un usuario intenta abrir un documento mediante un vínculo público, el vínculo lleva a una página en blanco. Esto ocurre cuando el vínculo se abre en una ventana en la que una sesión activa de [!DNL Workfront] está abierta.

**Error de ¡Uy! al añadir tarea o problema a la lista**

*Tareas y problemas*

Cuando un usuario que no es administrador intenta agregar una tarea o problema a una lista y rellena campos personalizados, la tarea o el problema no se crea y el usuario ve el siguiente error:

[!UICONTROL Error ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]

**Si se deja una actualización después de un cambio de estado, el objeto se convierte en un estado anterior**

Proyectos, tareas y problemas

Si se cambia el estado de un proyecto, tarea o problema y se empieza inmediatamente a escribir una actualización sin actualizar la página, el cuadro de actualización muestra el estado anterior. Si se publica la actualización, el objeto vuelve al estado anterior.

**Los usuarios agregados a las pruebas tienen funciones incorrectas**

*Pruebas*

Cuando un usuario agrega otro usuario a una prueba, la función de ese usuario en la prueba se establece como de “[!UICONTROL Solo lectura]” a pesar de la función de prueba real del usuario.

Solución alternativa: Establezca la función de prueba del usuario en su perfil en algo distinto y, a continuación, restablezca la función correcta.

**El formulario personalizado no se carga al convertir un problema a un proyecto mediante una plantilla**

*Formularios personalizados*

Cuando un usuario intenta convertir un problema en un proyecto mediante una plantilla, es posible que uno o más de los formularios personalizados adjuntos a la plantilla no se carguen. Cuando el usuario configura la plantilla para el nuevo proyecto, en lugar de los formularios personalizados, ve el siguiente mensaje:

“[!UICONTROL Se ha producido un error, no se pudo cargar el formulario].”

**El usuario no puede agregar problemas en línea con el campo desplegable personalizado que se muestra en la vista**

*Listas*

Cuando un usuario añade un problema en línea y hay una vista personalizada con campos desplegables personalizados aplicados a la lista, se produce un error cuando solo rellenan el campo desplegable. El usuario tiene acceso para editar formularios personalizados y es el propietario del proyecto con derechos de administración del proyecto.

[!UICONTROL Error: ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]

**Los permisos para agregar tareas a un proyecto no son necesarios para mover o copiar una tarea al proyecto**

*Tareas*

Ahora puede mover o copiar una tarea a otra tarea de un proyecto sin tener permisos para agregar tareas al proyecto de destino. Debe tener permisos para agregar tareas al menos a una de las tareas del proyecto de destino. Antes de esta actualización, era necesario tener permisos para agregar tareas al proyecto para mover o copiar una tarea al proyecto o a cualquiera de sus tareas.  Esta actualización ya está disponible en el entorno de producción. Ha estado disponible en el entorno de vista previa a partir de la actualización de mantenimiento del 24 de marzo de 2022.

NOTA: Esta actualización estará disponible en el entorno de producción al copiar o mover problemas después de la versión de producción 22.2. Para obtener más información sobre la versión actual, consulte workfront.com/release.

**El menú desplegable Preguntar está desactivado**

*Informes*

Cuando se utiliza una solicitud en un informe, se cortan los menús desplegables que permiten seleccionar los criterios de filtrado para el informe. Como resultado, no se muestran los criterios de la parte inferior del menú desplegable de selección.

**El elemento de trabajo vuelve al estado anterior cuando se realiza una actualización**

*Actualizaciones*

Cuando un usuario cambia el estado de un elemento de trabajo en el encabezado, el estado no se actualiza en el área de [!UICONTROL Actualizar]. Si el usuario realiza una actualización, la lista desplegable sigue mostrando el estado anterior. Cuando se guarda la actualización, este estado anterior e incorrecto sobrescribe el estado establecido en el encabezado.

+++

+++**Actualización de mantenimiento del 3 de marzo de 2022**

**No se puede agregar el documento desde [!DNL Google Drive]**

*Documentos*

Cuando un usuario intenta agregar un documento desde [!DNL Google Drive], la selección no responde y el usuario no puede seleccionar documentos para agregar.

**Los usuarios etiquetados no se agregan al subproceso de actualización**

*Actualizaciones*

Cuando se etiqueta a un usuario en una actualización, no se muestra en el área de “[!UICONTROL Para]” de la actualización o de sus respuestas.

**El usuario de prueba tiene dos cuentas de prueba independientes**

*[!DNL Workfront Proof]*

Una dirección de correo electrónico del usuario en [!DNL Workfront Proof] puede estar en dos cuentas independientes con ID distintos, lo que proporciona al usuario dos cuentas. Esto puede dificultar la localización de la cuenta correcta.

**Se muestra el error ¡Uy! en los encabezados de los informes**

*Informes*

Cuando un usuario ve un informe, aparece el siguiente error en el encabezado del informe:

“[!UICONTROL Intentémoslo de nuevo. ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]”

Si el usuario está viendo un panel, el error puede aparecer en el encabezado de todos los informes del panel.

**Los datos de los campos Solo edición de administración de formulario personalizado no se conservan al convertir problemas en proyectos**

*Proyectos*

Cuando un usuario no administrador intenta convertir un problema a un proyecto mediante una plantilla y el problema contiene datos en campos que solo un administrador puede editar, los datos de esos campos no se transfieren al nuevo proyecto.

Cuando un administrador convierte el problema, los datos se transmiten al nuevo proyecto según lo esperado.

El límite de tamaño de archivo de **[!DNL XLS] y [!DNL XLSX] disminuyó temporalmente a 100 MB para pruebas**

*Prueba*

Para solucionar un problema de seguridad, hemos limitado temporalmente el tamaño máximo de archivo para [!DNL XLS] y [!DNL XLSX] a 100 MB al crear una prueba.

NOTA: Esta actualización se realizó en el entorno de vista previa el 24 de febrero y estará en el entorno de producción el 3 de marzo.

**Actualización a Workfront Search**

Buscar

Esta semana comenzó un despliegue gradual para actualizar la infraestructura de la funcionalidad de búsqueda de [!DNL Workfront]. La actualización hará que las futuras mejoras en Buscar sean más sencillas y fiables. Con estos cambios, los elementos se agregaron a [!DNL Workfront] se indexarán más rápido y, por lo tanto, regresarán antes en los resultados de búsqueda.

La implementación por fases continuará durante 2 semanas.

**Barras de herramientas actualizadas para informes dentro de paneles**

Informes

Los informes incluidos en los paneles ahora muestran una nueva barra de herramientas. Esta barra de herramientas forma parte de las actualizaciones a listas e informes que se producen a lo largo de [!DNL Workfront].

+++


## Actualizaciones en febrero de 2022

+++**Actualización de mantenimiento (Hot Fix) el 24 de febrero de 2022**

**Datos que no se conservan al convertir problemas en proyectos si el campo está oculto en la plantilla**

*Proyectos*

Cuando un usuario convierte un problema en una plantilla y esta incluye un formulario personalizado que muestra u oculta campos basados en los valores de otros campos, cualquier dato de los campos que esté oculto en la plantilla (sin datos) en el momento de la conversión no se lleva al nuevo proyecto.

**No se puede exportar el planificador de recursos por función**

*Planificador de recursos*

Cuando un usuario intenta exportar el [!DNL Resource Planner] al usar la opción de [!UICONTROL Ver por función], la exportación no se realiza correctamente y el usuario recibe un correo electrónico con el siguiente mensaje:

Se produjo un error al exportar los datos del [!DNL Resource Planner].

**El botón Copiar solicitud no funciona**

*Solicitudes*

Cuando un usuario intenta copiar una solicitud, el botón [!UICONTROL Copiar solicitud] no funciona si el usuario no tiene acceso de Vista al tema de la cola.

+++

+++**Actualización de mantenimiento del 24 de febrero de 2022**

**Los datos de formulario personalizados desaparecen cuando se rellenan otros campos de formulario**

*Formularios personalizados*

Cuando un usuario rellena un formulario personalizado como parte de la conversión de un problema a un proyecto, rellenar un campo personalizado puede hacer que desaparezcan los datos de otro campo personalizado. Si el usuario vuelve a introducir los datos que faltan, cuando intenta crear el proyecto, verá el siguiente mensaje de error:

“[!UICONTROL Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado]”

**Falta el campo “[!UICONTROL Este proceso de aprobación lo puede utilizar…]””**

*Rutas de aprobación*

Cuando un usuario está creando o editando un proceso de aprobación en el área de [!UICONTROL Configuración], el campo “[!UICONTROL Este proceso de aprobación lo puede utilizar…]”. Esto puede ocurrir al crear un proceso de aprobación o al editar uno existente.

**El administrador del sistema no puede reasignar usuarios al eliminar un grupo**

*Grupos*

Cuando un administrador del sistema elimina un grupo, solo tendrá la opción de reasignar los usuarios de ese grupo a grupos para los que el administrador del sistema sea un administrador de grupo. Otros grupos no aparecen en la lista desplegable y el administrador no puede seleccionarlos.

**Error al convertir un problema en un proyecto**

*Proyectos*

Cuando un usuario intenta convertir un problema en un proyecto mediante una plantilla y agrega o quita formularios personalizados de la plantilla, el problema no se convierte y el usuario ve el siguiente mensaje:

[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]

**No se puede abrir la prueba; la página se actualiza**

*Pruebas*

Cuando un usuario intenta abrir una prueba, esta no se puede abrir. Finalmente, la página se actualiza.

El límite de tamaño de archivo de **[!DNL XLS] y [!DNL XLSX] disminuyó temporalmente a 100 MB para pruebas**

*Prueba*

Para solucionar un problema de seguridad, hemos limitado temporalmente el tamaño máximo de archivo para [!DNL XLS] y [!DNL XLSX] a 100 MB al crear una prueba.

NOTA: Esta actualización se realizará en el entorno de vista previa el 24 de febrero y en el entorno de producción el 3 de marzo.

**Los permisos para agregar tareas o problemas a un proyecto no son necesarios para mover o copiar una tarea o un problema en el proyecto**

*Proyectos*

Ahora puede mover o copiar una tarea o un problema en otra tarea de un proyecto sin tener permisos para agregar tareas o problemas al proyecto de destino. Debe tener permisos para agregar tareas o problemas al menos a una de las tareas del proyecto de destino. Antes de esta actualización, era necesario tener permisos para agregar tareas o problemas al proyecto para mover o copiar una tarea o un problema al proyecto o a cualquiera de sus tareas. Esta actualización solo está disponible en el entorno de vista previa.

NOTA: Esta actualización estará disponible en el entorno de producción al realizar o mover tareas el 10 de marzo. Esta actualización estará disponible en el entorno de producción al copiar o mover problemas con la versión de producción 22.2. Para obtener más información sobre la versión actual, consulte workfront.com/release.

**Actualización a Workfront Search**

*Buscar*

Esta semana comenzó un despliegue gradual para actualizar la infraestructura de la funcionalidad de búsqueda de [!DNL Workfront]. La actualización hará que las futuras mejoras en Buscar sean más sencillas y fiables. Con estos cambios, los elementos se agregaron a [!DNL Workfront] se indexarán más rápido y, por lo tanto, regresarán antes en los resultados de búsqueda.

La implementación por fases continuará durante 2 semanas.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 18 de febrero de 2022**

**Se agregó la validación de tipo de valor de campo a las propiedades de elementos de lista de [!DNL Anaplan]**

*[!DNL Adobe Workfront Fusion]*

Se ha corregido un problema que permitía a los usuarios colocar el tipo de datos incorrecto en campos para las propiedades de elementos de lista. La validación del tipo de propiedad permite a [!DNL Fusion] garantizar que se envía a Anaplan el tipo de datos correcto, se eliminan los errores causados por tipos de datos incorrectos.

+++

+++**Actualización de mantenimiento del 17 de febrero de 2022**

**Error al eliminar el predecesor de la pestaña Predecesores**

*Tareas*

Cuando un usuario intenta eliminar un predecesor del [!UICONTROL Predecesores] en una tarea, la tarea no se elimina y el usuario ve el siguiente error:

[!UICONTROL No se encontró la tarea con valores claves principales &quot;&quot;]

**Error al abrir la página de usuarios**

*Usuarios*

Cuando un usuario intenta abrir la página de [!UICONTROL Usuarios], la página no se carga y el usuario ve el siguiente mensaje de error:

[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con [!DNL Workfront] para que podamos averiguar qué ha fallado y solucionarlo.]

**Superposición de elementos en el encabezado de un informe en un panel**

*Paneles*

Cuando un usuario ve un informe en un panel, ve que el icono de agrupación y la etiqueta se superponen con los vínculos a [!UICONTROL Detalles] y [!UICONTROL Resumen].

**Problemas con el menú de “[!UICONTROL Más]” para documentos y pruebas**

*Documentos*

Cuando un usuario selecciona un documento o una prueba en una lista de documentos de [!DNL Workfront Classic]y, a continuación, hace clic en “[!UICONTROL Más],” pueden ver uno de los siguientes problemas: El botón no responde
Todas las opciones bajo el botón están etiquetadas como “[!UICONTROL objeto Objeto]” y no se pueden usar.

**Error de “Debe ser administrador del sistema” al crear un proyecto**

*Proyectos*

Cuando un usuario que no es administrador intenta crear un proyecto y adjunta un formulario personalizado que tiene una sección disponible solo para los administradores, no puede crear el proyecto y verá el siguiente error:

“Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado”

**Los datos de la sección de solo administración del formulario personalizado no se conservan al convertir problemas en proyectos**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto mediante una plantilla que tiene un formulario personalizado con una sección de solo administración, los datos de la sección de solo administración no se transfieren al nuevo proyecto. Esto ocurre incluso si un administrador está convirtiendo el problema.

+++

+++**Actualización de mantenimiento del 10 de febrero de 2022**

**Error de “[!UICONTROL Debe ser administrador del sistema]” al crear un proyecto**

*Proyectos*

Cuando un usuario que no es administrador intenta crear un proyecto y adjunta un formulario personalizado que tiene una sección disponible solo para los administradores, no puede crear el proyecto y verá el siguiente error:

“[!UICONTROL Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado]”

**Los usuarios desactivados y reactivados no aparecen en los [!UICONTROL contactos de Proof]**

*[!DNL Workfront Proof]*

Cuando un usuario ve su lista de contactos en [!DNL Workfront Proof], los usuarios desactivados y reactivados no aparecen en la lista.

**Mensaje “Se ha producido un error” al convertir un problema en un proyecto mediante una plantilla**

*Proyectos*

Cuando un usuario que no es administrador intenta convertir un problema en un proyecto mediante una plantilla, los campos de formulario personalizados que solo son visibles para los administradores muestran el siguiente mensaje:

“[!UICONTROL Se ha producido un error, no se pudo cargar el formulario]”

**Error de “No se puede cargar el contenido de la página” al ver las preferencias del proyecto**

*Configurar*

Cuando un usuario administrador intenta ver proyectos, tareas o problemas en [!UICONTROL Preferencias de proyecto] en el área de [!UICONTROL Configuración], la página no se carga y el usuario ve el siguiente error:

“[!UICONTROL No se puede cargar el contenido de la página. Pruebe a actualizar la página.]”

+++

+++**Actualización de mantenimiento del 3 de febrero de 2022**

**[!UICONTROL Error de BizContext] al iniciar sesión**

*Inicio de sesión*

Cuando un usuario intenta iniciar sesión en [!DNL Workfront], el inicio de sesión no se ha realizado correctamente y aparece el siguiente mensaje:

“[!UICONTROL Intentémoslo de nuevo. Error de base de datos: Error de BizContext commit.]”

Se ha informado de este problema en el entorno de vista previa.

**El flujo de actualización del problema desaparece si el problema está pendiente de aprobación**

*Actualizaciones*

Cuando un usuario hace clic en el cuadro [!UICONTROL Nueva actualización] en el flujo de actualización de un problema que está pendiente de aprobación, desaparece todo el flujo de actualización.

**Error al cargar la nueva versión de un documento**

*Documentos*

Cuando un usuario intenta crear una nueva versión de un documento, esta no se genera y el usuario ve uno de los siguientes mensajes:

* [!UICONTROL documentID no puede ser nulo]
* [!UICONTROL Error: Parámetro no válido: valor “indefinido” de documentID]

**El vínculo público para el documento lleva a una página en blanco**

*Documentos*

Cuando un usuario intenta abrir un documento mediante un vínculo público, el vínculo lleva a una página en blanco. Esto ocurre cuando el vínculo se abre en una ventana en la que una sesión activa de [!DNL Workfront] está abierta.

**Los controles de lista no funcionan en los informes de los paneles**

*Paneles*

Cuando un usuario está viendo un informe en un panel e intenta cambiar el filtro, la agrupación o la vista del informe, el filtro, la agrupación o la vista no cambian.

**Error de “[!UICONTROL Debe ser administrador del sistema]” al crear un proyecto**

*Proyectos*

Cuando un usuario que no es administrador intenta crear un proyecto y adjunta un formulario personalizado que tiene una sección disponible solo para los administradores, no puede crear el proyecto y verá el siguiente error:

“[!UICONTROL Debe ser administrador del sistema para cambiar este valor de parámetro de datos personalizado]”

**Los datos personalizados no se conservan al convertir un problema en un proyecto**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, los datos de un formulario personalizado sobre el problema no se transfieren al formulario personalizado comparable del proyecto. Esto sucede con los datos de campos personalizados que pueden estar ocultos en función de los valores de otros campos personalizados.

**Error al convertir el problema al proyecto**

*Proyectos*

Cuando un usuario intenta convertir un problema en un proyecto, el problema no se convierte y ve el siguiente error:

“[!UICONTROL Se produjo un error inesperado]”

+++


## Actualizaciones en enero de 2022

+++**Actualización de mantenimiento del 27 de enero de 2022**

**Los datos personalizados no se conservan al convertir un problema en un proyecto**

*Proyectos*

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, los datos de un formulario personalizado sobre el problema no se transfieren al formulario personalizado comparable del proyecto. Esto sucede con los datos de campos personalizados que pueden estar ocultos en función de los valores de otros campos personalizados.

**La lista de usuarios en el panel ágil no es alfabética**

*Agile*

Cuando un usuario ve la lista de usuarios en un panel ágil, los usuarios no se muestran en orden alfabético. En su lugar, se muestran primero los usuarios con la mayor cantidad de asignaciones.

**Vínculos actualizados para copiar y mover problemas**

*Problemas*

En el entorno de vista previa, los vínculos para copiar y mover problemas se han actualizado a “[!UICONTROL Copiar en]” y “[!UICONTROL Mover a]” tanto en la página de problemas como en una lista de problemas.

**Añada hasta 45 direcciones IP a su lista de permitidos de [!DNL Workfront]**

*Configurar*

El límite de direcciones IP agregadas a su lista de permitidos de [!DNL Workfront] ha aumentado de 30 a 45.

+++

+++**Actualización de mantenimiento del 20 de enero de 2022**

**Error de “[!UICONTROL Parámetro no válido]” al crear el proyecto a partir de la plantilla**

*Proyectos*

Cuando un usuario intenta crear un proyecto a partir de una plantilla y quita un formulario personalizado de la plantilla al crear el proyecto, el proyecto no se crea y el usuario ve un “[!UICONTROL Parámetro no válido]” mensaje de error que menciona un campo obligatorio en el formulario personalizado eliminado.

**La lista de usuarios no se carga en el [!DNL Safari] explorador**

*Usuarios*

Cuando un usuario va al área de [!UICONTROL Usuarios], aparece el encabezado pero la lista de usuarios no se carga.

**El retraso al arrastrar tareas en una lista hace que la tarea se mueva a una ubicación incorrecta**

*Listas*

Cuando un usuario intenta mover una tarea a una lista arrastrándola, la línea azul que indica a dónde se moverá la tarea se mueve mucho más lentamente que el cursor. Cuando el usuario libera la tarea, esta se mueve a donde está la línea azul, incluso si el cursor señala a una ubicación diferente en la lista.

+++

+++**[!DNL Workfront Fusion]Actualización de mantenimiento el 14 de enero de 2022**

**Algunos campos asignados se restablecen al seleccionar un [!UICONTROL nuevo campo para asignar]**

*[!DNL Workfront Fusion]*

Cuando al menos un campo de los módulos de [!DNL Workfront] [!UICONTROL Crear] o [!UICONTROL Actualizar] tienen habilitada la asignación y un usuario selecciona un nuevo campo para asignar, los campos asignados anteriormente que están habilitados para la asignación pierden valores de asignación.

+++

+++**Actualización de mantenimiento del 13 de enero de 2022**

**No se puede agregar un hipervínculo a un comentario en el panel Resumen**

*Tareas*

Cuando un usuario realiza un comentario en el panel de resumen de una tarea e intenta agregar un hipervínculo al comentario, la ventana de hipervínculo se abre, pero en cuanto el usuario hace clic en la ventana, se cierra y el usuario no puede agregar un hipervínculo. Si un usuario se desplaza por la ventana, puede escribir o pegar un vínculo en el campo, pero el hipervínculo no se guarda. En ambos casos, la tarea deja de estar seleccionada.

**La página Editar equipo no se cierra**

*Equipos*

Cuando un usuario intenta editar un equipo, la página [!DNL Edit team] no se cierra. El usuario no puede cerrar la página haciendo clic en ninguno de los botones, haciendo clic en la X ni saliendo de la página.

**Las notificaciones por correo electrónico y en la aplicación no se envían**

*Notificaciones*

Cuando se produce un evento que debería generar una notificación, esta no se envía. Esto puede ocurrir en el caso de las notificaciones por correo electrónico o en la aplicación, y puede ocurrir aunque se envíen otras notificaciones.

**[!UICONTROL La lista Mi trabajo] aparece vacía**

*[!UICONTROL Mi trabajo]*

Cuando un usuario ve su lista [!UICONTROL Mi trabajo] y la plantilla de diseño para su lista [!UICONTROL Mi trabajo] incluye un valor numérico como [!UICONTROL Porcentaje completado], la lista [!UICONTROL Mi trabajo] no se muestra.

**[!UICONTROL Porcentaje completado] y [!UICONTROL Horas de finalización] no se puede modificar en el panel de Agile**

*Agile*

Cuando el usuario selecciona “[!UICONTROL Mostrar más elementos de trabajo]” en el panel de Agile y, posteriormente, intenta cambiar el [!UICONTROL Porcentaje completado] o [!UICONTROL Horas de finalización] en uno de los elementos de trabajo recién cargados, no pueden cambiar el porcentaje completado o la hora de finalización. El botón [!UICONTROL Porcentaje completado] también está en gris, lo que indica que está inactivo.

+++

+++**Actualización de mantenimiento del 6 de enero de 2022**

**Error de “[!UICONTROL Parámetro no válido]” al adjuntar plantillas o formularios personalizados a proyectos**

*Proyectos*

Cuando un usuario intenta adjuntar un formulario personalizado o una plantilla a un proyecto existente, rellena los campos obligatorios en el formulario o plantilla personalizados y guarda los cambios en el proyecto, los cambios no se guardan y el usuario ve un error de “[!UICONTROL Parámetro no válido]” en la parte superior de la página de detalles del proyecto.

**Los comentarios de prueba no se muestran en las actualizaciones de documentos**

*Pruebas*

Cuando un usuario ve una prueba en el área de [!UICONTROL Documentos], los comentarios realizados en la prueba no se muestran en el área de [!UICONTROL actualizaciones] del documento.

**[!UICONTROL Distribuidor de cargas de trabajo]: “[!UICONTROL ?[objeto Objeto]?]” aparece en la información de sobreasignación**

*[!UICONTROL Distribuidor de cargas de trabajo]*

Si un usuario se muestra como sobreasignado en el [!UICONTROL Distribuidor de cargas de trabajo] debido a que una tarea se superpone con el tiempo de espera del usuario y otro usuario ve su sobreasignación, el área de “[!UICONTROL Capacidad]” de la información de sobreasignación muestra “[!UICONTROL ?[objeto Objeto]?]” en lugar de la capacidad real del usuario.

+++

## Actualizaciones de mantenimiento anteriores

La información sobre actualizaciones de mantenimiento anteriores está disponible aquí:

* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront]- 2021](2021-updates.md)
