---
title: 'Integraciones: error de outlookIdentityToken al usar Workfront para Outlook'
description: Cuando un usuario utiliza la integración de Workfront para Outlook, puede que vea un error.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Integraciones: error de outlookIdentityToken al usar Workfront para Outlook

Cuando un usuario utiliza la integración de Workfront para Outlook, puede que vea el siguiente error:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Solución**


Para resolver este error, debe habilitar los tokens heredados de Microsoft 365 para su organización. Como esto debe hacerse en Microsoft 365, Workfront no puede habilitar estos tokens para su organización.

Para obtener instrucciones sobre cómo habilitar tokens heredados de Microsoft 365, consulte [Activar o desactivar tokens heredados de Exchange Online](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) en la documentación de Microsoft.

Para obtener más información sobre tokens heredados, consulte [¿Puedo volver a activar los tokens heredados de Exchange Online?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) en la documentación de Microsoft.


_Notificado por primera vez el 3 de marzo de 2025, 2024._
