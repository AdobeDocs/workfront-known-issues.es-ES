---
title: 'Plantillas de horas: la plantilla de horas anclada pasa a una página en blanco'
description: Cuando un usuario hace clic en un anclaje de Workfront que debe llevarle a su plantilla de horas, el anclaje le lleva a una página en blanco. Hay una solución disponible.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
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
