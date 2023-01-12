---
title: '“Workfront Fusion: no se puede crear la conexión con Google”'
description: Cuando un usuario intenta crear una conexión en cualquiera de los conectores de Google (como Hojas de cálculo de Google o Google Drive), la conexión no se crea y el usuario ve varios mensajes de error.
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '109'
ht-degree: 94%

---

# [!DNL Workfront Fusion]: no se puede crear la conexión con [!DNL Google]

>[!NOTE]
>
>Este problema se corrigió el 9 de enero de 2023.

Cuando un usuario intenta crear una conexión en cualquiera de los conectores de [!DNL Google] (como [!DNL Google Sheets] o [!DNL Google Drive]), se abre una ventana con el siguiente error:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Cuando el usuario cierra esta ventana, la conexión falla con el siguiente error [!DNL Fusion]:

“[!UICONTROL Error: la solicitud falló debido al error de una solicitud anterior. No se especificó ningún token de acceso]”.

_Notificado por primera vez el 21 de noviembre de 2022._
