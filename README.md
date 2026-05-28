# Sistema Inteligente de Soporte Técnico con IA - Grupo 1

Repositorio académico estructurado para la documentación del proyecto **Sistema Inteligente de Soporte Técnico con IA**, orientado a transformar el soporte técnico de un modelo reactivo a un modelo preventivo mediante análisis de datos, Machine Learning, generación de alertas tempranas y visualización de métricas en tiempo real.

## 1. Descripción del proyecto

El proyecto consiste en el diseño de un sistema inteligente capaz de recolectar datos operativos, analizar patrones, detectar anomalías y predecir posibles fallos tecnológicos antes de que ocurran.

El sistema contempla un dashboard web, API backend, motor de Inteligencia Artificial, base de datos, integraciones externas y módulo de notificaciones para apoyar la toma de decisiones del equipo de soporte técnico.

## 2. Objetivo general

Diseñar y documentar un sistema inteligente de soporte técnico basado en Inteligencia Artificial que permita anticipar fallos tecnológicos, generar alertas tempranas y apoyar la toma de decisiones del equipo de soporte técnico.

## 3. Alcance del repositorio

Este repositorio contiene los artefactos principales del proyecto:

* Gestión del proyecto.
* Requerimientos funcionales y no funcionales.
* Casos de uso e historias de usuario.
* Arquitectura As-Is, To-Be y modelo C4.
* Decisiones de arquitectura ADR.
* Gestión de riesgos.
* Aseguramiento de calidad.
* Documentación base y presentación del proyecto.

## 4. Estructura del repositorio

```text
sistema-inteligente-soporte-tecnico-ia-grupo-1/
├── README.md
├── 01-gestion-proyecto/
├── 02-requerimientos/
├── 03-arquitectura/
├── 04-riesgos/
├── 05-calidad/
└── presentacion/
```

## 5. Descripción de carpetas

### 01-gestion-proyecto

Contiene el acta de constitución del proyecto, objetivos SMART, alcance, cronograma, matriz de interesados y plan de gestión del proyecto.

### 02-requerimientos

Contiene el documento de requerimientos funcionales, requerimientos no funcionales clasificados, casos de uso, historias de usuario y matriz de trazabilidad.

### 03-arquitectura

Contiene la documentación arquitectónica del sistema, incluyendo diagramas de flujo As-Is y To-Be, contexto C1, contenedores C2, componentes C3 y decisiones de diseño ADR.

### 04-riesgos

Contiene la matriz de riesgos del proyecto, identificación, probabilidad, impacto, nivel de riesgo, planes de mitigación y registro de seguimiento.

### 05-calidad

Contiene el plan de aseguramiento de calidad, criterios de aceptación del sistema, lista de verificación de artefactos, métricas de calidad y estrategia de pruebas.

### presentacion

Contiene la presentación del proyecto para exposición académica.

## 6. Integrantes

* Carlos Daniel Quintero Forero
* Sofía Salgado Osorio
* Mariana Duarte Castro
* María Fernanda Valencia Noreña
* José Stiven Rodas Beltrán
* Gerónimo Valencia González

## 7. Tecnologías propuestas

* **Frontend:** React.js
* **Backend:** Python FastAPI / Node.js
* **Inteligencia Artificial:** Python, scikit-learn, TensorFlow
* **Base de datos:** PostgreSQL / MongoDB
* **Notificaciones:** Email, Slack, mensajería
* **Integraciones:** Sistemas de monitoreo e ITSM

## 8. Criterios generales de aceptación

* El sistema debe recolectar datos de múltiples fuentes.
* El modelo predictivo debe alcanzar mínimo 70% en Accuracy, Recall y F1-Score.
* Las alertas deben generarse en un tiempo máximo de 5 segundos después de la detección.
* El dashboard debe visualizar métricas, alertas e historial de incidentes.
* La API debe responder en promedio en menos de 500 ms.
* El sistema debe cumplir criterios de seguridad, disponibilidad, escalabilidad y trazabilidad.

## 9. Estado del repositorio

Repositorio organizado para entrega académica. Los documentos principales se almacenarán en formato `.pdf`.
