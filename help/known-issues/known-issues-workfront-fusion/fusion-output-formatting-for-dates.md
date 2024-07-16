---
title: "Workfront Fusion: Formato de salida para fechas"
description: Cuando las fechas se muestran como cadenas, la fecha puede mostrarse como una cadena UTC o ISO. Esto depende de la lógica dentro de un panel de asignación.
hidefromtoc: true
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 7aba3a4ce3e0436a8fd9850197bc44da9dafe347
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 87%

---

# Workfront Fusion: formato de salida para fechas

Cuando las fechas se muestran como cadenas, la fecha puede mostrarse como una cadena UTC o ISO. Esto depende de la lógica dentro de un panel de asignación:

* Si una fecha dentro de una función se une a una cadena, la cadena se generará en formato **UTC**.
* Si la fecha no está unida dentro de una función, se genera como una **Cadena ISO**.

Los clientes deben utilizar las funciones `toString` (para ISO) o `formatDate` para garantizar que los resultados están en el formato que necesitan.
