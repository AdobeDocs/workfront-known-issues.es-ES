---
title: "Administración de recursos: cálculos financieros incorrectos debido a problemas de roles de trabajo"
description: '"Los cálculos de horas y finanzas pueden ser incorrectos y mostrar un coste de 0 aunque las horas se registren en un rol que tenga una tasa de coste".'
hidefromtoc: true
feature: Resource Management
source-git-commit: e9a7ff289e7c9fcc9c9ff13b7c4b5b554e303c11
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 3%

---


# Administración de recursos: cálculos financieros incorrectos debido a problemas de rol

Los cálculos de horas y finanzas pueden ser incorrectos y mostrar un coste de 0 aunque las horas se registren en un rol que tenga una tasa de coste.

Esto se debe a que los roles están creando automáticamente tasas duplicadas sin fechas de inicio o finalización. Como no tienen fechas de inicio o finalización, se tratan como un valor de 0 cuando se ejecutan los cálculos financieros.

**Solución alternativa**

1. Asegúrese de que se hayan guardado los datos correctos pasados.
1. Elimine las tasas duplicadas sin fechas de inicio o finalización.
1. Recalcular las finanzas.

_Notificado por primera vez el 18 de enero de 2023._
