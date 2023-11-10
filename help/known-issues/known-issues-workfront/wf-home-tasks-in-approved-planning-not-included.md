---
title: '“Inicio: las tareas de los proyectos con estado Aprobado o Planificación no se incluyen en Mis tareas o en la Lista de trabajos en el Inicio”'
description: “Las tareas de los proyectos que tienen el estado Aprobado o Planificación no se muestran en Inicio. Hay una solución disponible”.
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: ht
source-wordcount: '166'
ht-degree: 100%

---


# Inicio: las tareas de los proyectos con estado Aprobado o Planificación no se incluyen en Mis tareas o en la Lista de trabajos en el Inicio

Las tareas de los proyectos que tienen el estado Aprobado o Planificación no se muestran en las siguientes áreas:

* Inicio clásico: Lista de trabajos
* Nueva página de inicio: widget Mis tareas

Esto se debe a que las tareas de los proyectos con estos estados están incluidas actualmente en el límite de consultas de 2000 elementos, pero no se muestran en Mis tareas ni en la Lista de trabajos en el Inicio. Esto puede crear una situación en la que un usuario que tenga menos de 2000 tareas, éstas no sean visibles.

**Solución alternativa**

Cree un informe de Asignaciones personalizado que incluya los siguientes filtros de modo de texto:

Cuando la asignación sea WAITING_ACCEPTANCE, incluya los proyectos CURRENT|APPROVED:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Cuando la asignación sea ACCEPTED, incluya los proyectos CURRENT|APPROVED|PLANNING:

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_Notificado por primera vez el 6 de noviembre de 2023._
