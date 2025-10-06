---
title: 'Integraciones: error de outlookIdentityToken al usar Workfront para Outlook'
description: Cuando un usuario utiliza la integración de Workfront para Outlook, puede que vea un error.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# Integraciones: error de outlookIdentityToken al usar Workfront para Outlook

>[!NOTE]
>
>La integración de Workfront para Outlook ya no está disponible. Este artículo se eliminará en un futuro próximo.

Cuando un usuario utiliza la integración de Workfront para Outlook, puede que vea el siguiente error:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Solución**


Para resolver este error, debe habilitar los tókenes heredados de Microsoft 365 para su organización. Como esto debe hacerse en Microsoft 365, Workfront no puede habilitar estos tókenes para su organización.

Para obtener instrucciones sobre cómo habilitar los tókenes heredados de Microsoft 365, consulte [Activar o desactivar los tokens heredados de Exchange Online](https://learn.microsoft.com/es-es/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) en la documentación de Microsoft.

Para obtener más información sobre los tókenes heredados, consulte [¿Puedo volver a activar los tókenes heredados de Exchange Online?](https://learn.microsoft.com/es-es/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) en la documentación de Microsoft.


_Notificado por primera vez el 3 de marzo de 2025._
