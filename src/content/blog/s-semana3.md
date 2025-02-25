---
title: 'Semana 3: Riesgos en el Software'
description: ''
pubDate: 2025-02-24T22:00:00.000Z
heroImage: ../../assets/images/gestion_de_riesgos.jpg
category: Software
tags:
  - clase
---

# 📌 Proceso de Control de Cambios y Gestión de Riesgos en Ingeniería de Software

Estos dos procesos son esenciales en el desarrollo de software para garantizar la estabilidad del proyecto, minimizar impactos negativos y facilitar la toma de decisiones.

---

## **1. Control de Cambios**

El **control de cambios** en ingeniería de software permite gestionar modificaciones en el código, requisitos, arquitectura o documentación del proyecto de manera ordenada y sin afectar la estabilidad del sistema.

### **Pasos en el Proceso de Control de Cambios**

1. **Identificación del cambio**:
   - Un usuario, desarrollador o cliente solicita una modificación en el sistema.
2. **Registro del cambio**:
   - Se documenta la solicitud en un sistema de control de versiones (Git, Jira, etc.).
3. **Evaluación del impacto**:
   - Se analiza cómo el cambio afectará el código, el rendimiento, la seguridad y la arquitectura del software.
4. **Toma de decisión**:
   - El equipo de desarrollo y el comité de control de cambios (_Change Control Board_, CCB) revisan la solicitud y la aprueban o rechazan.
5. **Implementación del cambio**:
   - Se desarrolla, prueba e integra el cambio en el software.
6. **Seguimiento y verificación**:
   - Se monitorea el software para asegurarse de que el cambio no cause nuevos problemas.

> **Ejemplo práctico:**  
> Un cliente solicita modificar el proceso de autenticación para incluir autenticación en dos pasos. Se evalúa el impacto en seguridad y usabilidad, se desarrolla en una rama separada y, tras pruebas exitosas, se fusiona con la versión estable del sistema.

---

## **2. Gestión de Riesgos en Ingeniería de Software**

La **gestión de riesgos en software** se enfoca en identificar y mitigar problemas que pueden afectar el desarrollo, la calidad o la entrega del producto.

### **Tipos de Riesgos en Ingeniería de Software**

| **Categoría**        | **Ejemplo de Riesgo**                                           |
| -------------------- | --------------------------------------------------------------- |
| **Técnicos**         | Uso de tecnología inestable o desactualizada.                   |
| **Requerimientos**   | Cambios constantes en los requisitos del cliente.               |
| **Seguridad**        | Vulnerabilidades en la autenticación del sistema.               |
| **Rendimiento**      | El software no escala adecuadamente con el tráfico de usuarios. |
| **Recursos Humanos** | Falta de programadores con habilidades clave.                   |
| **Plazos y Costos**  | Retrasos en entregas por mala planificación.                    |

### **Pasos en la Gestión de Riesgos en Software**

1. **Identificación de riesgos**: Se detectan problemas potenciales en el desarrollo.
2. **Análisis de riesgos**: Se determina su probabilidad e impacto.
   - **Cualitativo**: Se clasifica como bajo, medio o alto.
   - **Cuantitativo**: Se mide con datos históricos y modelos de predicción.
3. **Planificación de respuestas**: Se establecen estrategias para:
   - **Mitigar** (reducir el impacto del riesgo).
   - **Evitar** (cambiar aspectos del proyecto para prevenirlo).
   - **Transferir** (delegarlo a un tercero, como un proveedor).
   - **Aceptar** (asumirlo si el costo de mitigación es mayor que el impacto).
4. **Monitoreo y control**: Se revisan continuamente los riesgos y se ajustan las estrategias.

> **Ejemplo práctico:**  
> Se detecta el riesgo de que una API externa no sea confiable. Se mitiga creando una capa de abstracción que permita cambiar la API sin afectar el código principal.

---

## **📌 Relación entre Control de Cambios y Gestión de Riesgos en Software**

- **Un cambio en el software puede introducir nuevos riesgos**  
  _(Ejemplo: Un cambio en la base de datos puede causar incompatibilidad con versiones anteriores)._
- **Un riesgo identificado puede generar la necesidad de un cambio**  
  _(Ejemplo: Detectar una vulnerabilidad de seguridad obliga a realizar una actualización de emergencia)._

Ambos procesos deben trabajarse juntos para garantizar que el software **sea estable, seguro y escalable**. 🚀
