---
title: 'Permisos: los permisos de objeto no se heredan correctamente'
description: Los permisos heredados no se aplican correctamente a los objetos. Esto puede ocurrir debido a la complejidad de los permisos heredados.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# Permisos: los permisos de objeto no se heredan correctamente

>[!NOTE]
>
>El equipo de productos está evaluando actualmente la resolución de este problema, que podría requerir mejoras en el producto. Las mejoras del producto no se comunican en las actualizaciones de mantenimiento, sino en los anuncios del producto.

Los permisos heredados no se aplican correctamente a los objetos. Esto puede ocurrir debido a la complejidad de los permisos heredados, que pueden verse afectados por lo siguiente:

* El objeto se comparte con un gran número de personas.
* Un gran número de objetos se ve afectado por un cambio de permisos heredado.

**Solución**

Limitar el tamaño o la complejidad de los objetos puede evitar este problema. Se recomienda no tener más de 10 000 objetos secundarios bajo ningún objeto principal.

_Notificado por primera vez el 21 de marzo de 2025._
