---
title: "Workfront Fusion: No se puede crear la conexión con Google"
description: "Cuando un usuario intenta crear una conexión en cualquiera de los conectores de Google (como hojas de Google o unidad de Google), la conexión no se crea y el usuario ve varios mensajes de error."
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# [!DNL Workfront Fusion]: No se puede crear la conexión con [!DNL Google]

Cuando un usuario intenta crear una conexión en cualquiera de los [!DNL Google] conectores (como [!DNL Google Sheets] o [!DNL Google Drive]), verán una ventana abierta con el siguiente error:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Cuando el usuario cierra esta ventana, la conexión falla con el siguiente error dentro [!DNL Fusion]:

&quot;[!UICONTROL Error: La solicitud falló debido al error de una solicitud anterior. No se especificó ningún token de acceso.]&quot;

_Notificado por primera vez el 21 de noviembre de 2022._

