---
title: "Pruebas: se ha creado una nueva etapa porque el plazo no puede coincidir con el de la etapa existente"
description: Cuando se crea una nueva prueba, el plazo puede fijarse en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se añade un usuario a una prueba después de crearla, el plazo solo puede fijarse en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: ht
source-wordcount: '197'
ht-degree: 100%

---

# Pruebas: se ha creado una nueva etapa porque el plazo no puede coincidir con el de la etapa existente

>[!NOTE]
>
>Este problema se ha solucionado.

Cuando se crea una nueva prueba, el plazo puede fijarse en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se añade un usuario a una prueba después de crearla, el plazo solo puede fijarse en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Por lo tanto, no se puede añadir al nuevo usuario a una etapa con un plazo que termine en :15 o :45, porque los plazos no pueden coincidir. En su lugar, el nuevo usuario se debe añadir a una nueva etapa, con un plazo establecido en incrementos de 30 minutos.

**Solución alternativa**:

* Si selecciona una fecha límite para una nueva prueba, establézcala a una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
* Si la fecha límite se establece automáticamente en el momento de la creación de la prueba, establezca manualmente la fecha límite de la prueba a una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
