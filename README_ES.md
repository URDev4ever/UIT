<h1 align="center">Plantilla Definitiva de Inyección de URDev</h1>

<h3 align="center">La Plantilla Definitiva de Inyección de URDev es mi colección personal de payloads: una colección de referencia integral de vectores de inyección web, enfocada principalmente en superficies de ejecución del lado del cliente en aplicaciones web modernas y heredadas.</h3>

<p align="center">
  🇺🇸 <a href="README.md"><b>English</b></a> |
  🇪🇸 <b>Español</b>
</p>

---

Este repositorio **no es un escáner automatizado** ni una lista de payloads de “usar y olvidar”.
Está pensado para ser utilizado como una **referencia de testing manual**, galería de payloads y banco de ideas durante evaluaciones de seguridad en aplicaciones web y en investigaciones de bug bounty.

## Qué es esto

* Una colección curada de **vectores de inyección y superficies de ejecución**
* Enfocada principalmente en **XSS, ejecución basada en DOM y abuso del navegador**
* Diseñada para **testing manual, análisis y experimentación**
* Útil al explorar **casos límite, contextos inusuales o el comportamiento de WAFs**

## Qué NO es esto

* ❌ No es un framework de explotación
* ❌ No es un buscador automático de vulnerabilidades
* ❌ No está garantizado que funcione en objetivos modernos y endurecidos
* ❌ No está pensado para pegar payloads a ciegas en sistemas en producción

## Alcance

La plantilla cubre una amplia variedad de contextos del lado del cliente, incluyendo pero no limitándose a:

* Contextos de inyección en HTML y atributos
* Sinks de ejecución basados en DOM
* Vectores basados en SVG, MathML, XML y namespaces
* Abuso de manejadores de eventos
* Técnicas de codificación, ofuscación y confusión del parser
* APIs del navegador, funcionalidades legacy y superficies de ejecución poco comunes

La mayoría de los payloads son **ejemplos contextuales**, pensados para ser adaptados y no utilizados de forma literal.

## Público objetivo

* Investigadores de seguridad web
* Bug bounty hunters
* Pentesters que realizan **análisis manual**
* Cualquiera interesado en entender **cómo los navegadores interpretan y ejecutan input no confiable**

## Filosofía

> Cobertura sobre automatización. Comprensión sobre repetición.

Este proyecto prioriza la **amplitud de superficies de ejecución** por sobre la confiabilidad de explotación.
Está pensado para ayudar a responder la pregunta:
**“¿Qué caminos de ejecución son siquiera posibles en este contexto?”**

---

## Contribuir

Las pull requests son bienvenidas si:

* Agregan nuevos **contextos de ejecución, vectores de inyección o comportamientos del navegador** que aún no estén documentados
* Mejoran la **organización de payloads, legibilidad o explicaciones contextuales**
* Aportan **valor educativo**, ayudando a entender cómo los navegadores interpretan y ejecutan input no confiable
* Mantienen la filosofía del proyecto: **referencia para investigación manual, no explotación automatizada**

---

## Disclaimer

Este repositorio se provee **únicamente con fines educativos y para testing de seguridad autorizado**.
No utilices estos payloads en sistemas que no sean tuyos o para los que no tengas permiso explícito de prueba.

---

Puede que en el futuro se agregue una organización más estructurada y galerías contextuales.
Haré lo posible por seguir actualizando esto para vos y para mí ;)

---

Hecho con <3 por URDev.
