---
title: 'Plantillas de horas: la plantilla de horas anclada pasa a una página en blanco'
description: Cuando un usuario hace clic en un anclaje de Workfront que debe llevarle a su plantilla de horas, el anclaje le lleva a una página en blanco. Hay una solución disponible.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%

---

# Plantillas de horas: la plantilla de horas anclada pasa a una página en blanco

<!--article live for workaround-->

Cuando un usuario hace clic en un anclaje de Workfront que debe llevarle a su plantilla de horas, el anclaje le lleva a una página en blanco.

Esto se debe a que la dirección URL de la plantilla de horas ha cambiado. El `/own` al final de la dirección URL ya no es la dirección URL correcta. Si el usuario ha anclado una URL que incluye `/own`, ese anclaje lleva a una página en blanco.

**Solución**

1. Desanclar la plantilla de horas.
1. Quitar `/own` del final de la dirección URL
1. Vuelva a anclar la plantilla de horas.

_Informado por primera vez el miércoles, 07 de mayo de 2024._
