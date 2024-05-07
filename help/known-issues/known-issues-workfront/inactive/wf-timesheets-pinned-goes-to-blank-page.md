---
title: "Plantillas de horas: la plantilla de horas anclada pasa a una página en blanco"
description: '"Cuando un usuario hace clic en un fijador de Workfront que va a su plantilla de horas, el fijador va a una página en blanco. Hay una solución disponible”.'
hidefromtoc: true
feature: Timesheets
source-git-commit: d3068f21ba6e1a9a1dd4a9ed78da43cef88f4fde
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 7%

---


# Plantillas de horas: la plantilla de horas anclada pasa a una página en blanco

Cuando un usuario hace clic en un fijador de Workfront que va a su plantilla de horas, el fijador va a una página en blanco.

Esto se debe a que la dirección URL de la plantilla de horas ha cambiado. el `/own` al final de la dirección URL ya no es la dirección URL correcta. Si el usuario ha anclado una URL que incluya `/own`, ese pin lleva a una página en blanco.

**Solución alternativa**

1. Desanclar la hoja de horas.
1. Eliminar `/own` desde el final de la dirección URL
1. Vuelva a anclar la hoja de horas.

_Informado por primera vez el miércoles, 07 de mayo de 2024._
