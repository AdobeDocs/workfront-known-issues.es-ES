---
title: 'Nueva página de inicio: el filtro de widget y los valores predeterminados de agrupación no siguen la plantilla de diseño'
description: Cuando un usuario ve el widget Mis proyectos, Mis tareas, o Mis problemas en la nueva experiencia de inicio, el filtro y la agrupación predeterminados para ese widget no son los valores predeterminados de la plantilla de diseño asignada a ese usuario.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: ht
source-wordcount: '191'
ht-degree: 100%

---

# Nuevo [!UICONTROL Inicio]: el filtro de widget y los valores predeterminados de agrupación no siguen la plantilla de diseño

>[!NOTE]
>
>Este problema se ha cerrado porque funciona como se diseñó.

Cuando un usuario ve el [!UICONTROL Mis proyectos], [!UICONTROL Mis tareas], o [!UICONTROL Mis problemas] widget en la nueva experiencia de [!UICONTROL Inicio], el filtro y la agrupación predeterminados para ese widget no son los valores predeterminados en la plantilla de diseño asignada a ese usuario.

**Solución alternativa**:

Al utilizar la nueva página de inicio, es importante recordar que la configuración del usuario (preferencias) tiene prioridad. Como resultado, si establece un filtro o una agrupación predeterminados para un widget específico mediante una plantilla de diseño, es posible que no surta efecto inmediatamente debido a las preferencias de usuario existentes. Para aplicar el nuevo filtro o agrupación, es posible que usted o el usuario tengan que restablecer las preferencias. Esto se puede hacer añadiendo `/resetUser` a su URL.

_Informado por primera vez el 3 de enero de 2024._
