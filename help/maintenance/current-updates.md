---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '7226'
ht-degree: 99%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2023 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado el problema enviado por usted.

Para ver las actualizaciones de mantenimiento anteriores a 2023, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones en noviembre de 2023

+++**Actualización de mantenimiento del 30 de noviembre de 2023**

**Las tareas no aparecen en [!UICONTROL Mi trabajo] widget**

_[!UICONTROL Inicio]_

Cuando un usuario ve su widget [!UICONTROL Mi trabajo] en [!UICONTROL Inicio], algunas de las tareas que tiene asignadas no se muestran en el widget. Por ejemplo, un usuario puede acceder a un proyecto y ver que tiene tareas asignadas, pero estas tareas no aparecen en el widget [!UICONTROL Mi trabajo ] del usuario.

**La página de inicio de sesión redirige a la página de aterrizaje de cierre**

_Inicio de sesión_

Cuando un usuario intenta iniciar la sesión en [!DNL Workfront], en lugar de la página de inicio de sesión, se le dirige a la página en la que aterrizaría si cerrara la sesión.

**Error 500 al exportar un informe**

_Informes_

Cuando un usuario intenta exportar un informe, la exportación falla con el siguiente error:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Se ha informado de este problema en informes que utilizan un `valueexpression` para hacer referencia a la nota de texto `lastNote`.

+++

+++**Actualización de mantenimiento del 16 de noviembre de 2023**

**Informes: las horas presupuestadas en el informe de utilización no coinciden con las horas presupuestadas notificadas a través de la API**

_Informes_

Cuando un usuario realiza una llamada de API al objeto RPBGHR para un proyecto determinado y compara los resultados de esa llamada con el informe de utilización de dicho proyecto, los resultados no coinciden.

**Solicitudes: se muestra una moneda personalizada incorrecta en la página Nueva solicitud**

_Solicitudes_

Cuando un usuario envía una solicitud y realiza una selección que cambia la lógica de visualización en el formulario de solicitud, la moneda mostrada vuelve a la moneda predeterminada en lugar de la personalizada que se establece en el proyecto que representa la cola de solicitudes.

Cuando el usuario envía su solicitud, la moneda se muestra como la moneda personalizada correcta para el proyecto que representa la cola de solicitudes

**Líneas adicionales en los comentarios realizados a través de la API o[!DNL Workfront Fusion]**

_Actualizaciones_

Cuando un usuario envía un comentario a través de la API o de [!DNL Workfront Fusion], el comentario que aparece en el área de Actualizaciones muestra líneas adicionales. A veces hay tantas líneas que el usuario debe desplazarse hacia abajo para ver el comentario.

Se ha informado de este problema en la nueva experiencia de comentarios.

+++

+++**Actualización de mantenimiento del 9 de noviembre de 2023**

**Al widget Mi trabajo le faltan objetos cuando no está en la parte superior de la página**

_Inicio_

Si el widget Mi trabajo se encuentra en la parte superior de la nueva página de inicio, extrae todos los objetos esperados. Sin embargo, si este widget está por debajo de cualquier otro widget de la página, solo extrae 10 objetos.

**No se puede generar la prueba**

_Pruebas_

Cuando un usuario intenta crear una prueba, esta no se crea y aparece el siguiente mensaje de error:

&quot;[!UICONTROL Error al generar la revisión]&quot;

Esto ocurre cuando la configuración del nivel de acceso del usuario[!UICONTROL Ver información de contacto] se establece en Deshabilitado.

**Solicitudes: los campos se borran cuando se añade un documento a una solicitud**

_Solicitudes_

Cuando un usuario está creando una solicitud, rellena los campos de un formulario y, a continuación, añade o quita un documento, algunos campos del formulario se vacían de datos y el usuario debe rellenarlos de nuevo antes de enviar la solicitud.

**Plantillas de horas: la tarea personal aparece en la plantilla de horas**

_Plantillas de horas_

Cuando un usuario crea una tarea en el widget [!UICONTROL Todo] de la nueva experiencia de [!UICONTROL Inicio], dicha tarea aparece en la plantilla de horas del usuario. Esto ocurre incluso si la tarea no tiene horas registradas y el proyecto personal no está anclado.

+++

+++**Actualización de mantenimiento de (Hot Fix) el 3 de noviembre de 2023**

**Las tareas secundarias aparecen desordenadas cuando se mueven debajo de la tarea principal**

_Plantillas_

Cuando un usuario crea tareas en una plantilla y, a continuación, mueve esas tareas debajo de una tarea principal, los números asignados a las tareas secundarias no aparecen en el orden previsto. Por lo tanto, cuando se actualiza la página, las tareas secundarias se ordenan por números de tareas inesperados y, como resultado, las tareas secundarias aparecen desordenadas.

+++

+++**Actualización de mantenimiento del 2 de noviembre de 2023**

**Las actualizaciones privadas se muestran en los campos de expresión de valor**

_Informes_

Cuando un campo de un informe incluye una expresión de valor que hace referencia a una actualización privada, los usuarios que no están incluidos en la actualización privada pueden verlo en el informe.

**El usuario se muestra con un exceso de asignaciones debido a una capacidad inexacta**

_Distribuidor de cargas de trabajo_

Un usuario puede mostrarse en el Distribuidor de cargas de trabajo con exceso de asignaciones. Si un usuario pasa el ratón sobre la sobreasignación, verá que la capacidad del usuario está configurada en 0.

Si el usuario cambia el intervalo de fechas, la asignación es precisa. Sin embargo, si el usuario actualiza la página, la capacidad puede volver a ser inexacta.

+++

## Actualizaciones en octubre de 2023

+++**Actualización de mantenimiento del 26 de octubre de 2023**

**La búsqueda no funciona**

_Tableros_

Cuando un usuario intenta buscar en los tableros, la búsqueda no devuelve todas las tarjetas que cumplen los criterios de búsqueda.

**No se puede ver la prueba interactiva en el visualizador web**

_Pruebas_

Cuando un usuario intenta ver una prueba en el visualizador de pruebas web, la prueba no se muestra y el usuario ve el siguiente error:

&quot;[!UICONTROL Falta el parámetro de consulta Key-Pair-Id o el valor de la cookie]&quot;

**No se puede crear una nueva versión de una prueba**

_Pruebas_

Cuando un usuario intenta crear una nueva versión de una prueba, la nueva versión no se crea y el usuario ve el siguiente mensaje de error:

&quot;[!UICONTROL Error al generar la revisión]&quot;

**El usuario está duplicado al compartir una solicitud**

_Solicitudes_

Al compartir una solicitud, si se modifica el nivel de acceso de un usuario con el que se comparte la solicitud, el usuario que se encuentra justo encima de este en la lista se convierte en dicho usuario.

Por ejemplo, si la solicitud se comparte con el usuario A y el B y se modifica el acceso del usuario B, el usuario A cambia al B y ahora hay dos usuarios B en la lista. Además, solo se ha modificado el acceso del usuario B principal.

**Error &quot;[!UICONTROL ¡Uy!]&quot; en el encabezado de la tarea**

_Tareas_

Cuando un usuario ve una tarea, su encabezado no contiene información. En su lugar, el usuario ve el siguiente mensaje de error:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo]”.

+++

+++**Actualización de mantenimiento del 19 de octubre de 2023**

A los usuarios no se les notifican las respuestas en un hilo de comentarios

_Notificaciones_

Cuando un usuario responde a un comentario, los demás usuarios que deberían recibir notificaciones para la respuesta no las reciben. Es posible que algunos usuarios reciban la notificación, mientras que otros no.

**Prueba: comentario adicional en blanco al realizar un comentario sobre una prueba**

_Pruebas_

Cuando un usuario hace un comentario sobre una prueba, esta también produce otro comentario en blanco.

Se ha informado de este problema en pruebas de vídeo.

La pestaña **[!UICONTROL Actividad de la prueba] no se abre**

_Pruebas_

Cuando un usuario está viendo una prueba y hace clic en la pestaña [!UICONTROL Actividad de la prueba], se muestran los [!UICONTROL Detalles de la prueba].

Las **[!UICONTROL horas planificadas] se reasignan cuando se asigna un usuario adicional a una tarea**

_Tareas_

Cuando se asigna a un usuario una tarea que tiene [!UICONTROL horas planificadas] asignadas a otras personas asignadas a la tarea, las [!UICONTROL horas planificadas] de la tarea se distribuyen equitativamente a todas las personas asignadas a la tarea.

**&quot;[!UICONTROL Eliminado]&quot; se muestra como nombre de usuario en las actualizaciones del sistema cuando el problema se convierte en tarea**

_Actualizaciones_

Cuando un usuario que ha iniciado sesión como otro usuario convierte un problema en una tarea, y el problema se asigna a un equipo, las actualizaciones del sistema muestran “[!UICONTROL Eliminado]” como el usuario que solicitó que el equipo trabajara en la tarea.

+++

+++**Actualización de mantenimiento del 12 de octubre de 2023**

**Secuencias de trabajo eliminados para las cuentas que no se utilizan**

_Tableros_

En el caso de las cuentas que nunca han creado una secuencia de trabajo en la aplicación Tableros, el área Secuencias de trabajo se ha eliminado del panel Tableros. Las cuentas que sí utilizan secuencias de trabajo siguen teniendo acceso a ellas.

**Los campos calculados no conservan el valor cuando el problema se convierte en tarea**

_Formularios personalizados_

Los campos calculados que hacen referencia a sí mismos no conservan sus valores cuando un problema se convierte en una tarea.

Cuando se convierte el problema en una tarea, el valor deseado se muestra correctamente en la ventana de edición. Sin embargo, una vez completada la conversión, el campo calculado muestra “N/d”.

**Error al cambiar los filtros en [!UICONTROL Inicio]**

_Inicio_

Cuando un usuario cambia los filtros en [!UICONTROL Inicio], el área [!UICONTROL Inicio] no se carga y aparece el siguiente error:

“[!UICONTROL Se produjo un error y se está tratando de resolver el problema. Para continuar trabajando, intente actualizar esta página de explorador.]”

+++

+++**Actualización de mantenimiento del 5 de octubre de 2023**

**El tablero se carga lentamente**

_Tableros_

Cuando un usuario carga un tablero, este se carga muy lentamente. Esto puede ocurrir aunque el tablero tenga un número pequeño de tarjetas.

Las tarjetas archivadas, incluso si no se muestran, afectaban al tiempo de carga del tablero.

**No se pueden mover tarjetas entre columnas**

_Tableros_

Cuando un usuario intenta mover una tarjeta en un tablero, la tarjeta no se mueve. Esto ocurre en las siguientes circunstancias:

* Arrastrar y soltar
* Opción Mover en la tarjeta
* Edición de la tarjeta

**No se pueden mover las tarjetas fuera de la columna de entrada**

_Tableros_

El usuario puede arrastrar una tarjeta de la columna de entrada a otra columna del tablero, pero las tarjetas posteriores no se pueden mover fuera de la columna de entrada.

**Agrupar por afecta al rendimiento del tablero**

_Tableros_

Cuando el usuario intenta agrupar las tarjetas por usuarios asignados o etiquetas, el rendimiento del tablero se vuelve muy lento.

**No se envían los correos electrónicos de recordatorio automático**

_Notificaciones_

Los recordatorios automáticos por correo electrónico no se envían. Esto comenzó el 14 de septiembre de 2023.

+++

## Actualizaciones en septiembre de 2023

+++**Actualización de mantenimiento del 28 de septiembre de 2023**

**No se puede eliminar el campo personalizado**

_Formularios personalizados_

Cuando un usuario intenta eliminar un campo personalizado, no puede eliminarlo y ve el mensaje “[!UICONTROL Error de base de datos debido a infracción de restricción]”.

**Los comentarios realizados en la nueva experiencia de comentarios no son visibles en la heredada**

_Actualizaciones_

Cuando un usuario hace un comentario en la nueva experiencia y este aparece en el área de Comentarios de la nueva experiencia, es posible que este no aparezca en la experiencia de comentario heredada. Esto puede ocasionar que los usuarios que utilicen la experiencia heredada no reciban comentarios.

**Faltan elementos en la página de objeto**

_Workfront_

Cuando un usuario navega a una sección personalizada en un objeto en [!DNL Workfront], es posible que a la página que se carga le falten algunos elementos. Estos elementos pueden incluir los siguientes:

* El panel de navegación izquierdo
* El nombre del objeto al que pertenece la sección personalizada
* Campos e información en el encabezado

+++

+++**Actualización de mantenimiento del 21 de septiembre de 2023**

**No se puede asignar un usuario en un tablero de una secuencia de trabajo**

_Tableros_

Cuando un usuario intenta asignar a otro usuario una tarea de un tablero que forma parte de una secuencia de trabajo y empieza a escribir el nombre del usuario, este no aparece en la lista desplegable de usuarios disponibles. Esto ocurre incluso cuando el usuario está activo y es miembro tanto del tablero como de la secuencia de trabajo.

También puede observar que los usuarios desactivados aparecen en la lista desplegable.

**No se puede eliminar el elemento de lista de comprobación**

_Tableros_

Cuando un usuario intenta eliminar un elemento de la lista de comprobación de una tarjeta de un tablero, el botón [!UICONTROL Eliminar] no responde y el elemento no se elimina.

**Los formularios personalizados se cargan lentamente**

_Formularios personalizados_

Cuando un usuario intenta cargar un formulario personalizado, este se carga lentamente.

**No se puede mover el documento a otra carpeta**

_Documentos_

Cuando un usuario mueve un documento a una carpeta de objetos, no puede mover el objeto a otra carpeta.

**Error de XML al descargar**

_Documentos_

Cuando se intenta descargar un documento, este no se descarga y aparece una página con el siguiente mensaje de texto XML.

“[!UICONTROL Parece ser que el archivo XML no tiene asociada ninguna información de estilo. El árbol de documentos se encuentra a continuación]”.

**No se pueden descargar documentos de entornos de previsualización o de zona protegida**

_Documentos_

Cuando un usuario intenta descargar un documento de un entorno que no sea de producción, el documento no se descarga y el usuario ve el siguiente error:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo]”.

**Las pruebas aparecen desaturadas o recortadas**

_Pruebas_

Se han notificado los siguientes problemas al crear una prueba a partir de una dirección URL.

* La prueba aparece desaturada o descolorida.
* La prueba se ha recortado.

Esto puede dificultar las decisiones sobre la prueba, ya que esta no se representa con exactitud.

**Las pruebas tardan demasiado en generarse**

_Pruebas_

Cuando un usuario intenta generar una prueba, esta tarda demasiado. La generación de pruebas puede tardar varios días.

+++

+++**Actualización de mantenimiento del 14 de septiembre de 2023**

Error **“[!UICONTROL No hay fábrica]” al añadir un documento**

_Documentos_

Cuando un usuario intenta añadir un documento desde un origen externo, [!DNL Workfront] no puede acceder al origen y aparece el siguiente error:

“[!UICONTROL Se ha producido el siguiente error: No se ha encontrado ninguna fábrica para el tipo de autenticación nulo]”

**Error “¡Uy!”, en los informes de matriz**

_Informes_

Cuando un usuario intenta abrir una informe de matriz, el informe no se carga y el usuario ve el siguiente mensaje de error:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo]”.

Esto ocurre al agrupar un informe por intervalos de fechas.

+++

+++**Actualización de mantenimiento del 11 de septiembre de 2023**

**Las tareas personales no se muestran en las plantillas de horas**

_Plantillas de horas_

Las tareas personales ya no se muestran en la plantilla de horas de forma predeterminada. Las tareas personales se muestran en la plantilla de horas cuando están ancladas o cuando se han registrado horas. Antes de este cambio, las tareas personales se mostraban en las plantillas de horas de forma predeterminada.

+++

+++**Actualización de mantenimiento del 7 de septiembre de 2023**

**El proyecto está en blanco cuando se carga desde la nueva experiencia de [!UICONTROL Inicio]**

_Proyectos_

Cuando un usuario hace clic en un proyecto desde su página de [!UICONTROL Inicio] en la nueva experiencia de Inicio, la página del proyecto no se puede cargar.

Esto ocurre cuando el usuario ha iniciado sesión y ha cerrado la sesión como otro usuario y ha vuelto a su propia página de [!UICONTROL Inicio].

+++

## Actualizaciones de agosto de 2023

+++**Actualización de mantenimiento del 31 de agosto de 2023**

**Los filtros no se aplican a los widgets en la nueva experiencia de [!UICONTROL Inicio]**

_[!UICONTROL Inicio]_

Cuando se aplica un filtro a un widget en la nueva experiencia de [!UICONTROL Inicio], el widget muestra los elementos que el filtro debería haber excluido.

Se ha informado de este problema en el entorno de zona protegida personalizada. Los mismos widgets en los entornos de vista previa y producción filtran como estaba previsto.

**Informes: problemas al cargar informes de matriz**

_Informes_

Cuando un usuario intenta cargar un informe de matriz como gráfico, puede producirse una de las siguientes situaciones:

* Parte de la información del informe no se carga
* El informe muestra el error “[!UICONTROL No se puede cargar contenido del servidor]”

**Planificador de recursos: el planificador no se carga cuando se aplica el filtro**

_[!UICONTROL Planificador de recursos]_

Cuando se intenta cargar el [!UICONTROL Planificador de recursos], no se carga y aparece el siguiente mensaje de error:

“[!UICONTROL Se produjo el siguiente error: Error al conectar con el servicio WorkPerDay]”

+++

+++**Actualización de mantenimiento del 24 de agosto de 2023**

**No se puede seleccionar texto en listas o viñetas**

_Pruebas_

Cuando se ve una prueba en el visualizador de revisión y se intenta seleccionar texto que está en una lista o viñeta, la herramienta de selección de texto no funciona y el texto no se puede seleccionar.

**Al crear una nueva versión de prueba, se eliminan todas las versiones de prueba**

_Pruebas_

Cuando un usuario crea una prueba a partir de un documento, se crea la prueba. Sin embargo, si el usuario crea otra versión de la prueba, se eliminan tanto la versión antigua como la nueva. Hay una opción [!UICONTROL Crear prueba] en el documento original, y las versiones de prueba se pueden encontrar en el área [!UICONTROL Papelera] del área [!UICONTROL Revisión] en [!DNL Workfront].

+++

+++**Actualización de mantenimiento del 17 de agosto de 2023**

**No se puede navegar al proyecto con una URL que utilice un [!UICONTROL ID de referencia]**

_Proyectos_

Cuando un usuario intenta navegar a un proyecto mediante una dirección URL que incluya un número [!UICONTROL ID de referencia], se le redirigirá a una página con un mensaje de error. La navegación a una tarea mediante una URL con un [!UICONTROL ID de referencia] funciona según lo esperado.

**La configuración “[!UICONTROL Deshabilitar notificaciones de correo electrónico de prueba]” se muestra de forma inexacta**

_Pruebas_

Cuando un usuario está viendo la configuración de prueba en [!DNL Workfront], la casilla de verificación “[!UICONTROL Deshabilitar notificaciones de correo electrónico de prueba]” no muestra con precisión la configuración actual correcta. Cuando se marca la casilla, lo que indica que las notificaciones de prueba por correo electrónico están desactivadas, las notificaciones están activadas. Lo contrario también es cierto.

**No se pueden ajustar las marcas de la prueba**

_Pruebas_

Cuando el usuario hace un comentario en el visualizador de revisión, realiza una marca en la prueba y luego hace clic fuera, el usuario ya no puede ajustar la marca.

+++

+++**Actualización de mantenimiento del 10 de agosto de 2023**

**No se pueden eliminar elementos de [!UICONTROL Tareas pendientes] en la nueva experiencia de [!UICONTROL Inicio]**

_Inicio_

Cuando el usuario intenta eliminar un elemento del widget [!UICONTROL Tareas pendientes] en la nueva experiencia de [!UICONTROL Inicio], no se elimina y aparece el siguiente error:

“[!UICONTROL Hubo un problema al eliminar su tarea, inténtelo de nuevo.]”

Esto puede ocurrir cuando hay horas registradas en el elemento de [!UICONTROL Tareas pendientes].

**El proyecto anclado no muestra información en algunas columnas**

_Proyectos_

Cuando el usuario navega a un proyecto anclado utilizando el pin, las listas de objetos (como la lista de tareas) pueden mostrar columnas en blanco. Por ejemplo, una columna [!UICONTROL Asignaciones] puede que no muestre ninguna asignación, aunque se hayan realizado.

**El módulo Suspensión hace que se cuelguen los escenarios**

_[!DNL Workfront Fusion]_

El módulo [!UICONTROL Herramientas] > [!UICONTROL Suspensión] en un escenario puede hacer que se cuelgue la ejecución de un escenario. Estas ejecuciones muestran el estado En ejecución en el [!UICONTROL Historial del escenario] y no finalizan.

+++

+++**Actualización de mantenimiento del 3 de agosto de 2023**

**Dificultad para localizar elementos en la columna de entrada**

_Tableros_

La columna de entrada de un tablero se ordenaba anteriormente por la prioridad definida en las tareas y problemas, lo que dificultaba la localización de elementos específicos.

El orden predeterminado ahora es el siguiente:

Tareas:

* Orden principal: nombre del proyecto
* Orden secundario: estructura del desglose de trabajo

Problemas

* Orden principal: nombre del proyecto
* Orden secundario: número de referencia

**El proyecto no resuelve el problema correctamente**

_Proyectos/problemas_

Cuando se cambia el estado de un proyecto que es el objeto de resolución de un problema, el estado del problema se cambia a un estado que no coincide con la misma clave que el estado del proyecto.

**Error “¡Uy!”, en los informes de matriz**

_Informes_

Cuando un usuario intenta abrir una informe de matriz, el informe no se carga y el usuario ve el siguiente mensaje de error:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo]”.

Se ha informado de este problema a los usuarios de EMEA.

+++

## Actualizaciones en julio de 2023

+++**Actualización de mantenimiento del 27 de julio de 2023**

**Las etiquetas y los elementos de la lista de comprobación no funcionan correctamente en la vista del tablero del proyecto**

_Tableros_

Las etiquetas y los elementos de la lista de comprobación se han eliminado de la vista del tablero de los proyectos, ya que no forman parte de las tareas de Workfront y no se pueden compartir entre los usuarios.

**“[!UICONTROL Habilitar en todo el sistema]” y “[!UICONTROL Ver en todo el sistema]” representan funcionalidades diferentes**

_Filtros_

Si un usuario comparte un filtro y habilita la opción “[!UICONTROL Ver en todo el sistema]”, lo comparte con cada usuario del sistema. Sin embargo, cuando un administrador ve este filtro en [!UICONTROL Configuración], muestra “[!UICONTROL falso]” en la columna “[!UICONTROL Visible en todo el sistema]”. Para que este filtro sea predeterminado del sistema, el administrador debe habilitar la opción “[!UICONTROL Habilitar en todo el sistema]” en [!UICONTROL Configuración]. Esto puede causar cierta confusión debido a la similitud de la redacción.

+++

+++**Actualización de mantenimiento del 20 de julio de 2023**

Esta actualización contiene solo correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

+++

+++**Actualización de mantenimiento del 13 de julio de 2023**

**La cronología no se recalcula**

_Proyectos/tareas/problemas_

Cuando se produce un evento que debería activar un cálculo de la cronología, esta no se recalcula. Esto afecta a los nuevos cálculos que se producen en los cambios y a los recalculaciones programadas. Esto puede repercutir en la precisión del Distribuidor de cargas de trabajo.

**Las aprobaciones de prueba bloqueadas siguen apareciendo en la lista de trabajo**

_Pruebas_

Las aprobaciones de pruebas que han pasado la fecha límite y están bloqueadas siguen apareciendo en la lista de trabajo en el Inicio del aprobador, en lugar de desaparecer.

**El informe de utilización no se carga**

_Informes_

Cuando un cliente intenta ver un informe de utilización, el usuario ve un indicador de carga giratorio, pero el informe no se carga. El informe ha devuelto un error 500, pero el usuario no ve ninguna indicación de que haya fallado.

**La página Editar usuario está en blanco**

<!--no article-->

_Usuarios_

Cuando se intenta editar otro usuario o usuaria, la página Editar usuario se queda en blanco y no se puede editar ese usuario o usuaria.

+++

## Actualizaciones en junio de 2023

+++**Actualización de mantenimiento del 29 de junio de 2023**

Esta actualización contiene solo correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

+++

+++**Actualización de mantenimiento del 22 de junio de 2023**

**Error “[!UICONTROL ¡Uy!]” al ver el informe de matriz**

_Informes_

Cuando un usuario ve un informe de matriz, ve el siguiente error:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo]”.

Esto se ha notificado cuando el informe se ordena por fecha y la opción “[!UICONTROL Mostrar semanas sin resultados]” está activada.

**Las fechas no se muestran correctamente en los informes de matriz**

_Informes_

Cuando un gráfico o informe de matriz se agrupa por fecha, las fechas cerca de los bordes de la agrupación pueden aparecer en la agrupación correcta, en la agrupación anterior o siguiente, o en ambas.

+++

+++**Actualización de mantenimiento del 15 de junio de 2023**

Esta actualización contiene solo correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

+++

+++**Actualización de mantenimiento del 8 de junio de 2023**

Esta actualización contiene solo correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento del 8 de junio de 2023**

[!DNL Fusion] ha implementado una corrección que impide que se eliminen las conexiones de un usuario cuando este se elimina o desactiva en la [!UICONTROL Adobe Admin Console].

Los administradores de equipo de [!DNL Fusion] siguen pudiendo quitar conexiones innecesarias de la página [!UICONTROL Conexiones] en [!DNL Fusion].

+++

+++**Actualización de mantenimiento del 1 de junio de 2023**

**No hay ningún mensaje de error al reordenar la tarea en el estado [!UICONTROL Pendiente de aprobación]**

_Tareas_

Cuando un usuario intenta reordenar una tarea en una lista de tareas y la tarea se encuentra en [!UICONTROL Pendiente de aprobación], la tarea parece moverse en la lista de tareas. Cuando se actualiza, el usuario ve que el elemento no se ha movido. El elemento no se puede mover porque está en estado [!UICONTROL Pendiente de aprobación], pero no hay ningún mensaje que indique al usuario que el elemento no se puede mover, lo que puede provocar confusión.

**No hay ningún mensaje de error al mover la tarea predecesora a una tarea dependiente**

_Tareas_

Cuando un usuario intenta reordenar una tarea en una lista de tareas y la tarea se encuentra en [!UICONTROL Pendiente de aprobación], la tarea parece moverse en la lista de tareas. Cuando se actualiza, el usuario ve que el elemento no se ha movido. El elemento no se puede mover porque una tarea predecesora no se puede mover a una tarea de la que es predecesora, pero no hay ningún mensaje que indique al usuario que el elemento no se puede mover, lo que puede llevar a confusión.

+++

## Actualizaciones en mayo de 2023

+++**Actualización de mantenimiento del 25 de mayo de 2023**

El tablero **[!UICONTROL Kanban] se queda en blanco al editar tarjetas**

_Agile_

Cuando un usuario cambia algo acerca de una tarjeta en el tablero [!UICONTROL Kanban], el tablero [!UICONTROL Kanban] se queda en blanco en lugar de actualizarse con el cambio. Si el usuario actualiza la página manualmente, el tablero [!UICONTROL Kanban] vuelve y muestra el cambio correcto.

Se ha informado de esto en las siguientes circunstancias:

* Edición de una tarjeta
* Mover una tarjeta


+++

+++**Actualización de mantenimiento del 22 de mayo de 2023**

**No se puede ajustar el tamaño del texto descriptivo**

_Formularios personalizados_

Cuando se lanzó el diseñador de formularios personalizado en la versión beta, la funcionalidad para ajustar el tamaño del texto descriptivo no estaba disponible. Este problema se ha corregido y los usuarios ahora pueden ajustar el tamaño del texto descriptivo.

+++

+++**Actualización de mantenimiento del 18 de mayo de 2023**

**El informe no se ordena correctamente al ordenar por campo personalizado**

_Informes_
Cuando un usuario ejecuta un informe de tareas, este parece ordenarse correctamente cuando se está cargando, pero cuando termina se ve que no está bien ordenado.

Esto parece ocurrir si se cumplen todas las siguientes circunstancias:

* El informe es uno de tareas
* El informe se ordena por un campo personalizado
* El informe tiene una agrupación aplicada

+++

+++**Actualización de mantenimiento del 11 de mayo de 2023**

**No se puede cambiar de versión de prueba al ver la prueba**

_Pruebas_

Cuando se está viendo una prueba en el [!UICONTROL visualizador de revisión] y se cambia a otra versión, el desplegable de la versión se desactiva y no se puede volver a la versión original que se estaba viendo ni a otra versión de la prueba.

**[!DNL Workfront]Búsqueda agotada**

_Búsqueda_

La búsqueda de [!DNL Workfront] está agotando el tiempo de espera. La búsqueda puede arrojar algunos resultados, o ninguno.

Este problema también afecta a la funcionalidad del [!DNL Workfront Fusion] > [!DNL Workfront] > módulo de [!UICONTROL búsqueda].

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento del 11 de mayo de 2023**

**Errores de tiempo de espera en[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Cuando se está ejecutando un escenario, puede producirse un error de tiempo de espera. La información del módulo con el error no llega a su destino.

**[!DNL Workfront]Búsqueda agotada**

_Búsqueda_

La búsqueda de [!DNL Workfront] está agotando el tiempo de espera. La búsqueda puede arrojar algunos resultados, o ninguno.

Este problema también afecta a la funcionalidad del [!DNL Workfront Fusion] > [!DNL Workfront] > módulo de [!UICONTROL búsqueda].

+++

+++**Actualización de mantenimiento del 9 de mayo de 2023**

**Filtros guardados disponibles en la columna de entrada del tablero**

_Tableros_

Ahora puede utilizar los filtros de problemas y tareas de Workfront existentes al configurar la columna de entrada para un tablero. Sin embargo, los filtros de columna de entrada existentes son ahora de solo lectura en el panel de configuración. Los filtros existentes se siguen aplicando a la columna de entrada, pero debe volver a crear los filtros si desea editarlos.

+++

+++**Actualización de mantenimiento del 4 de mayo de 2023**

**No se puede seleccionar la plantilla de [!UICONTROL Favoritas]**

_Plantillas_

Cuando un usuario intenta seleccionar una plantilla del menú Acciones (tres puntos), la lista de plantillas desaparece cuando mueve el ratón a la lista y no se puede. Esto se debe a que la barra de desplazamiento está entre el menú y la lista de plantillas, y el ratón se centra en la barra de desplazamiento a medida que se mueve a la lista de plantillas.

+++

## Actualizaciones en abril de 2023

+++**Actualización de mantenimiento del 27 de abril de 2023**

**No se puede cambiar entre pruebas en el [!UICONTROL visualizador de pruebas]**

_Pruebas_

Cuando un usuario está viendo una prueba en el [!UICONTROL Visualizador de pruebas] y cambia a otra, el botón de conmutar pruebas deja de responder. El usuario no puede volver a la prueba original que estaba viendo ni a otra.

**Editar imágenes adjuntas al editar un comentario**

_Actualizaciones_

Ahora puede editar la imagen adjunta a un comentario cuando edita un comentario. Esto está disponible en la sección de Workfront para objetivos y en la de problemas al habilitar la experiencia de comentarios beta.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento del 25 de abril de 2023**

Los vínculos de ayuda en la aplicación de **[!DNL Fusion]no conducen a páginas de ayuda específicas**

_[!DNL Workfront Fusion]_

Cuando un usuario está viendo una prueba en el [!UICONTROL Visualizador de pruebas] y cambia a otra, el botón de conmutar pruebas deja de responder. El usuario no puede volver a la prueba original que estaba viendo ni a otra.

+++

+++**Actualización de mantenimiento del 20 de abril de 2023**

**Problemas en los campos desplegables personalizados**

_Formularios personalizados_

Los campos desplegables personalizados que están habilitados como campos de selección múltiple pueden mostrar los siguientes problemas:

* El botón “+[!UICONTROL Agregar]” no está presente cuando el formulario no está en modo de edición.
* Los campos que no tienen valores muestran una opción “--[!UICONTROL sin etiqueta]--”.

**No se puede usar la herramienta Polyline al comentar una prueba**

_Pruebas_

Cuando se está viendo una prueba en el visualizador de revisión y se intenta realizar un comentario con la herramienta Polyline, esta no marca la prueba.

**El cuadro de opciones de texto muestra “textAnnotations”**

_Pruebas_

Cuando un usuario está viendo una prueba, se comienza a añadir un comentario y se abre la herramienta Texto, la palabra “textAnnotation” aparece junto a las opciones de la herramienta. La herramienta Texto sigue funcionando como se espera y “textAnnotation” desaparece después de publicar el comentario.

**Mantener las imágenes como borrador al alejarse de una actualización para objetivos y problemas en la experiencia de comentarios beta**

>[!NOTE]
>
>Esta función se publicó como previsualización el 19 de abril de 2023 y en producción, el 20 de abril de 2023.

_Actualizaciones_

Ahora, cuando se aleja de la página Actualizaciones mientras está redactando un mensaje en el que ha adjuntado una imagen, el mensaje y la imagen se conservan al volver. Antes de esta actualización, el comentario no enviado se mantenía, pero la imagen se borraba. Esto está disponible en la sección Actualizaciones para objetivos y en la de problemas al habilitar la experiencia de comentarios beta.

**Actualizaciones en tiempo real y comentarios eliminados en la sección Actualizaciones**

>[!NOTE]
>
>Esta función se publicó como previsualización el 19 de abril de 2023 y en producción, el 20 de abril de 2023.

_Actualizaciones_

Ahora, cuando alguien agrega un comentario o responde, o elimina un comentario del área Actualizaciones, puede ver el nuevo comentario o una indicación de que un comentario se ha borrado en tiempo real, sin demoras. Esto está disponible en la sección Actualizaciones para metas y en la de problemas al habilitar la experiencia de comentarios beta.

**Nivel de acceso cambiado por el sistema sin registro del cambio**

_Usuarios_

El sistema puede cambiar impredeciblemente el nivel de acceso de un usuario. Cuando esto sucede, no hay ninguna actualización visible y el cambio no aparece en el registro de auditoría.

+++

+++**Actualización de mantenimiento del 17 de abril de 2023**

**Mostrar nuevos comentarios fuera del área de la pantalla visible en la sección [!UICONTROL Actualizaciones] de problemas (nueva experiencia beta de comentarios) y [!UICONTROL Objetivos]**

_Actualizaciones_

Se ha añadido un banner de notificación en la sección [!UICONTROL Actualizaciones] para informar a los usuarios cuando hay comentarios más recientes sobre un elemento que podría estar fuera del área visible de la pantalla. Esta actualización está disponible actualmente en la sección [!UICONTROL Actualizaciones] de objetivos y en la de problemas cuando se ha habilitado la nueva experiencia beta de comentarios para problemas.

+++

+++**Actualización de mantenimiento del 13 de abril de 2023**

**Los filtros no se aplican a la lista de solicitudes**

_Solicitudes_

Cuando un usuario ve una lista de solicitudes que tiene un filtro aplicado, incluye algunas que se deberían excluir.

**No se puede seleccionar el [!UICONTROL Tipo de hora predeterminado] o los [!UICONTROL Tipos de hora disponibles]**

_Usuarios_

Cuando un administrador está editando un usuario e intenta seleccionar un [!UICONTROL Tipo de hora predeterminado] o [!UICONTROL Tipo de hora disponible], verá que los desplegables de esos campos están deshabilitados y que no puede.

+++

+++**Actualización de mantenimiento del 6 de abril de 2023**

**Los desplegables no se abren cuando se añade a un usuario a una prueba**

_Pruebas_

Cuando un usuario añade a otro usuario a una prueba en el [!UICONTROL Visor de revisión], los menús desplegables de la “[!UICONTROL Función de prueba]” y de las “[!UICONTROL Alertas de correo electrónico]” no se pueden abrir. No se puede asignar una función de prueba o una alerta de correo electrónico. Esto puede ocurrir al añadir a un usuario a través de un comentario o al compartir la prueba con el usuario.

+++

## Actualizaciones en marzo de 2023

+++**Actualización de mantenimiento del 30 de marzo de 2023**

**No se puede cambiar de versión de prueba al ver la prueba**

_Pruebas_

Cuando se está viendo una prueba en el [!UICONTROL visualizador de revisión] y se cambia a otra versión, el desplegable de la versión se desactiva y no se puede volver a la versión original que se estaba viendo ni a otra versión de la prueba.

**Error 504 al exportar los informes**

_Informes_

Cuando se intenta exportar un informe con un número elevado de elementos, aparece un error 504 y no se puede exportar el informe.

**La actualización realizada en nombre de un usuario se muestra directamente como hecha por ese usuario**

_Actualizaciones_

Cuando un rol de administrador ha iniciado sesión como usuario y realiza un comentario, ese comentario se muestra directamente como hecho por el usuario, en lugar de hacerlo como hecho por el rol de administrador en nombre del usuario.

+++

+++**Actualización de mantenimiento del 23 de marzo de 2023**

El contenido del panel **[!UICONTROL Resumen] es demasiado ancho para el panel**

_Documentos_

Cuando se ve el panel [!UICONTROL Resumen] de un documento, el contenido es demasiado ancho para verlo en el panel. El panel ahora tiene una barra de desplazamiento horizontal y hay que desplazarse horizontalmente para ver el contenido del panel [!UICONTROL Resumen]. Esto ocurre porque el nombre de archivo del documento no se ajusta. Este problema se limita al archivo donde el nombre del archivo tiene una extensión de archivo HTML.

**Nueva versión de**[!UICONTROL Desktop Proofing Viewer]

_Revisión_

Para solucionar un problema de comentarios en [!UICONTROL Desktop Proofing Viewer], hemos implementado una nueva versión del visualizador de revisión de escritorio.

Cuando [!UICONTROL Desktop Proofing Viewer] ya está instalado, esta actualización se obtiene automáticamente.

También es posible descargar manualmente la versión más reciente. Para obtener más información, consulte la [[!UICONTROL Instalación de Desktop Proofing Viewer]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html).

* Versión anterior: 2.1.22
* Nueva versión: 2.1.23

+++

+++**Actualización de mantenimiento del 16 de marzo de 2023**

**Elementos de la lista de comprobación no copiados al copiar una tarjeta**

_Tableros_

Al copiar una tarjeta ad hoc (las tarjetas conectadas no se pueden copiar), los elementos de la lista de comprobación no se copian en la nueva tarjeta.

**Falta el campo personalizado cuando el problema se convierte en proyecto**

_Proyectos_

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, un campo personalizado que estaba en el problema no se muestra en el proyecto. Este problema solo afecta a las personas que no son administradores.

**Los mensajes personalizados no aparecen en las notificaciones por correo electrónico**

_Pruebas_

Cuando un usuario comparte una prueba y añade un mensaje personalizado, ese mensaje personalizado no aparece en el correo electrónico de notificación al destinatario. El asunto es el nombre de la revisión y el mensaje no aparece en el correo electrónico.

+++

+++**Actualización de mantenimiento del 9 de marzo de 2023**

**El nivel de acceso no está asignado al reactivar el usuario**

_Usuarios_

Cuando un usuario está reactivando a uno desactivado e intenta asignarle un nivel de acceso en la ventana [!UICONTROL Reactivar usuario], la lista desplegable de nivel de acceso no se rellena a medida que se va escribiendo, y el usuario no puede seleccionar un nivel de acceso. Si el usuario escribe el nivel de acceso y guarda, el nivel de acceso no se asigna al usuario.

**Guarde el borrador de un comentario en el área de [!DNL Goals]**

_[!DNL Workfront Goals]_

Así, si se abandona la página [!UICONTROL Actualizaciones] de una meta mientras se está redactando un mensaje, este se conserva al volver. Antes de esta actualización, el comentario no enviado se habría eliminado.

+++

+++**Actualización de mantenimiento del 2 de marzo de 2023**

**No se pueden agregar tarjetas al aplicar la agrupación**

_Tableros_

Cuando un usuario está viendo un tablero que tiene una agrupación aplicada, e intenta agregar una tarjeta, el usuario solo puede introducir el nombre de la tarjeta. El resto de los campos de tarjeta están desactivados, incluido el botón [!UICONTROL Guardar].

Si el usuario cambia la agrupación a [!UICONTROL Ninguna], el problema continúa. El usuario debe cambiar la agrupación a [!UICONTROL Ninguna] y, a continuación, actualizar la página para restaurar la capacidad de agregar una tarjeta.

**Las tarjetas conectadas no se añaden a las columnas según el estado**

_Tableros_

Aunque las directivas de columna se aplican al estado, las nuevas tarjetas conectadas aparecen en la columna situada más a la izquierda y no en la columna que corresponde a su estado.


**El vínculo a un comentario redirige a la página [!UICONTROL detalles]**

_Actualizaciones_

Cuando un usuario sigue un vínculo a un comentario sobre un objeto en Workfront, el flujo de actualización se carga brevemente y, a continuación, se redirige al usuario al área [!UICONTROL Detalles] del objeto. Esto puede ocurrir si el usuario hace clic en el vínculo de un correo electrónico o pega el vínculo en su explorador.

Actualmente, esto solo afecta a los objetos de tipo Documento.

**Imprimir resumen no se carga**

_[!UICONTROL Revisión de Workfront]_

Cuando un usuario intenta cargar la página Imprimir resumen, la página parece estar cargándose, pero no se carga.

+++

## Actualizaciones en febrero de 2023

+++**Actualización de mantenimiento del 23 de febrero de 2023**

**El vínculo a un comentario redirige a la página [!UICONTROL detalles]**

_Actualizaciones_

Cuando un usuario sigue un vínculo a un comentario sobre un objeto en Workfront, el flujo de actualización se carga brevemente y, a continuación, se redirige al usuario al área [!UICONTROL Detalles] del objeto. Esto puede ocurrir si el usuario hace clic en el vínculo de un correo electrónico o pega el vínculo en su explorador.

Actualmente, esto solo afecta a los objetos de tipo Documento.

**El usuario no puede editar su propia configuración de notificación**

_Usuarios_

Cuando un usuario con una licencia de [!UICONTROL Trabajador] intenta editar su propia configuración de notificación, las opciones de [!UICONTROL Notificaciones] no están visibles en la ventana [!UICONTROL Editar] y el usuario no puede editar la configuración.

+++

+++**Actualización de mantenimiento del 16 de febrero de 2023**

**Múltiples asignaciones de equipo en tableros**

_Tableros_

Ahora puede asignar varios equipos a una tarea o problema de un tablero, así como al tablero en sí.

**Aumento del límite de caída de tarjetas**

_Tableros_

Los límites de tiempo de caída de la tarjeta se han aumentado a 8 semanas / 60 días en lugar de 4 semanas / 30 días.

**La desactivación programada no desactiva el usuario**

_Usuarios_

Cuando se programa la desactivación de un usuario y la fecha y hora programadas pasan, el usuario no se desactiva.

+++

+++**Actualización de mantenimiento del 9 de febrero de 2023**

Se ha agregado el campo **[!UICONTROL Puntos de caso] a los informes y a las listas de tareas y problemas**

_Informes_

El campo [!UICONTROL Puntos de caso] ahora está disponible para agregarlo a las listas e informes para tareas o problemas. Se trata de un campo libre editable que no está vinculado a las horas planificadas ni a las asignaciones de equipo.

+++

+++**Actualización de mantenimiento del 8 de febrero de 2023**

**Botón Filtro en la columna de admisión**

_Tableros_

La columna de admisión de un tablero ahora incluye un botón **[!UICONTROL Agregar un filtro]** cuando la columna está vacía y no se han creado filtros. El botón abre el área de configuración, donde puede agregar filtros para incluir tareas y problemas en la columna de admisión.

+++

+++**Actualización de mantenimiento del 2 de febrero de 2023**

El icono de **[!UICONTROL Tableros] aparece en el [!UICONTROL Menú principal] de forma predeterminada**

_Tableros_

El icono de [!UICONTROL Tableros] ahora aparece en el [!UICONTROL Menú principal] para los usuarios que no tienen una plantilla de diseño. Los tableros también se incluyen en el menú principal de forma predeterminada para cualquier plantilla de diseño nueva que se cree. Las plantillas de diseño existentes no han cambiado.

**No se pueden guardar las plantillas de correo electrónico**

_Configuración_

Cuando un usuario intenta crear o editar una plantilla de correo electrónico, el botón [!UICONTROL Guardar] no responde y el usuario no puede guardar la plantilla.

+++

## Actualizaciones en enero de 2023

+++**Actualización de mantenimiento del 30 de enero de 2023**

**Métodos abreviados de teclado agregados para acciones comunes de las plantillas de horas**

_Plantillas de horas_

Hemos introducido los siguientes métodos abreviados del teclado para las siguientes acciones que se realizan con más frecuencia dentro de una plantilla de horas:

* Agregar fila (Cmd+Opción++ / Ctrl+Opción++)
* Eliminar fila (Cmd+Opción+- / Ctrl+Opción+-)
* Fijar o Liberar un elemento de trabajo (Opción+P / Opción+P)
* Abrir comentario (Mayús+F2 / Mayús+F2)
* Guardar comentario (Cmd+Intro / Ctrl+Intro)
* Expandir (Mayús+Opción+Flecha arriba / Mayús+Alt+Flecha arriba)
* Contraer (Mayús+Opción+Flecha abajo / Mayús+Alt+Flecha abajo)

Para que se apliquen estas acciones, el área en la que se realizan debe estar resaltada.

**Nuevos iconos de información para las plantillas de horas, los perfiles de plantillas de horas y las preferencias de plantillas de horas**

_Plantillas de horas_

>[!NOTE]
>
>Esta actualización se publicó solo en el entorno de vista previa el 3 de noviembre de 2022 y ya está disponible en Producción.

Hemos añadido varios iconos de información a las siguientes opciones de configuración:

* Casilla de verificación “[!UICONTROL Puede editar las horas]” al crear o editar una plantilla de horas o un perfil de plantilla de horas, para indicar que, cuando está activada, los aprobadores también pueden enviar, volver a abrir o editar la plantilla de horas, a menos que el administrador restrinja estas acciones en el área [!UICONTROL Preferencias de plantilla de horas] de [!UICONTROL Configuración].
* “[!UICONTROL Restringir la edición de la plantilla de horas a propietarios y administradores]” en el área [!UICONTROL Preferencias de plantilla de horas y horas] de [!UICONTROL Configuración], para indicar que, cuando está desactivada, los siguientes usuarios también pueden editar las plantillas de horas: usuarios con acceso administrativo a plantillas de horas y horas, aprobadores de plantillas de horas que tienen permiso para editar las horas y administradores de propietarios de plantilla de horas.

Tenga en cuenta que la funcionalidad de estas opciones de configuración no ha cambiado y que solo se han añadido los iconos de información para aclarar el ámbito de la configuración.

+++

+++**Actualización de mantenimiento del 26 de enero de 2023**

**Error al enviar la solicitud desde [!DNL Outlook]**

_Integraciones_

Cuando un usuario intenta enviar una solicitud con datos adjuntos de un correo electrónico de [!DNL Outlook], uno o más archivos adjuntos no se cargan y el usuario ve el siguiente error:

“[!UICONTROL Se produjo el siguiente error: El archivo con el identificador xxxx no existe.]”

Esto solo ocurre cuando se realiza una asignación para la nueva solicitud, ya sea a través de la cola de solicitudes o manualmente al crear la solicitud.

**Nueva versión de Desktop Proofing Viewer**

_Revisión_

Para solucionar un problema de congelación en Desktop Proofing Viewer, hemos implementado una nueva versión del visor de revisión de escritorio. Los usuarios que ya tengan instalado Desktop Proofing Viewer obtendrán esta actualización automáticamente.

Los usuarios también pueden descargar manualmente la versión más reciente. Para obtener más información, consulte [Instalación de Desktop Proofing Viewer](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=es).

* Versión anterior: 2.1.19
* Nueva versión: 2.1.20

**El usuario no puede editar su propia configuración de usuario**

_Usuarios_

Cuando un usuario con una licencia de Trabajo, Revisión o Solicitud intenta editar su propia configuración de usuario, la ventana emergente que se abre está en blanco y el usuario no puede realizar ningún cambio. Para salir de la ventana emergente, el usuario debe actualizar la página.

+++

+++**Actualización de mantenimiento del 19 de enero de 2023**

**Los filtros de columnas de admisión ahora se pueden compartir**

_Tableros_

Cuando la funcionalidad de columna de admisión se envió a los Paneles, la persona que creó esos filtros solo podía ver los filtros para configurar la columna de entrada. Ahora el creador puede compartir los filtros con otros usuarios o equipos.

**Funcionalidad de pines disponible en el menú [!UICONTROL Más]**

_Navegación_

Las siguientes funciones ya están disponibles en el menú [!UICONTROL Más] para pines, en el entorno de producción:

* Cambio del nombre de los pines
* Reorganización de pines dentro del menú [!UICONTROL Más]
* Desplazamiento de un pin fuera del menú [!UICONTROL Más] (al hacerlo, el último pin de la barra de navegación superior se mueve al menú [!UICONTROL Más])

+++

+++**Actualización de mantenimiento del 18 de enero de 2023**

**Las expresiones con caracteres comodín no son válidas en los campos personalizados**

_Formularios personalizados_

Cuando un usuario utiliza un comodín como \$$TODAY o $$NOW junto con un modificador (como “-30d”) en un campo personalizado, el validador no acepta el comodín como válido. Los comodines sin modificadores se consideran válidos.

El **[!UICONTROL Distribuidor de cargas de trabajo] muestra las horas que no están asociadas a un proyecto, tarea o problema**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario visualizo el [!UICONTROL Distribuidor de cargas de trabajo], verá las horas registradas para un usuario que no está asociado a ningún proyecto, tarea o problema, ni se registran como horas [!UICONTROL Generales]. Estas horas solo pueden mostrarse en la vista de 4 o 6 semanas.

+++

+++Actualización de mantenimiento de **[!DNL Adobe Workfront Fusion] (Hot Fix) el 12 de enero de 2023**

**Errores 404 en módulos [!DNL Workfront]**

_Workfront Fusion_

Cuando se ejecuta un escenario, un módulo [!DNL Workfront] devuelve un error 404.

Se ha informado de este problema en los siguientes módulos:

* [!UICONTROL Leer un registro]

+++

+++**Actualización de mantenimiento (Hot Fix) el 12 de enero de 2023**

**Error “[!UICONTROL ¡Uy!]” al configurar un campo calculado**

_Formularios personalizados_

Cuando un usuario crea o edita un campo calculado en un formulario personalizado e incluye un campo personalizado en la expresión del campo calculado, la expresión se considera no válida. El botón [!UICONTROL Guardar] está desactivado y el usuario no puede salir del campo personalizado. Además, el usuario recibe el siguiente mensaje debajo del campo:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo]”.

Al eliminar el campo personalizado de la expresión, el usuario puede guardar y desplazarse fuera del campo.

**No se pueden establecer niveles de acceso**

_Usuarios_

Cuando un usuario intenta cambiar el nivel de acceso de otro usuario, los niveles de acceso aparecen atenuados y el usuario no puede cambiarlos. Esto ocurre incluso cuando el usuario que intenta realizar el cambio es un administrador del sistema.

+++

+++**Actualización de mantenimiento del 12 de enero de 2023**

**Ctrl+F o Cmd+F no funcionan como se espera en los campos desplegables**

_Formularios personalizados_

Cuando un usuario rellena un formulario personalizado y busca en una lista desplegable utilizando Ctrl+F o Cmd+F, luego intenta ir a la siguiente instancia de la búsqueda, la lista desplegable vuelve a la parte superior de la lista en lugar de saltar a la siguiente instancia de la búsqueda. Esto ocurre cuando se establece un menú desplegable para permitir varias selecciones.

La pantalla **[!UICONTROL Editar informe] está en blanco**

_Informes_

Cuando un usuario está viendo un informe y trata de editarlo, se le dirige a una pantalla en blanco y no puede hacerlo.

**Las tareas con sangría no permanecen con sangría**

_Tareas_

Cuando un usuario está viendo una lista de tareas y aplica sangría a una tarea, la tarea vuelve inmediatamente a su estado original (obsoleto).

+++

+++**Actualización de mantenimiento del 5 de enero de 2023**

**Funcionalidad de pines disponible en el menú [!UICONTROL Más]**

_Navegación_

Las siguientes funciones ya están disponibles en el menú [!UICONTROL Más] para pines, solo en el entorno de vista previa:

* Cambio del nombre de los pines
* Reorganización de pines dentro del menú [!UICONTROL Más]
* Desplazamiento de un pin fuera del menú [!UICONTROL Más] (al hacerlo, el último pin de la barra de navegación superior se mueve al menú [!UICONTROL Más])

**Se ha eliminado la limitación de grupos de proyectos al agregar usuarios al equipo de proyectos**

_Equipos_

Se ha eliminado la limitación que requería que los usuarios que deben agregarse a un equipo de proyectos estuvieran en el Grupo asociado al proyecto. Ahora, puede agregar cualquier usuario activo a un equipo de proyectos, independientemente de los grupos a los que pertenezca.

**Nuevos iconos de información para las plantillas de horas, los perfiles de plantillas de horas y las preferencias de plantillas de horas**

>[!NOTE]
>
>Esta actualización se publicó en el entorno de vista previa el 3 de noviembre de 2022 y ya está disponible en Producción

_Workfront_

Hemos añadido varios iconos de información a las siguientes opciones de configuración:

* Casilla de verificación “Puede editar las horas”: al crear o editar una plantilla de horas o un perfil de plantilla de horas, para indicar que, cuando está activada, los aprobadores también pueden enviar, volver a abrir o editar la plantilla de horas, a menos que el administrador restrinja estas acciones en el área Preferencias de plantilla de horas de Configuración.
* “Restringir la edición de la plantilla de horas a propietarios y administradores”: en el área Preferencias de plantilla de horas y horas de Configuración, para indicar que, cuando está desactivada, los siguientes usuarios también pueden editar las plantillas de horas: usuarios con acceso administrativo a plantillas de horas y horas, aprobadores de plantillas de horas que tienen permiso para editar las horas y administradores de propietarios de plantilla de horas.

Tenga en cuenta que la funcionalidad de estas opciones de configuración no ha cambiado y que solo se han añadido los iconos de información para aclarar el ámbito de la configuración.

+++

## Actualizaciones de mantenimiento anteriores

La información sobre actualizaciones de mantenimiento anteriores está disponible aquí:

* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2022](2022-updates.md)
* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] 2021](2021-updates.md)
