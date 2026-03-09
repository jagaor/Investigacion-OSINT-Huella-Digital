# Análisis Forense e Inteligencia de Fuentes Abiertas (OSINT)

## 📝 Descripción General
Este proyecto, enmarcado en el módulo de "Análisis Forense", documenta una investigación práctica utilizando técnicas de Inteligencia de Fuentes Abiertas (OSINT). El objetivo principal es auditar la huella digital de un objetivo específico (realizado sobre el propio autor mediante auto-auditoría por motivos éticos y de privacidad), demostrando cómo la información pública fragmentada en Internet puede correlacionarse para construir perfiles detallados. Se evalúa el riesgo de que esta información caiga en manos de actores maliciosos y se proponen medidas de mitigación.

## 🎯 Objetivos de la Investigación
* Aplicar una metodología OSINT estructurada: Definición del objetivo, recolección, análisis de datos, evaluación de riesgos y remediación.
* Utilizar técnicas de búsqueda avanzada (Google Dorks) para localizar documentos y perfiles no indexados de forma directa.
* Extraer y correlacionar identidades, correos electrónicos y dominios mediante herramientas gráficas de análisis de enlaces.
* Identificar riesgos reales de ciberseguridad derivados de la exposición de datos, como ataques de Ingeniería Social (Phishing, Vishing), Suplantación de Identidad o Doxing.
* Elaborar un plan de contingencia y concienciación para reducir la superficie de exposición digital.

## 🛠️ Tecnologías y Herramientas OSINT
* **Búsqueda Avanzada**: Operadores booleanos y Google Dorks (`site:`, `filetype:`, `intitle:`).
* **Análisis de Enlaces y Relaciones**: Maltego (para mapeo de dominios, correos y servidores).
* **Extracción de Metadatos**: FOCA (Fingerprinting Organizations with Collected Archives).
* **Búsqueda de Identidades**: Motores de búsqueda de personas (ej. Pipl, Social Searcher) y análisis transversal en redes sociales (LinkedIn, Instagram).

## ⚙️ Hallazgos y Evaluación de Riesgos
* **Correlación de Identidades**: Se demostró cómo el uso de alias compartidos y fotografías vinculadas permite a un investigador unificar perfiles inconexos, deduciendo hábitos, relaciones personales y horarios aproximados.
* **Fuga por Metadatos**: Se evidenció que los documentos públicos (como PDFs o archivos ofimáticos) pueden contener información invisible a simple vista (metadatos) sobre el software utilizado, rutas locales y nombres de usuario del sistema.
* **Vector de Ataque**: La investigación concluye que los datos expuestos, aparentemente inofensivos por separado, son el vector inicial perfecto para orquestar delitos informáticos, facilitando la creación de campañas de suplantación o fraudes personalizados.
* **Plan de Mitigación**: Se definieron directrices de protección activa, incluyendo la depuración de la huella digital, la segmentación de identidades online (no reutilizar *usernames*), y el endurecimiento de la privacidad en redes.

## 📄 Documentación Completa
Para visualizar los grafos de Maltego resultantes de la investigación, las consultas exactas realizadas en los motores de búsqueda y la evaluación detallada de cada vulnerabilidad humana encontrada, puedes acceder a la memoria técnica:

👉 [Enlace al Informe Técnico en Google Drive](https://docs.google.com/document/d/18zWuroXhp-Rop438JZYK-0myuTit-2NunWjboBIP014/edit?usp=sharing)

## ⚠️ Aviso Legal / Ética
*Las técnicas de recolección de información documentadas en este proyecto se han aplicado estrictamente bajo el marco del Hacking Ético (Auto-auditoría), respetando la legalidad vigente en materia de protección de datos (RGPD). La utilización de herramientas OSINT para investigar a terceros sin consentimiento o justificación legal puede constituir un delito.*
