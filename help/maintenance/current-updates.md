---
title: Actualizaciones de mantenimiento de Workfront
description: Actualizaciones de mantenimiento para [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 244d9f48b2f63bf2b0b30259e42ca9317f5ad933
workflow-type: tm+mt
source-wordcount: '879'
ht-degree: 74%

---

# Actualizaciones de mantenimiento de [!DNL Workfront]

En 2023 se realizaron las siguientes actualizaciones de mantenimiento.

>[!NOTE]
>
>Estas actualizaciones también incluyen otras correcciones de errores menores o menos importantes. El servicio de asistencia técnica de [!DNL Workfront]le avisará cuando haya solucionado un problema enviado por usted.

Para ver las actualizaciones de mantenimiento anteriores a 2023, consulte [Actualizaciones de mantenimiento anteriores](#previous-maintenance-updates)

## Actualizaciones en enero de 2023

+++**Actualización de mantenimiento del 19 de enero de 2023**

**Los filtros de columnas de entrada ahora se pueden compartir**

_Tableros_

Cuando la función de columna de admisión se liberó a los tableros, la persona que creó esos filtros solo podía ver los filtros para configurar la columna de admisión. Ahora el creador puede compartir los filtros con otros usuarios o equipos.

**Funcionalidad de pines disponible en el menú [!UICONTROL Más]**

_Exploración_

Las siguientes funciones ya están disponibles en la sección [!UICONTROL Más] para pines, en el entorno Producción:

* Cambio del nombre de los pines
* Reorganización de pines dentro del menú [!UICONTROL Más]
* Desplazamiento de un pin fuera del menú [!UICONTROL Más] (al hacerlo, el último pin de la barra de navegación superior se mueve al menú [!UICONTROL Más])

+++

+++**Actualización de mantenimiento del 18 de enero de 2023**

**Las expresiones con caracteres comodín no son válidas en los campos personalizados**

_Formularios personalizados_

Cuando un usuario utiliza un comodín como \$$TODAY o $$AHORA junto con un modificador (como &quot;-30d&quot;) en un campo personalizado, el validador no acepta el comodín como válido. Los comodines sin modificadores se consideran válidos.

**[!UICONTROL Equilibrador de carga de trabajo] muestra las horas que no están asociadas a un proyecto, tarea o problema**

_[!UICONTROL Distribuidor de cargas de trabajo]_

Cuando un usuario ve la variable [!UICONTROL Equilibrador de carga de trabajo], verán las horas registradas para un usuario que no está asociado a ningún proyecto, tarea o problema, ni se registran como [!UICONTROL General] horas. Estas horas solo pueden mostrarse en la vista de 4 semanas o 6 semanas.

+++

+++**[!DNL Adobe Workfront Fusion]Actualización de mantenimiento (corrección) el 12 de enero de 2023**

**Errores 404 en módulos[!DNL Workfront]**

_Workfront Fusion_

Cuando se ejecuta un escenario, un módulo [!DNL Workfront] devuelve un error 404.

Se ha informado de este problema en las siguientes módulos:

* [!UICONTROL Leer un registro]

+++

+++**Actualización de mantenimiento (corrección) el 12 de enero de 2023**

**&quot;[!UICONTROL Whoops]&quot; error al configurar un campo calculado**

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
