# Actividad 4: Herramientas y tecnologías de calidad de software

**Caso de estudio:** Therac-25
**Herramienta seleccionada:** SonarQube (análisis estático)
**Versión:** 2 (mejorada con citación de autores y paráfrasis, según la retroalimentación del docente)

| | |
|---|---|
| **Estudiante** | Breynner Alexander Pérez Álvarez |
| **Institución** | Corporación Universitaria Iberoamericana |
| **Programa** | Ingeniería de Software |
| **Curso** | Calidad de Software |
| **Docente** | Willian Ruiz |
| **Fecha** | Octubre de 2026 |

## Descripción

Informe académico que investiga y compara herramientas de calidad de software (análisis estático, pruebas automatizadas y gestión de pruebas), selecciona la más pertinente para el caso Therac-25 y describe cómo se aplicaría para detectar y prevenir las fallas que causaron los accidentes de radioterapia entre 1985 y 1987.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `Actividad_4_Herramientas_Calidad_Software_Therac25.pdf` | Informe completo (13 páginas, formato APA 7) |
| `README.md` | Este archivo |

## Estructura del informe

1. **Portada e introducción**, con objetivo general y objetivos específicos.
2. **Caso de estudio:** resumen del Therac-25 y seis fallas principales asociadas a atributos de calidad (modelo de McCall e ISO/IEC 25010:2023).
3. **Selección y análisis de herramientas:** SonarQube, JUnit, TestRail, Selenium y SoapUI, con funcionalidades, problemas que abordan, ventajas y desventajas.
4. **Comparación:** matriz con seis criterios (facilidad de uso, costo, plataformas, integración, comunidad y pertinencia para el caso).
5. **Herramienta seleccionada:** características, funcionalidades y limitaciones de SonarQube.
6. **Aplicación práctica (parte descriptiva):** módulo simulado en C, flujo dentro del proceso de desarrollo y relación entre fallas, hallazgos esperados y medidas correctivas.
7. **Evaluación de impacto y medidas anticipadas:** quality gate, integración continua, pruebas dinámicas, revisión por pares, análisis de riesgos y gestión de defectos.
8. **Conclusiones y referencias.**

## Cambios de la versión 2

- Se incorporaron citas de autores y normas en la introducción, el caso de estudio, la comparación, la herramienta seleccionada y las medidas propuestas: Aizprua et al. (2019), Campbell y Papapetrou (2013), Cunningham (1992), Fagan (1976), Humble y Farley (2010), Leveson (1995), McCall et al. (1977), Myers et al. (2011), IEC 62304 e ISO/IEC 25010:2023.
- Se parafrasearon los conceptos principales y se amplió la lista de referencias en APA 7.

## Correspondencia con la rúbrica

| Criterio de la rúbrica | Dónde se aborda |
|---|---|
| Selección correcta de una herramienta de calidad | Secciones 2 y 3: análisis de características, funcionalidades, ventajas y problemas que puede abordar |
| Procesos de calidad usando la herramienta | Secciones 4 y 5: aplicación al caso, evaluación del impacto y medidas anticipadas |
| Presentación (normas APA) | Todo el documento: portada, introducción, desarrollo, conclusiones, tablas y figuras con formato APA 7 y referencias |

## Aclaraciones importantes

- **Caso simulado.** El software original del Therac-25 estaba escrito en lenguaje ensamblador, que SonarQube no analiza. Por eso la aplicación se hace sobre un módulo simulado en C que reproduce el tipo de defecto del caso.
- **Hallazgos ilustrativos.** Los resultados descritos en la sección 4 son el tipo de alerta esperado y no una salida real de SonarQube.
- **Matriz comparativa.** Las valoraciones de 1 a 5 son un juicio razonado del autor, no una medición objetiva.
- **Uso de IA.** La actividad limita el uso de herramientas de IA a un máximo del 30 %.

## Referencias principales

- Leveson, N. G., & Turner, C. S. (1993). An investigation of the Therac-25 accidents. *Computer, 26*(7), 18-41. https://doi.org/10.1109/MC.1993.274940
- Pressman, R. S., & Maxim, B. R. (2021). *Ingeniería de software*. McGraw-Hill Interamericana.
- Piattini-Velthuis, M., & García-Rubio, F. (2015). *Calidad de sistemas de información*. RA-MA Editorial.
- SonarSource. (s. f.). *SonarQube documentation*. https://docs.sonarsource.com/sonarqube/

La lista completa está al final del PDF.
