---
title: 'Pruebas: se ha creado una nueva etapa porque el plazo no puede coincidir con el de la etapa existente'
description: Cuando se crea una nueva prueba, el plazo puede fijarse en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se añade un usuario a una prueba después de crearla, el plazo solo puede fijarse en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 44%

---

# Pruebas: se ha creado una nueva etapa porque el plazo no puede coincidir con el de la etapa existente

<!--Requested article-->

Cuando se crea una nueva prueba, el plazo puede establecerse en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se agrega un usuario a una prueba después de crearla, el plazo solo se puede establecer en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Por lo tanto, no se puede agregar al nuevo usuario a una etapa con un plazo que termine en :15 o :45, porque los plazos no pueden coincidir. En su lugar, el nuevo usuario se debe añadir a una nueva etapa, con un plazo establecido en incrementos de 30 minutos.

**Solución alternativa**:

* Si selecciona una fecha límite para una nueva prueba, establézcala a una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
* Si la fecha límite se establece automáticamente en el momento de la creación de la prueba, establezca manualmente la fecha límite de la prueba a una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
