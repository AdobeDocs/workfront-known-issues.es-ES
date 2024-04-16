---
title: '“Plantillas de diseño: las plantillas de diseño causan incoherencias en los informes”'
description: Las plantillas de diseño de la experiencia clásica de Workfront ya no están disponibles en la interfaz de Workfront, pero pueden afectar a los datos de Workfront. Esto puede provocar incoherencias en los campos afectados por las plantillas de diseño (como el campo Compartido con) en los informes o paneles.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 2631a7a9cd6c07feae192cb0e29f168929fc9f3c
workflow-type: ht
source-wordcount: '193'
ht-degree: 100%

---

# Plantillas de diseño: las plantillas de diseño causan incoherencias en los informes

<!--Live for workaround-->

Las plantillas de diseño de la experiencia clásica de [!DNL Workfront] ya no están disponibles en la interfaz de [!DNL Workfront], pero pueden seguir afectando a los datos de [!DNL Workfront]. Esto puede provocar incoherencias en los campos afectados por las plantillas de diseño (como el campo [!UICONTROL Compartido con]) en los informes o paneles.

**Solución alternativa**

Elimine las plantillas de diseño de la experiencia clásica mediante una llamada de API. Debe haber iniciado sesión en Workfront.

>[!NOTE]
>
>Las plantillas de diseño del tipo Global y Sistema no se pueden eliminar.

1. Busque la plantilla de diseño que desea eliminar mediante la siguiente llamada de API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Tome nota del ID de la plantilla de diseño que desea eliminar.
1. Localice el ID de sesión con la siguiente llamada de API:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Nunca comparta su ID de sesión con nadie.

1. Inserte el ID de la plantilla de diseño y el ID de sesión en la siguiente llamada de API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Pegue la llamada de API del paso 4 en la barra URL del explorador y pulse Intro.

   Esto elimina la plantilla de diseño.
