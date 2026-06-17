# Toolkit Unidad 2 FVIE01: Innovación y Emprendimiento I

**UNIDAD 2:** “MODELO DE NEGOCIOS Y EXPERIMENTACIÓN”  
**Proyecto:** SeniorClick — Capa de Accesibilidad Cognitiva Bancaria  

---

## 🎯 Desafío de Innovación
> **¿Cómo podríamos implementar interfaces más amigables y entendibles para usuarios mayores de 60 años garantizando mejoras en el porcentaje de aumento de la usabilidad de tecnologías de la información?**

---

## 🛠 Recurso 2.1: Plantilla de BMC V1 (Modelo de Negocios Canvas)

* **Nombre empresa:** SeniorClick
* **Diseñado para:** Personas mayores de 60 años y entidades financieras/públicas.
* **Diseñado por:** Equipo Emprendedor (Asignatura Innovación y Emprendimiento I)
* **Fecha:** Junio 2026
* **Versión:** 1

| Socios Claves | Actividades Claves | Propuesta de Valor | Relación con Clientes | Segmento de Clientes |
| :--- | :--- | :--- | :--- | :--- |
| • Municipalidades y Chile Atiende.<br>• Bancos y entidades financieras.<br>• Empresas tecnológicas.<br>• Familias y cuidadores.<br>• Organizaciones de adultos mayores. | • **Desarrollo e Inyección de Código (Front-end):** Programación y optimización de scripts (JavaScript/CSS) seguros y ligeros.<br>• **Diseño Inclusivo:** Adaptación cognitiva bajo normas WCAG 2.1 AA. | • Integración nativa sin descargas externas.<br>• Interfaz amigable, limpia y libre de distractores.<br>• Doble confirmación visual para mitigar el miedo al error.<br>• Notificación automática a "Tutor Financiero". | • Relación institucional y B2B (con el banco).<br>• Asistencia automatizada y empática dentro del flujo transaccional. | **B2B (Quién Paga):**<br>Instituciones financieras y servicios públicos obligados por ley de inclusión.<br><br>**B2C (Quién Usa):**<br>Personas mayores de 60 años que buscan autonomía digital. |
| **Recursos Claves** | | **Canales** | | |
| • Desarrolladores UX/UI Senior.<br>• Servidores web seguros para inyección de la capa. | | • Portales web oficiales de las instituciones bancarias.<br>• Sitios gubernamentales. | | |
| **Estructura de Costos** | | **Fuentes de Ingresos** | | |
| • Sueldos de equipo técnico y de diseño cognitivo.<br>• Auditorías de accesibilidad y ciberseguridad. | | • Suscripción SaaS (Software as a Service) corporativa pagada por el banco.<br>• Cobro por integración (setup fee). | | |

---

## 🧪 Recurso 2.2: Modelo de Experimentación

Para validar la hipótesis principal, se diseñó una maqueta interactiva funcional (Front-end 100% responsivo) de la propuesta **SeniorClick**.

* **Hipótesis a validar:** Los usuarios mayores de 60 años pueden realizar una transferencia bancaria de manera autónoma si la interfaz de su banco actualiza su diseño para eliminar el "ruido visual" y se agregan validaciones amigables (ej: autorización de Tutor Financiero).
* **Mecanismo de experimentación:** Simulación en entorno web (HTML/CSS/JS) donde el usuario activa el modo "SeniorClick" y navega por el flujo de transferencia y agregar un nuevo destinatario (con validación de SMS).
* **Métrica de éxito:** Aumento en el porcentaje de usabilidad (finalización exitosa del flujo sin requerir ayuda presencial) y disminución de la fricción tecnológica.

---

## 📊 Recurso 2.3: Test Card (Resultados e Insights)

* **¿Qué medimos?** 
  El nivel de confianza y el porcentaje de finalización exitosa de los usuarios al utilizar el flujo simulado con colores institucionales adaptativos (BancoEstado, Santander, Falabella, Chile).
* **Resultados Obtenidos:**
  1. La inyección nativa del botón de activación dentro del portal del banco generó **confianza inmediata** (elimina el miedo a instalar extensiones fraudulentas).
  2. La función del **Tutor Financiero** (envío de código SMS a un tercero de confianza) disminuyó drásticamente el "miedo a equivocarse".
  3. Al ser la interfaz 100% responsiva, los usuarios pudieron leer los números y textos enormes desde sus celulares sin hacer "zoom".
* **Insight Principal:**
  El adulto mayor no rechaza la tecnología; rechaza las interfaces mal diseñadas que los penalizan por equivocarse. SeniorClick demuestra que una capa cognitiva inyectada directamente en la web soluciona la usabilidad sin forzarlos a "aprender" un sistema completamente nuevo.

---

## 🔄 Recurso 2.4: BMC Versión 2 (Ajustado)

Tras el proceso de experimentación, el modelo original de negocios se refina en su estructura de costos y alianzas:

* **Nuevos Socios Claves:** Consultoras de Ciberseguridad y Entidades Certificadoras de Accesibilidad (W3C/WCAG) para garantizar a los bancos que la inyección de código es segura.
* **Ajuste en Propuesta de Valor:** Ahora el foco B2B incluye ayudar a las entidades a **cumplir con normativas legales obligatorias** sobre accesibilidad digital (Ley de Inclusión, Decreto Supremo N° 1).
* **Viabilidad Demostrada:** El proyecto es altamente escalable ya que el código es transversal (se adapta a los colores de cada banco automáticamente mediante variables CSS) y no toca el core bancario (solo opera sobre la capa visual del cliente o Front-end).

---

> **Repositorio Oficial:** Los últimos cambios responsivos, adaptativos a marca, y de accesibilidad normativa se encuentran en la rama `main`.
