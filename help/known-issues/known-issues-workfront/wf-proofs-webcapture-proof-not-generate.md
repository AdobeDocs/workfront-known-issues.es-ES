---
title: 'Pruebas: las pruebas de captura web no se generan'
description: Cuando un usuario intenta crear una prueba de captura web, la prueba no se genera correctamente.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: ht
source-wordcount: '98'
ht-degree: 100%

---

# Pruebas: las pruebas de captura web no se generan

>[!NOTE]
>
>Este problema se ha cerrado porque funciona como se diseñó. Consulte la siguiente solución.

Cuando un usuario intenta crear una prueba de captura web, la prueba no se genera correctamente.

**Solución alternativa**

Este problema se debe a los tiempos de generación de pruebas largos para ciertos archivos de PDF. Para aumentar el tiempo de espera de generación de los 30 segundos predeterminados, edite la siguiente propiedad en Configuración de procesamiento en el nivel de cuenta en Administración de pruebas:

`WebCaptureNavigationTimeout -> 120`

_Notificado por primera vez el viernes, 03 de octubre de 2024._
