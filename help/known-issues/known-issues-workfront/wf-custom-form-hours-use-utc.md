---
title: "Formularios personalizados: La función HOUR en los campos calculados utiliza UTC"
description: '"Cuando un campo calculado incluye la función HOUR, la función devuelve valores en función de UTC en lugar de la zona horaria esperada. Por lo tanto, cualquier cálculo basado en el valor HOUR es incorrecto".'
hidefromtoc: true
source-git-commit: a681d8afd4bcf1ddfccf192871442e63dae1b2c3
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 4%

---


# Formularios personalizados: [!UICONTROL HORA] función en campos calculados utiliza UTC

>[!NOTE]
>
>Este problema se corrigió el 3 de noviembre de 2022.

Cuando un campo calculado incluye la variable [!UICONTROL HORA] , la función devuelve valores basados en UTC en lugar del huso horario esperado. Por lo tanto, cualquier cálculo basado en el valor HOUR es incorrecto.

_Notificado por primera vez el 17 de octubre de 2022._

