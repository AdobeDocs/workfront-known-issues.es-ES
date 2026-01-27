---
title: 'Workfront Fusion: el módulo de búsqueda de Jira devuelve un error'
description: El módulo de búsqueda utilizado por el conector Jira heredado puede provocar un error. Hay una solución alternativa disponible
hidefromtoc: true
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
source-git-commit: 8c2968464f1a7c8347a21367b940b8c298fde727
workflow-type: ht
source-wordcount: '186'
ht-degree: 100%

---

# Workfront Fusion: el módulo de búsqueda de Jira devuelve un error

>[!NOTE]
>
>Este problema se debe a un cambio que Jira realizó en su producto.

El módulo de búsqueda utilizado por el conector Jira heredado puede provocar el siguiente error:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Esto se debe a una obsolescencia por parte de Jira.

Tenga en cuenta lo siguiente:

* Solo se ve afectado el módulo Buscar. En este momento, otros puntos de conexión de API de Jira utilizados por el conector Fusion no se ven afectados por esta obsolescencia.

* El despliegue geográfico puede causar incoherencias. Atlassian está implementando este cambio a nivel regional, lo que significa que algunas instancias de Jira Cloud pueden seguir admitiendo temporalmente puntos de conexión más antiguos. Esto puede generar un comportamiento incoherente entre entornos.

**Solución**

Si encuentra este error, puede reemplazar el módulo de búsqueda del conector Jira heredado por el módulo de búsqueda del conector nuevo. Tenga en cuenta que el nuevo conector le permite seleccionar la versión de API utilizada. Asegúrese de seleccionar **V3** en el campo **versión de API** al crear la conexión.

_Notificado por primera vez el 15 de septiembre de 2025._
