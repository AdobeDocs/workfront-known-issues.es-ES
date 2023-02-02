---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 9cd28fae4c6e1a3c6759353351de4b09a46984f3
workflow-type: tm+mt
source-wordcount: '1402'
ht-degree: 76%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2023 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront]le avisará cuando haya solucionado un problema enviado por usted.

Para ver las actualizaciones de mantenimiento anteriores a 2023, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones en febrero de 2023

+++**Actualización de mantenimiento del 2 de febrero de 2023**

**El icono Tableros aparece en el menú principal de forma predeterminada**

_Tableros_

El icono Tableros aparece ahora en el menú principal para los usuarios que no tienen una plantilla de diseño. Los tableros también se incluyen en el menú principal de forma predeterminada para cualquier plantilla de diseño nueva que se cree. Las plantillas de diseño existentes no han cambiado.

**No se pueden guardar las plantillas de correo electrónico**

_Configurar_

Cuando un usuario intenta crear o editar una plantilla de correo electrónico, el botón [!UICONTROL Guardar] no responde y el usuario no puede guardar la plantilla.

+++

+++**Actualización de mantenimiento del 30 de enero de 2023**

**Métodos abreviados de teclado agregados para acciones comunes de hojas de horas**

_Plantillas de horas_

Hemos introducido los siguientes métodos abreviados del teclado para las siguientes acciones que se realizan con más frecuencia dentro de un parte de horas:

* Añadir fila (Cmd+Opción++ / Ctrl+Opción++)
* Eliminar fila (Cmd+Opción+- / Ctrl+Opción+-)
* Fijar o desfijar un elemento de trabajo (Opción+P/Opción+P)
* Abrir comentario (Mayús + F2 / Mayús + F2)
* Guardar comentario (Cmd+Intro/Ctrl+Intro)
* Expandir (Mayús+Opción+Flecha arriba/Mayús+Alt+Flecha arriba)
* Contraer (Mayús+Opción+Flecha abajo/ Mayús+Alt+Flecha abajo)

El área en la que se realizan estas acciones debe estar resaltada para que se apliquen.

**Nuevos iconos de información para las plantillas de horas, los perfiles de plantillas de horas y las preferencias de plantillas de horas**

_Plantillas de horas_

>[!NOTE]
>
>Esta actualización solo se publicó en el entorno de vista previa el 3 de noviembre de 2022 y ahora está disponible en Producción.

Hemos añadido varios iconos de información a las siguientes opciones de configuración:

* &quot;[!UICONTROL Puede editar el tiempo]&quot; al crear o editar un parte de horas o un perfil de parte de horas para indicar que, cuando está activado, los aprobadores también pueden enviar, volver a abrir o editar el parte de horas, a menos que el administrador restrinja estas acciones en [!UICONTROL Preferencias de partes de horas] área de [!UICONTROL Configuración].
* &quot;[!UICONTROL Restringir la edición de hojas de horas a propietarios y administradores]&quot; en el [!UICONTROL Preferencias de horario y hora] área de [!UICONTROL Configuración] para indicar que, cuando está desactivado, los siguientes usuarios también pueden editar las partes de horas: usuarios con acceso administrativo a hojas de horas y horas, aprobadores de hojas de horas permitidos para editar la hora y administradores de propietarios de hojas de horas.

Tenga en cuenta que la funcionalidad de estas opciones de configuración no ha cambiado y que solo se han añadido los iconos de información para aclarar el ámbito de la configuración.

+++

+++**Actualización de mantenimiento del 26 de enero de 2023**

**Error al enviar la solicitud desde[!DNL Outlook]**

_Integraciones_

Cuando un usuario intenta enviar una solicitud con datos adjuntos de un correo electrónico de [!DNL Outlook], uno o más archivos adjuntos no se cargan y el usuario ve el siguiente error:

&quot;[!UICONTROL Se produjo el siguiente error: El archivo con el identificador xxxx no existe.]&quot;

Esto solo ocurre cuando se realiza una asignación para la nueva solicitud, ya sea a través de la cola de solicitudes o manualmente al crear la solicitud.

**Nueva versión del visor de prueba de escritorio**

_Prueba_

Para solucionar un problema de congelación en el Visor de prueba de escritorio, hemos implementado una nueva versión del visor de pruebas de escritorio. Los usuarios que ya tengan instalado Desktop Proofing Viewer obtendrán esta actualización automáticamente.

Los usuarios también pueden bajar manualmente la versión más reciente. Para obtener más información, consulte [Instalación del Visor de prueba de escritorio](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Versión anterior: 2.1.19
* Nueva versión: 2.1.20

**El usuario no puede editar su propia configuración de usuario**

_Usuarios_

Cuando un usuario con una licencia de Trabajo, Revisión, o Solicitud intenta editar su propia configuración de usuario, la ventana emergente que se abre está en blanco y el usuario no puede realizar ningún cambio. Para salir de la ventana emergente, el usuario debe actualizar la página.

+++

+++**Actualización de mantenimiento del 19 de enero de 2023**

**Los filtros de columnas de entrada ahora se pueden compartir**

_Tableros_

Cuando la funcionalidad de columna de entrada se envió a los Paneles, la persona que creó esos filtros solo podía ver los filtros para configurar la columna de entrada. Ahora el creador puede compartir los filtros con otros usuarios o equipos.

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

El **[!UICONTROL Distribuidor de cargas de trabajo] muestra las horas que no están asociadas a un proyecto, tarea o problema**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario ve la variable [!UICONTROL Distribuidor de cargas de trabajo], verá las horas registradas para un usuario que no está asociado a ningún proyecto, tarea o problema, ni se registran como horas [!UICONTROL Generales]. Estas horas solo pueden mostrarse en la vista de 4 o 6 semanas.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento (Hot Fix) el 12 de enero de 2023**

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

La pantalla **[!UICONTROL Editar informe] está en blanco**

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

* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront]- 2022](2022-updates.md)
* [Archivo de actualizaciones de mantenimiento de [!DNL Workfront]- 2021](2021-updates.md)
