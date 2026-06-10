# 📊 Informe Académico: Introducción a la Ciencia de Datos

Este documento constituye el registro de competencias, conceptos clave y aplicaciones estratégicas adquiridas durante el programa **"Introducción a la Ciencia de Datos"**, desarrollado por **IE University** en colaboración con **Santander Open Academy**.

El objetivo de este informe es documentar los fundamentos de la gestión, calidad y análisis de datos masivos (Big Data), y demostrar su aplicación directa en la ingeniería de detección y respuesta ante incidentes en **Ciberseguridad**.

---

## 📋 Ficha del Programa Académico

* **Institución Emisora:** IE University & Santander Open Academy
* **Especialidad:** Ciencia de Datos e Inteligencia de Negocio
* **Estudiante:** Alejandro (Junior Security Consultant / Data Analyst)
* **Enfoque de Aplicación:** Detección de Anomalías e Inteligencia de Amenazas (Threat Intelligence)

---

## 🚀 Módulos Académicos y Conceptos Clave

### 1. Fundamentos Estadísticos Aplicados
Comprensión de la estadística descriptiva e inferencial como base para la toma de decisiones:
* **Variables Estadísticas:** Clasificación de datos cuantitativos (discretos/continuos) y cualitativos (nominales/ordinales) para el correcto modelado de datos.
* **Unidad Experimental:** Identificación de la entidad mínima de análisis (por ejemplo, una dirección IP única o un proceso del sistema) para evaluar comportamientos anómalos.

### 2. Gestión de la Calidad de Datos (Data Quality)
La efectividad de cualquier modelo de detección depende directamente de la calidad de sus datos de entrada (*Garbage In, Garbage Out*):
* **Tratamiento de Ruido:** Técnicas para filtrar logs irrelevantes o duplicados que saturan el almacenamiento.
* **Análisis de Outliers (Valores Atípicos):** Identificación matemática de registros que se desvían drásticamente del comportamiento promedio, siendo este el principio fundamental para detectar intrusiones en la red.

---

## 📈 Estrategia Big Data: El Modelo de las 5 Vs

En entornos corporativos modernos, la telemetría de seguridad supera la capacidad de las bases de datos relacionales tradicionales. El ecosistema Big Data se define mediante cinco pilares estratégicos:

| Dimensión (V) | Definición Técnica | Aplicación Directa en Ciberseguridad |
| :--- | :--- | :--- |
| **Volumen** | Escala masiva de información generada en Terabytes. | Almacenamiento histórico de logs de toda la infraestructura corporativa. |
| **Velocidad** | Rapidez en el flujo y procesamiento de datos. | Correlación de eventos en tiempo real para bloquear ataques en tránsito (SIEM). |
| **Variedad** | Diversidad de fuentes (Estructuradas, JSON, Texto). | Integración de datos de firewalls, correos, sistemas operativos y endpoints. |
| **Veracidad** | Fiabilidad, integridad y precisión de las fuentes. | Descarte de "Falsos Positivos" y verificación criptográfica de logs. |
| **Valor** | Transformación de datos en decisiones estratégicas. | Inteligencia de amenazas que permite anticipar y mitigar futuros incidentes. |

---

## 👥 Roles Profesionales en el Ecosistema de Datos

Comprender la división de funciones dentro de un equipo de datos es vital para la correcta ejecución de proyectos complejos:

* **Analista de Datos (Data Analyst):** Se enfoca en mirar el pasado; limpia datos, genera dashboards y extrae métricas de rendimiento (KPIs).
* **Científico de Datos (Data Scientist):** Se enfoca en predecir el futuro; construye modelos predictivos y algoritmos de Machine Learning.
* **Ingeniero de Datos (Data Engineer):** Construye la infraestructura (pipelines, bases de datos distribuidas) para que los analistas y científicos puedan trabajar.

---

## 🛡️ Intersección Estratégica: Ciencia de Datos + Ciberseguridad

La ciberseguridad moderna es, en esencia, un problema de análisis de datos masivos. La integración de los conocimientos de este curso con la seguridad informática permite optimizar dos áreas críticas:

### A. Filtrado de Ruido y Reducción de Fatiga por Alerta
En un centro de operaciones de seguridad (SOC), los analistas sufren de "fatiga por alerta" debido a la inmensa cantidad de alertas falsas generadas por sistemas de prevención de intrusos (IDS/IPS). 
* **Solución desde la Ciencia de Datos:** La correcta gestión de la calidad de datos y la eliminación de "ruido estadístico" permiten refinar las reglas del IDS para que solo notifiquen incidentes con un nivel de veracidad y riesgo real.

### B. Análisis de Anomalías de Red (Detección de Amenazas)
Las firmas de virus tradicionales no sirven para detectar ataques de día cero (vulnerabilidades nuevas). 
* **Solución desde la Ciencia de Datos:** Al definir una "línea base" de lo que es tráfico normal (usando fundamentos estadísticos), cualquier conexión atípica (*outlier*), como la exfiltración silenciosa de datos sensibles fuera del horario de oficina, es identificada automáticamente como una anomalía sospechosa.

## 🎓 Certificación
- **Institución:** IE University / Santander Open Academy
- **Fecha de finalización:** 8 de junio de 2026
- **ID de Credencial:** OA-2026-0608002722407
- **Ver certificado oficial:** [Descargar Certificado PDF](Certificado_Ciencia_Datos.pdf)
