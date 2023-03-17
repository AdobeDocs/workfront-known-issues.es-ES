---
title: '“Formularios personalizados: no se puede utilizar el campo en el cálculo si su nombre contiene comillas o un apóstrofo”'
description: “Cuando un usuario crea una expresión de campo calculado e intenta incluir un campo de escritura anticipada que tiene un nombre con un apóstrofo o comillas, el cálculo no se acepta y el usuario ve el mensaje ‘La expresión personalizada no es válida, inténtelo de nuevo’”.
hidefromtoc: true
source-git-commit: 3307a9be28555d0b9561e8ae96e3667cb1fee711
workflow-type: ht
source-wordcount: '154'
ht-degree: 100%

---


# Formularios personalizados: no se puede utilizar el campo en el cálculo si su nombre contiene comillas o un apóstrofo

>[!NOTE]
>
>Este problema se corrigió el 2 de marzo de 2023.

Cuando un usuario crea una expresión de campo calculado e intenta incluir un campo de escritura anticipada que tiene un nombre con un `'` o `"`, el cálculo no se acepta y el usuario ve el mensaje “[!UICONTROL La expresión personalizada no es válida, inténtelo de nuevo]”.

Este problema solo existe con los campos de escritura anticipada. Se pueden utilizar campos de texto con `'` o `"` en el nombre en expresiones de campo calculado sin problemas.

_Notificado por primera vez el 10 de noviembre de 2022._

