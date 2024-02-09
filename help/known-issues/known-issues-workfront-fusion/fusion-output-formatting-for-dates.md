---
title: '“Workfront Fusion: formato de salida para fechas”'
description: “Cuando las fechas se muestran como cadenas, la fecha puede mostrarse como una cadena UTC o ISO. Esto depende de la lógica dentro de un panel de asignación”.
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---


# Workfront Fusion: formato de salida para fechas

Cuando las fechas se muestran como cadenas, la fecha puede mostrarse como una cadena UTC o ISO. Esto depende de la lógica dentro de un panel de asignación:

* Si una fecha dentro de una función se une a una cadena, la cadena se generará en formato **UTC**.
* Si la fecha no está unida dentro de una función, se genera como una **Cadena ISO**.

Los clientes deben utilizar las funciones `toString` (para ISO) o `formatDate` para garantizar que los resultados están en el formato que necesitan.
