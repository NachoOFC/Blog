---
title: "SMTR: construyendo un sistema de monitoreo eléctrico en tiempo real"
datePublished: Tue Jan 06 2026 01:48:44 GMT+0000 (Coordinated Universal Time)
cuid: cmk1xkvrk000c02l41znocpfw
slug: smtr-construyendo-un-sistema-de-monitoreo-electrico-en-tiempo-real
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1767663917925/aa58ba32-99de-460a-a58c-28b08cc83011.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1767664038859/698a2296-a4be-438d-92f3-19e20086cbb5.png
tags: software-development, python, firebase, web-development, software-engineering, studentprojects

---

![ACCESO DE PRUEBA ](https://cdn.hashnode.com/res/hashnode/image/upload/v1767664093785/68864d49-2f45-4940-af1a-b0430ce156cc.png align="left")

  
[https://smtr-web.netlify.app/login](https://smtr-web.netlify.app/login)  
Este proyecto nació en un contexto universitario, pero desde el inicio fue pensado como una solución aplicable a un escenario real. **SMTR (Sistema de Monitoreo en Tiempo Real)** busca abordar un problema común en muchas empresas eléctricas: la falta de información en tiempo real para anticipar fallas y tomar mejores decisiones técnicas.

Más que un trabajo académico, SMTR fue una experiencia completa de análisis, diseño y desarrollo de un sistema con múltiples componentes.

---

## El problema que queríamos resolver

En muchas instalaciones eléctricas, el mantenimiento se realiza de forma reactiva. Es decir, se actúa cuando el problema ya ocurrió. Esto genera:

* Fallas inesperadas
    
* Mayores costos de reparación
    
* Pérdida de tiempo y trazabilidad
    
* Poca información histórica para analizar tendencias
    

Además, gran parte de la gestión técnica se sigue realizando con planillas, documentos sueltos y registros manuales, lo que complica el seguimiento y la toma de decisiones.

---

## La idea detrás de SMTR

La propuesta fue crear un **sistema de monitoreo eléctrico en tiempo real**, capaz de:

* Visualizar el estado de los activos eléctricos
    
* Simular la recolección de datos como temperatura, consumo y vibraciones
    
* Generar alertas tempranas ante valores críticos
    
* Centralizar toda la información técnica en una plataforma digital
    

El foco principal fue **pasar de un mantenimiento reactivo a uno preventivo**, utilizando datos en tiempo real como base.

---

## Cómo está construido el sistema

SMTR se compone de dos grandes partes:

### Plataforma Web

La plataforma web funciona como centro de control. Desde ahí es posible:

* Visualizar dashboards con el estado de los activos
    
* Identificar rápidamente equipos en estado crítico o de precaución
    
* Revisar alertas activas y datos históricos
    

La interfaz fue pensada para ser clara, simple y fácil de usar, incluso para usuarios sin experiencia técnica avanzada.

### Aplicación móvil

La aplicación móvil está orientada a técnicos en terreno, permitiendo:

* Ver el estado de los activos en tiempo real
    
* Consultar información detallada de cada componente
    
* Registrar datos manuales de mantenimiento
    

Esto facilita el trabajo en terreno y mejora la trazabilidad de la información.

---

## Tecnologías utilizadas

Durante el desarrollo se trabajó con un stack moderno y realista:

* Frontend web: HTML, CSS, JavaScript y Vue.js
    
* Backend y simulación de datos: Python
    
* Base de datos y sincronización en tiempo real: Firebase
    
* Aplicación móvil: Android Studio con Java
    
* Despliegue: Netlify
    

La simulación de sensores fue clave para validar el funcionamiento del sistema sin necesidad de hardware físico.

---

## Lo más valioso del proyecto

Más allá del resultado final, SMTR dejó aprendizajes importantes:

* Diseñar pensando en el usuario final cambia completamente las decisiones técnicas
    
* Trabajar con datos en tiempo real implica considerar rendimiento y consistencia
    
* La metodología ágil permitió adaptarse a cambios y avanzar de forma iterativa
    
* Simular escenarios reales ayuda a validar ideas antes de implementarlas en producción
    

---

## Próximos pasos

Este artículo es solo el inicio. En los siguientes posts profundizaré en:

* La arquitectura del sistema
    
* El diseño de los dashboards y alertas
    
* Los errores cometidos y qué mejoraría hoy
    

SMTR representa una etapa de crecimiento como desarrollador y una base sólida para proyectos más grandes en el futuro.