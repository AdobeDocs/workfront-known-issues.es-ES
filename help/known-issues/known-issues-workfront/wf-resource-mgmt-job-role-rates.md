---
title: "Administración de recursos: cálculos financieros incorrectos debido a problemas de función"
description: '"Los cálculos de horas y finanzas pueden ser incorrectos y mostrar un coste de 0 aunque las horas se registren en una función que tenga una tasa de coste".'
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 100%

---


# Administración de recursos: cálculos financieros incorrectos debido a problemas de función

>[!NOTE]
>
>Este problema se corrigió el viernes, 08 de febrero de 2024.

Los cálculos de horas y finanzas pueden ser incorrectos y mostrar un coste de 0 aunque las horas se registren en una función que tenga una tasa de coste.

Esto se debe a que las funciones están creando automáticamente tasas duplicadas sin fechas de inicio o finalización. Como no tienen fechas de inicio o finalización, se tratan como un valor de 0 cuando se ejecutan los cálculos financieros.

**Solución alternativa**

1. Asegúrese de que se hayan guardado los datos anteriores correctos.
1. Elimine las tasas duplicadas sin fechas de inicio o finalización.
1. Vuelva a calcular las finanzas.

_Notificado por primera vez el 18 de enero de 2023._
