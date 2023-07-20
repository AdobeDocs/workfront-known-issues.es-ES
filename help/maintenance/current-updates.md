---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '4258'
ht-degree: 98%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2023 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

Para ver las actualizaciones de mantenimiento anteriores a 2023, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones en julio de 2023

+++**Actualización de mantenimiento del 20 de julio de 2023**

**Establezca las horas planificadas en tareas secundarias recurrentes con [!UICONTROL Sencilla] tipo de duración sin asignaciones**

_Tareas_

Ahora, cuando establece horas planificadas en una nueva tarea principal recurrente con un [!UICONTROL Sencilla] Tipo de duración y sin asignaciones, las horas también se añaden a las recurrencias individuales. Antes de este cambio, las horas no se guardaban para las repeticiones cuando se quitaba la asignación de las tareas principales.

+++

+++**Actualización de mantenimiento del 13 de julio de 2023**

**La cronología no se recalcula**

_Proyectos / tareas / problemas_

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

+++**Actualización de mantenimiento el 29 de junio de 2023**

Esta actualización contiene solo correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

+++

+++**Actualización de mantenimiento el 22 de junio de 2023**

**Error &quot;[!UICONTROL ¡Uy!]&quot; al ver el informe de matriz**

_Informes_

Cuando un usuario ve un informe de matriz, ve el siguiente error:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo.]”

Esto se ha notificado cuando el informe se ordena por fecha y la opción &quot;[!UICONTROL Mostrar semanas sin resultados]&quot; está activada.

**Las fechas no se muestran correctamente en los informes de matriz**

_Informes_

Cuando un gráfico o informe de matriz se agrupa por fecha, las fechas cerca de los bordes de la agrupación pueden aparecer en la agrupación correcta, en la agrupación anterior o siguiente, o en ambas.

+++

+++**Actualización de mantenimiento el 15 de junio de 2023**

Esta actualización contiene solo correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

+++

+++**Actualización de mantenimiento el 8 de junio de 2023**

Esta actualización contiene solo correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront] le avisará cuando haya solucionado un problema enviado por usted.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento el 8 de junio de 2023**

[!DNL Fusion] ha implementado una corrección que impide que se eliminen las conexiones de un usuario cuando este se elimina o desactiva en la [!UICONTROL Adobe Admin Console].

[!DNL Fusion] Los administradores de equipo siguen pudiendo quitar conexiones innecesarias de la página [!UICONTROL Conexiones] en [!DNL Fusion].

+++

+++**Actualización de mantenimiento el 1 de junio de 2023**

**No hay ningún mensaje de error al reordenar la tarea en el estado [!UICONTROL Pendiente de aprobación]**

_Tareas_

Cuando un usuario intenta reordenar una tarea en una lista de tareas y la tarea se encuentra en [!UICONTROL Pendiente de aprobación], la tarea parece moverse en la lista de tareas. Cuando se actualiza, el usuario ve que el elemento no se ha movido. El elemento no se puede mover porque está en estado [!UICONTROL Pendiente de aprobación], pero no hay ningún mensaje que indique al usuario que el elemento no se puede mover, lo que puede provocar confusión.

**No hay ningún mensaje de error al mover la tarea predecesora a una tarea dependiente**

_Tareas_

Cuando un usuario intenta reordenar una tarea en una lista de tareas y la tarea se encuentra en [!UICONTROL Pendiente de aprobación], la tarea parece moverse en la lista de tareas. Cuando se actualiza, el usuario ve que el elemento no se ha movido. El elemento no se puede mover porque una tarea predecesora no se puede mover a una tarea de la que es predecesora, pero no hay ningún mensaje que indique al usuario que el elemento no se puede mover, lo que puede llevar a confusión.

+++

## Actualizaciones en mayo de 2023

+++**Actualización de mantenimiento: 25 de mayo de 2023**

El tablero **[!UICONTROL Kanban] se queda en blanco al editar tarjetas**

_Agile_

Cuando un usuario cambia algo acerca de una tarjeta en el tablero [!UICONTROL Kanban], el tablero [!UICONTROL Kanban] se queda en blanco en lugar de actualizarse con el cambio. Si el usuario actualiza la página manualmente, el tablero [!UICONTROL Kanban] vuelve y muestra el cambio correcto.

Se ha informado de esto en las siguientes circunstancias:

* Edición de una tarjeta
* Mover una tarjeta


+++

+++**Actualización de mantenimiento: 22 de mayo de 2023**

**No se puede ajustar el tamaño del texto descriptivo**

_Formularios personalizados_

Cuando se lanzó el diseñador de formularios personalizado en la versión beta, la funcionalidad para ajustar el tamaño del texto descriptivo no estaba disponible. Este problema se ha corregido y los usuarios ahora pueden ajustar el tamaño del texto descriptivo.

+++

+++**Actualización de mantenimiento: 18 de mayo de 2023**

**El informe no se ordena correctamente al ordenar por campo personalizado**

_Informes_
Cuando un usuario ejecuta un informe de tareas, este parece ordenarse correctamente cuando se está cargando, pero cuando termina se ve que no está bien ordenado.

Esto parece ocurrir si se cumplen todas las siguientes circunstancias:

* El informe es uno de tareas
* El informe se ordena por un campo personalizado
* El informe tiene una agrupación aplicada

+++

+++**Actualización de mantenimiento: el 11 de mayo de 2023**

**No se puede cambiar de versión de prueba al ver la prueba**

_Pruebas_

Cuando se está viendo una prueba en el [!UICONTROL Visor de revisión] y se cambia a otra versión, el desplegable de la versión se desactiva y no se puede volver a la versión original que se estaba viendo ni a otra versión de la prueba.

Búsqueda de **[!DNL Workfront]agotada**

_Búsqueda_

[!DNL Workfront] la búsqueda está agotando el tiempo de espera. La búsqueda puede arrojar algunos resultados, o ninguno.

Este problema también afecta a la funcionalidad del [!DNL Workfront Fusion] > [!DNL Workfront] > módulo de [!UICONTROL búsqueda].

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento: 11 de mayo de 2023**

**Errores de tiempo de espera en[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Cuando se está ejecutando un escenario, puede producirse un error de tiempo de espera. La información del módulo con el error no llega a su destino.

Búsqueda de **[!DNL Workfront]agotada**

_Búsqueda_

[!DNL Workfront] la búsqueda está agotando el tiempo de espera. La búsqueda puede arrojar algunos resultados, o ninguno.

Este problema también afecta a la funcionalidad del [!DNL Workfront Fusion] > [!DNL Workfront] > módulo de [!UICONTROL búsqueda].

+++

+++**Actualización de mantenimiento: 9 de mayo de 2023**

**Filtros guardados disponibles en la columna de entrada del tablero**

_Tableros_

Ahora puede utilizar los filtros de problemas y tareas de Workfront existentes al configurar la columna de entrada para un tablero. Sin embargo, los filtros de columna de entrada existentes son ahora de solo lectura en el panel de configuración. Los filtros existentes se siguen aplicando a la columna de entrada, pero debe volver a crear los filtros si desea editarlos.

+++

+++**Actualización de mantenimiento del 4 de mayo de 2023**

**No se puede seleccionar la plantilla de [!UICONTROL Plantillas favoritas]**

_Plantillas_

Cuando un usuario intenta seleccionar una plantilla del menú Acciones (tres puntos), la lista de plantillas desaparece cuando mueve el ratón a la lista y no se puede. Esto se debe a que la barra de desplazamiento está entre el menú y la lista de plantillas, y el ratón se centra en la barra de desplazamiento a medida que se mueve a la lista de plantillas.

+++

## Actualizaciones en abril de 2023

+++**Actualización de mantenimiento del 27 de abril de 2023**

**No se puede cambiar entre pruebas en el [!UICONTROL Visualizador de pruebas]**

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

Cuando un se está viendo una prueba, se comienza a añadir un comentario y se abre la herramienta Texto, la palabra &quot;textAnnotation&quot; aparece junto a las opciones de la herramienta. La herramienta Texto sigue funcionando como se espera y &quot;textAnnotation&quot; desaparece después de publicar el comentario.

**Mantener las imágenes como borrador al alejarse de una actualización para objetivos y problemas en la experiencia de comentarios beta**

>[!NOTE]
>
>Esta función se publicó como previsualización el 19 de abril de 2023 y en producción el 20 de abril de 2023.

_Actualizaciones_

Ahora, cuando se aleja de la página Actualizaciones mientras está redactando un mensaje en el que ha adjuntado una imagen, el mensaje y la imagen se conservan al volver. Antes de esta actualización, el comentario no enviado se mantenía, pero la imagen se borraba. Esto está disponible en la sección Actualizaciones para objetivos y en la de problemas al habilitar la experiencia de comentarios beta.

**Actualizaciones en tiempo real y comentarios eliminados en la sección Actualizaciones**

>[!NOTE]
>
>Esta función se publicó como previsualización el 19 de abril de 2023 y en producción el 20 de abril de 2023.

_Actualizaciones_

Ahora, cuando alguien agrega un comentario o responde, o elimina un comentario del área Actualizaciones, puede ver el nuevo comentario o una indicación de que un comentario se ha borrado en tiempo real, sin demoras. Esto está disponible en la sección Actualizaciones para objetivos y en la de problemas al habilitar la experiencia de comentarios beta.

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

**No se puede seleccionar [!UICONTROL Tipo de hora predeterminado] o [!UICONTROL Tipos de hora disponibles]**

_Usuarios_

Cuando un administrador está editando un usuario e intenta seleccionar un [!UICONTROL Tipo de hora predeterminado] o [!UICONTROL Tipo de hora disponible], verá que los desplegables de esos campos están deshabilitados y que no puede.

+++

+++**Actualización de mantenimiento del 6 de abril de 2023**

**Los desplegables no se abren cuando se añade a un usuario a una prueba**

_Pruebas_

Cuando un usuario añade a otro usuario a una prueba en el [!UICONTROL Visor de revisión], los menús desplegables de la &quot;[!UICONTROL Función de prueba]&quot; y de las &quot;[!UICONTROL Alertas de correo electrónico]&quot; no se pueden abrir. No se puede asignar una función de prueba o una alerta de correo electrónico. Esto puede ocurrir al añadir a un usuario a través de un comentario o al compartir la prueba con el usuario.

+++

## Actualizaciones en marzo de 2023

+++**Actualización de mantenimiento del 30 de marzo de 2023**

**No se puede cambiar de versión de prueba al ver la prueba**

_Pruebas_

Cuando se está viendo una prueba en el [!UICONTROL Visor de revisión] y se cambia a otra versión, el desplegable de la versión se desactiva y no se puede volver a la versión original que se estaba viendo ni a otra versión de la prueba.

**Error 504 al exportar informes**

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

Para solucionar un problema de comentarios en [!UICONTROL Desktop Proofing Viewer], hemos implementado una nueva versión del visor de revisión de escritorio.

Cuando [!UICONTROL Desktop Proofing Viewer] ya está instalado, esta actualización se obtiene automáticamente.

También es posible descargar manualmente la versión más reciente. Para obtener más información, consulte [[!UICONTROL Instalación de Desktop Proofing Viewer]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html).

* Versión anterior: 2.1.22
* Nueva versión: 2.1.23

+++

+++**Actualización de mantenimiento del 16 de marzo de 2023**

**Elementos de la lista de comprobación no copiados al copiar una tarjeta**

_Tableros_

Al copiar una tarjeta ad hoc (las tarjetas conectadas no se pueden copiar), los elementos de la lista de comprobación no se copian en la nueva tarjeta.

**Falta el campo personalizado cuando el problema se convierte en proyecto**

_Proyectos_

Cuando un usuario convierte un problema en un proyecto mediante una plantilla, un campo personalizado que estaba en el problema no se muestra en el proyecto. Este problema solo afecta a los no administradores.

**Los mensajes personalizados no aparecen en las notificaciones por correo electrónico**

_Pruebas_

Cuando un usuario comparte una prueba y añade un mensaje personalizado, ese mensaje personalizado no aparece en el correo electrónico de notificación al destinatario. El asunto es el nombre de la revisión y el mensaje no aparece en el correo electrónico.

+++

+++**Actualización de mantenimiento del 9 de marzo de 2023**

**El nivel de acceso no está asignado al reactivar el usuario**

_Usuarios_

Cuando un usuario está reactivando un usuario desactivado e intenta asignarle un nivel de acceso en la ventana [!UICONTROL Reactivar usuario], la lista desplegable de nivel de acceso no se rellena a medida que se va escribiendo, y el usuario no puede seleccionar un nivel de acceso. Si el usuario escribe el nivel de acceso y guarda, el nivel de acceso no se asigna al usuario.

**Guarde el borrador de un comentario en el área [!DNL Goals]**

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

Cuando un usuario intenta cargar la página Imprimir resumen, la página parece estar cargándose, pero nunca se carga.

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

Se ha agregado el campo **[!UICONTROL Puntos de caso] a los informes y las listas de tareas y problemas**

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

_Configurar_

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

_Exploración_

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

Cuando un usuario ve la variable [!UICONTROL Distribuidor de cargas de trabajo], verá las horas registradas para un usuario que no está asociado a ningún proyecto, tarea o problema, ni se registran como horas [!UICONTROL Generales]. Estas horas solo pueden mostrarse en la vista de 4 o 6 semanas.

+++

+++Actualización de mantenimiento de **[!DNL Adobe Workfront Fusion] (Hot Fix) el 12 de enero de 2023**

**Errores 404 en módulos [!DNL Workfront]**

_Workfront Fusion_

Cuando se ejecuta un escenario, un módulo [!DNL Workfront] devuelve un error 404.

Se ha informado de este problema en las siguientes módulos:

* [!UICONTROL Leer un registro]

+++

+++**Actualización de mantenimiento (Hot Fix) el 12 de enero de 2023**

**Error “[!UICONTROL ¡Uy!]” al configurar un campo calculado**

_Formularios personalizados_

Cuando un usuario crea o edita un campo calculado en un formulario personalizado e incluye un campo personalizado en la expresión del campo calculado, la expresión se considera no válida. El botón [!UICONTROL Guardar] está desactivado y el usuario no puede salir del campo personalizado. Además, el usuario recibe el siguiente mensaje debajo del campo:

“[!UICONTROL ¡Uy! Se ha producido un error. Póngase en contacto con Workfront para que podamos averiguar qué ha fallado y solucionarlo.]”

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

_Exploración_

Las siguientes funciones ya están disponibles en el menú [!UICONTROL Más] para pines, solo en el entorno de vista previa:

* Cambio del nombre de los pines
* Reorganización de pines dentro del menú [!UICONTROL Más]
* Desplazamiento de un pin fuera del menú [!UICONTROL Más] (al hacerlo, el último pin de la barra de navegación superior se mueve al menú [!UICONTROL Más])

**Se ha eliminado la limitación de grupos de proyectos al agregar usuarios al equipo de proyectos**

_Equipos_

Se ha eliminado la limitación que requería que los usuarios que deben agregarse a un equipo de proyecto estuvieran en el Grupo asociado al proyecto. Ahora, puede agregar cualquier usuario activo a un equipo de proyecto, independientemente de los grupos a los que pertenezca.

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

* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] - 2022](2022-updates.md)
* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront] - 2021](2021-updates.md)
