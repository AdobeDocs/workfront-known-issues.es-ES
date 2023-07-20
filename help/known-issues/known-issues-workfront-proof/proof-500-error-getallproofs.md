---
title: "Workfront Proof: Error 500 al acceder a Workfront Proof a través de API o Workfront Fusion"
description: "Cuando un usuario accede a la acción getAllProofs de la API Proof, el servidor Workfront Proof devuelve el mensaje: 500 Internal Server Error"
hidefromtoc: true
feature: Workfront Proof
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 100%

---


# [!DNL Workfront Proof]: Error 500 al acceder a [!DNL Workfront Proof] mediante API o [!DNL Workfront Fusion]

>[!NOTE]
>
>El equipo de productos está evaluando actualmente la resolución de este problema, que podría requerir mejoras en el producto. Las mejoras del producto no se comunican en las actualizaciones de mantenimiento, sino en los anuncios del producto.

<!--This article is on Proof and Fusion TOCs-->

Cuando un usuario accede a la acción [!UICONTROL `getAllProofs`] de la API [!DNL Workfront Proof], el servidor devolverá el siguiente mensaje:

[!UICONTROL Error de servidor interno 500]

Porque [!DNL Workfront Fusion] utiliza la API [!DNL Workfront Proof] para los módulos [!DNL Workfront Proof], este error puede devolverse a un módulo, deteniendo un escenario.

_Notificado por primera vez el 28 de abril de 2023._

