---
title: '''Pruebas: Nueva etapa creada porque la fecha límite no puede coincidir con la fecha límite de la etapa existente'
description: Cuando se crea una prueba nueva, la fecha límite se puede establecer en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se agrega un usuario a una prueba después de haberla creado, la fecha límite solo se puede establecer en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 0%

---

# Pruebas: Nueva etapa creada porque la fecha límite no puede coincidir con la fecha límite de la etapa existente

>[!NOTE]
>
>Este problema se ha corregido.

Cuando se crea una prueba nueva, la fecha límite se puede establecer en un incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). Sin embargo, cuando se agrega un usuario a una prueba después de haberla creado, la fecha límite solo se puede establecer en incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Por lo tanto, el nuevo usuario no se puede agregar a una etapa con una fecha límite que termine en :15 o :45, ya que no se pueden establecer coincidencias con los plazos. En su lugar, el nuevo usuario se añade a una nueva etapa, con una fecha límite establecida en incrementos de 30 minutos.

**Solución alternativa**:

* Si selecciona una fecha límite para una prueba nueva, establezca la fecha límite en una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
* Si la fecha límite se establece automáticamente en el momento de la creación de la prueba, establezca manualmente la fecha límite de la prueba en una hora que termine en :00 o :30 (10:00, 10:30, 11:00, etc.).
