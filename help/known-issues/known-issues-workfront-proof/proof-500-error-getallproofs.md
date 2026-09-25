---
title: 'Workfront Proof: Error 500 al acceder a Workfront Proof a través de API o Workfront Fusion'
description: 'Cuando un usuario accede a la acción getAllProofs de la API de prueba, el servidor de Workfront Proof devuelve el mensaje: 500 Internal Server Error'
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 69%
---
# [!DNL Workfront Proof]: Error 500 al acceder a [!DNL Workfront Proof] mediante API o [!DNL Workfront Fusion]

>[!NOTE]
>
>El equipo de productos está evaluando actualmente la resolución de este problema, que podría requerir mejoras en el producto. Las mejoras del producto no se comunican en las actualizaciones de mantenimiento, sino en los anuncios del producto.

<!--This article is on Proof and Fusion TOCs-->

Cuando un usuario accede a la acción [!UICONTROL `getAllProofs`] de la API [!DNL Workfront Proof], el servidor devolverá el siguiente mensaje:

[!UICONTROL Error de servidor interno 500]

Porque [!DNL Workfront Fusion] utiliza la API [!DNL Workfront Proof] para los módulos [!DNL Workfront Proof], este error puede devolverse a un módulo, deteniendo un escenario.

_Informado por primera vez el sábado, 28 de abril de 2023._
