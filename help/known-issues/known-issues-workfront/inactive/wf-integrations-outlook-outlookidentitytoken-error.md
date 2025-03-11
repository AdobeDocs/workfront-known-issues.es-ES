---
title: 'Integraciones: error de outlookIdentityToken al usar Workfront para Outlook'
description: Cuando un usuario utiliza la integración de Workfront para Outlook, puede que vea un error.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: fff5428fd0c9a50f20ded044bf0ab251dfde5a6e
workflow-type: ht
source-wordcount: '127'
ht-degree: 100%

---

# Integraciones: error de outlookIdentityToken al usar Workfront para Outlook

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
