---
title: 'Pruebas: se ha creado una nueva etapa porque el plazo no puede coincidir con el de la etapa existente'
description: Cuando se crea una nueva prueba, el plazo puede fijarse en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se añade un usuario a una prueba después de crearla, el plazo solo puede fijarse en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
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
source-wordcount: '243'
ht-degree: 64%
---
# Pruebas: se ha creado una nueva etapa porque el plazo no puede coincidir con el de la etapa existente

<!--Requested article-->

Cuando se crea una nueva prueba, el plazo puede fijarse en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se añade un usuario a una prueba después de crearla, el plazo solo puede fijarse en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Por lo tanto, no se puede añadir al nuevo usuario a una fase con un plazo que termine en :15 o :45, porque los plazos no pueden coincidir. En su lugar, el nuevo usuario se debe añadir a una nueva etapa, con un plazo establecido en incrementos de 30 minutos.

**Solución alternativa**:

* Si selecciona una fecha límite para una nueva prueba, establézcala a una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
* Si el plazo se establece automáticamente en el momento de la creación de la prueba, establezca manualmente el plazo de la prueba a una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
