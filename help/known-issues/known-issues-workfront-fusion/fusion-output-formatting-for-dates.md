---
title: 'Workfront Fusion: formato de salida para fechas'
description: Cuando las fechas se muestran como cadenas, la fecha puede mostrarse como una cadena UTC o ISO. Esto depende de la lógica dentro de un panel de asignación.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion: formato de salida para fechas

Cuando las fechas se muestran como cadenas, la fecha puede mostrarse como una cadena UTC o ISO. Esto depende de la lógica dentro de un panel de asignación:

* Si una fecha dentro de una función se une a una cadena, la cadena se generará en formato **UTC**.
* Si la fecha no está unida dentro de una función, se genera como una **Cadena ISO**.

Los clientes deben utilizar las funciones `toString` (para ISO) o `formatDate` para garantizar que los resultados están en el formato que necesitan.
