---
title: 'Nueva página de inicio: el filtro de widget y los valores predeterminados de agrupación no siguen la plantilla de diseño'
description: Cuando un usuario ve el widget Mis proyectos, Mis tareas, o Mis problemas en la nueva experiencia de inicio, el filtro y la agrupación predeterminados para ese widget no son los valores predeterminados de la plantilla de diseño asignada a ese usuario.
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c042179c-157b-516d-b27c-e3bf303e8567
    internal-label: Get Started with Workfront
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 93%
---
# Nuevo [!UICONTROL Inicio]: el filtro de widget y los valores predeterminados de agrupación no siguen la plantilla de diseño

>[!NOTE]
>
>Este problema se ha cerrado porque funciona según lo previsto.

Cuando un usuario ve el [!UICONTROL Mis proyectos], [!UICONTROL Mis tareas], o [!UICONTROL Mis problemas] widget en la nueva experiencia de [!UICONTROL Inicio], el filtro y la agrupación predeterminados para ese widget no son los valores predeterminados en la plantilla de diseño asignada a ese usuario.

**Solución alternativa**:

Al utilizar la nueva página de inicio, es importante recordar que la configuración del usuario (preferencias) tiene prioridad. Como resultado, si establece un filtro o una agrupación predeterminados para un widget específico mediante una plantilla de diseño, es posible que no surta efecto inmediatamente debido a las preferencias de usuario existentes. Para aplicar el nuevo filtro o agrupación, es posible que usted o el usuario tengan que restablecer las preferencias. Esto se puede hacer añadiendo `/resetUser` a su URL.

_Informado por primera vez el 3 de enero de 2024._
