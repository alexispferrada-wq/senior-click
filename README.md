# Informe Académico: Proyecto SeniorClick
**Asignatura:** Innovación y Emprendimiento I (FVIE01)  
**Proyecto:** SeniorClick — Capa de Accesibilidad Cognitiva Bancaria  

---

## 1. Contexto Inicial
En la era actual de transformación digital, los canales de atención presencial de las instituciones financieras y públicas se están reduciendo drásticamente, obligando a los usuarios a migrar hacia la banca en línea. Sin embargo, este proceso de digitalización acelerada ha dejado atrás a un segmento vulnerable: las **personas mayores de 60 años**. 

Este grupo se enfrenta a barreras cognitivas significativas: interfaces complejas llenas de distractores publicitarios, tipografías pequeñas, menús de navegación confusos y, sobre todo, un profundo **miedo al error financiero** (como transferir a un destinatario equivocado) y al fraude digital. La falta de herramientas adaptadas genera dependencia de familiares y aislamiento financiero, reduciendo la autonomía de la tercera edad.

---

## 2. Redefinición del Desafío + Idea de Solución

* **Redefinición del Desafío:** ¿Cómo podríamos facilitar que las personas mayores de 60 años realicen transferencias electrónicas de fondos (TEF) de manera 100% autónoma, segura y sin temor, reduciendo al mínimo la fricción de instalación de nuevas tecnologías?
* **Idea de Solución:** **SeniorClick**. Una capa de accesibilidad cognitiva integrada nativamente en los sitios web oficiales de bancos y servicios públicos. No requiere descargas, extensiones ni instalaciones por parte del usuario final; se activa mediante un llamativo botón de **un solo clic** incorporado en la cabecera del portal oficial. Al activarse, transforma la interfaz compleja en una pantalla limpia, con tipografía de alta visibilidad, asistencia paso a paso y pantallas de doble confirmación visual antes de realizar cualquier movimiento de dinero.

---

## 3. Modelo de Negocio (2.1 BMC, Versión 1)

| Socios Claves | Actividades Claves | Propuesta de Valor | Relación con Clientes | Segmento de Clientes |
| :--- | :--- | :--- | :--- | :--- |
| - Municipalidades y ChileAtiende.<br>- Bancos y entidades financieras.<br>- Hospitales y centros de salud.<br>- Empresas tecnológicas.<br>- Familias y cuidadores.<br>- Organizaciones de adultos mayores. | - Desarrollo e Inyección de Código (Front-end): JavaScript/CSS seguros y ligeros.<br>- Diseño UI/UX: Estándares de diseño cognitivo adaptados a la tercera edad. | - Función integrada de accesibilidad cognitiva (cero descargas).<br>- Interfaz limpia y simplificada con tipografía de alta visibilidad.<br>- Doble confirmación visual.<br>- Soporte contextual automatizado por voz. | - Confianza institucional (integración web nativa).<br>- Soporte automatizado en tiempo real dentro del flujo. | **Clientes Comerciales:**<br>- Instituciones financieras (bancos, cajas de compensación).<br>- Organismos públicos (ChileAtiende, IPS).<br>**Usuarios Finales:**<br>- Personas mayores de 60 años digitales. |
| **Recursos Claves** | | **Canales** | | |
| - Equipo de desarrollo e ingeniería.<br>- Servidores en la nube seguros. | | - Plataforma web.<br>- Municipios y centros comunitarios.<br>- Redes sociales.<br>- Convenios institucionales. | | |
| **Estructura de Costos** | | **Fuentes de Ingresos** | | |
| - Capital Humano Técnico (Sueldos).<br>- Seguridad y Certificaciones (auditorías externas). | | - Licenciamiento Corporativo: Suscripción mensual o anual (SaaS B2B) por uso, mantenimiento e integración. | | |

* **Factibilidad V1:** Evita mantener apps en App/Play Store o dar soporte a dispositivos fragmentados. Un script inyectado centralizadamente es más limpio y escalable.
* **Deseabilidad V1:** El adulto mayor recibe ayuda inmediata en el sitio oficial que ya conoce. La institución migra usuarios presenciales a digital de forma segura.
* **Viabilidad V1:** Financiado por contratos corporativos de alto valor bajo presupuestos de Responsabilidad Social Empresarial (RSE), inclusión legal y eficiencia operativa.

---

## 4. Proceso de Experimentación con Clientes/Usuarios

Para validar las hipótesis críticas del negocio, se diseñó un prototipo interactivo de alta fidelidad que simula la pantalla real de una sucursal bancaria. Este prototipo incluye el botón nativo **"Activar Modo SeniorClick"**, que al ser presionado limpia la interfaz y despliega un asistente de transferencia guiado en 4 pasos.

Se realizó un testeo con un grupo de adultos mayores de entre 63 y 74 años (Elena, Humberto, Gladys, Raúl, Pedro, Marta y Juan), aplicando un cuestionario de campo enfocado en evaluar la usabilidad, la confianza en el canal y la autonomía de uso.

---

## 5. 2.2 Modelo de Experimentación

* **Título del Experimento:** Validación de Usabilidad y Confianza de la Capa Nativa SeniorClick.
* **Bloque 1 (Propuesta de Valor):** Validar si una interfaz simplificada con doble confirmación visual mitiga el miedo al error financiero, permitiendo operar de forma autónoma.
* **Bloque 2 (Canales):** Comprobar si el usuario comprende cómo activar el servicio mediante el botón incorporado directamente en la web y si esto elimina la fricción de descargas externas.
* **Hipótesis 1:** Los adultos mayores de 60 años realizarán trámites digitales de forma autónoma si la interfaz reduce pasos complejos y ofrece mensajes claros.
* **Hipótesis 2:** Los usuarios prefieren un botón incorporado en la página oficial en lugar de instalar herramientas externas por su cuenta.
* **Método de Prototipado:** Maqueta interactiva HTML5/CSS/JS que simula un entorno real. Permite medir errores y la usabilidad cognitiva sin incurrir en costos de backend.

---

## 6. 2.3 Test Card (Resultados e Insights)

* **Métricas Medidas:**
  1. % de usuarios que completan la transacción de forma 100% independiente. (Meta: >= 70%)
  2. Nivel de confianza autopercibida al terminar (Escala 1 a 5). (Meta: >= 4/5)
  3. Comportamiento y reacción ante la activación nativa y la doble confirmación visual.
* **Resultados Obtenidos:**
  * **80% de los participantes** logró completar la transferencia de forma autónoma.
  * La doble confirmación visual generó un **alivio inmediato**, reduciendo drásticamente la ansiedad al hacer clic.
  * Los usuarios validaron que la integración nativa (sin descargas) les dio la tranquilidad de que **no se trataba de una estafa externa**.
* **Insights Clave:**
  La fricción tecnológica no se resuelve enseñando a los adultos mayores a instalar herramientas externas (lo cual genera pánico y bloqueos por contraseñas o falta de espacio), sino adaptando las plataformas corporativas desde el origen para que sean intuitivas y seguras por defecto.

---

## 7. Ajustes del Modelo de Negocio (2.4 BMC, Versión 2)

Tras analizar los resultados de la experimentación, hemos ajustado el modelo de negocio para optimizar la propuesta de valor y robustecer la viabilidad comercial.

| Socios Claves | Actividades Claves | Propuesta de Valor | Relación con Clientes | Segmento de Clientes |
| :--- | :--- | :--- | :--- | :--- |
| - Bancos comerciales y Cajas de compensación.<br>- ChileAtiende y municipalidades.<br>- **NUEVO:** Consultoras de Ciberseguridad.<br>- **NUEVO:** Certificadoras de Accesibilidad (W3C/WAI). | - Desarrollo de la capa UI/UX adaptable.<br>- Auditorías de código.<br>- **NUEVO:** Monitoreo activo de telemetría de errores cognitivos. | - Capa nativa de accesibilidad cognitiva sin descargas.<br>- Asistente de doble confirmación visual.<br>- **NUEVO:** Certificación de Cumplimiento Legal de Inclusión Financiera para el Banco. | - Confianza y seguridad institucional.<br>- Co-diseño continuo con juntas de vecinos y centros de adulto mayor. | **Clientes:** Bancos y Servicios Públicos obligados a cumplir leyes de inclusión digital.<br>**Usuarios:** Adultos mayores de 60 años y personas con discapacidad cognitiva leve. |
| **Recursos Claves** | | **Canales** | | |
| - Desarrolladores y Diseñadores UX Senior.<br>- **NUEVO:** Set de pruebas con usuarios reales (Juntas de vecinos de tercera edad). | | - Integración directa (Script B2B).<br>- Sitios oficiales bancarios e institucionales. | | |
| **Estructura de Costos** | | **Fuentes de Ingresos** | | |
| - Sueldos y servidores.<br>- Auditorías de ciberseguridad.<br>- **NUEVO:** Costos de certificación de accesibilidad y usabilidad cognitiva. | | - Cobro de licenciamiento anual (SaaS).<br>- **NUEVO:** Cobro por integración y personalización inicial (Setup Fee). | | |

* **Factibilidad V2 (Ajustada):** Altamente factible porque se centra en la inyección de estilos (CSS) y scripts ligeros (JS) en el DOM existente del banco, eliminando integraciones profundas en bases de datos financieras críticas.
* **Deseabilidad V2 (Ajustada):** El usuario final no tiene fricción de instalación, y para el banco es sumamente deseable porque reduce las filas físicas en sucursales y cumple con las normativas legales de accesibilidad digital.
* **Viabilidad V2 (Ajustada):** Viable debido a que se vende bajo un modelo SaaS B2B institucional. Las multas por discriminación o falta de accesibilidad, sumado al costo operativo de la atención en caja física, justifican con creces la inversión corporativa en SeniorClick.

---

## 8. Descripción Detallada de la Propuesta de Valor

La propuesta de valor de **SeniorClick** se sostiene sobre tres pilares fundamentales que fueron completamente validados en el experimento:

1. **Cero Instalación (One-Click Native):** Al estar integrado dentro del portal del propio banco, el usuario solo presiona un interruptor en pantalla. Se eliminan las App Stores, contraseñas de descarga, actualizaciones y problemas de memoria en el celular.
2. **Diseño UI/UX Cognitivo:** Remoción total de banners, seguros preconcedidos, promociones y menús secundarios. Solo se muestran los elementos esenciales de la transacción con tipografías de 22px a 36px y alto contraste.
3. **Doble Confirmación Visual Guiada:** Un paso obligatorio que le lee al usuario (o muestra de forma gigante y clara) el nombre completo del destinatario, su RUT, el banco y el monto exacto en pesos chilenos escritos con palabras, previniendo el miedo al "botón equivocado".

---

## 9. Conclusiones del Proceso de Experimentación

* **La confianza es institucional:** Los adultos mayores no confían en antivirus ni extensiones raras de internet debido al miedo a las estafas. Sin embargo, confían plenamente en lo que está *dentro* de la página de su banco.
* **El diseño adaptativo vence al miedo:** El miedo a la tecnología en la tercera edad no es un rechazo a la comodidad digital, sino una respuesta racional ante interfaces mal diseñadas que castigan el error. Cuando el diseño es indulgente, claro y asistido, el adulto mayor demuestra una autonomía del 80%.
* **Modelo B2B robusto:** Adaptar el portal web mediante SeniorClick no solo responde a un imperativo ético de inclusión, sino que representa un negocio altamente rentable para los bancos al derivar transacciones costosas del canal físico al digital de forma segura.
