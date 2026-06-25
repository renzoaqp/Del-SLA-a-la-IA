# Search Strategy

## Objetivo
Construir una base de literatura academica y tecnica confiable para sustentar el proyecto Del SLA a la IA y el framework DDIA.

## Regla principal
Consensus, Elicit, Perplexity, Semantic Scholar, Connected Papers y Research Rabbit son herramientas de descubrimiento. No son fuentes primarias. Toda referencia encontrada debe verificarse en la fuente original.

## Herramientas de apoyo

### Consensus
Uso recomendado:
- Validar si existe consenso academico sobre una pregunta.
- Buscar papers relacionados con preguntas concretas.
- Detectar revisiones sistematicas y meta-analisis cuando existan.

Preguntas sugeridas:
- What are the main challenges in defining service level agreements in IT service management?
- How are service level indicators and objectives used in site reliability engineering?
- What metrics are used to evaluate IT service desk performance?
- How is artificial intelligence applied to IT operations and AIOps?

### Elicit
Uso recomendado:
- Extraer tablas de papers.
- Comparar aportes, metodos, datasets y limitaciones.
- Identificar variables de investigacion.

Consultas sugeridas:
- SLA IT service management metrics service desk
- SLO SLI observability site reliability engineering
- AIOps incident management prediction IT operations
- KPI OKR IT service management performance measurement

### Perplexity
Uso recomendado:
- Exploracion rapida de temas.
- Encontrar fuentes primarias, documentos oficiales y papers.
- No usar su resumen como evidencia final.

Modo recomendado:
- Solicitar DOI.
- Solicitar fuente primaria.
- Solicitar papers revisados por pares.
- Verificar manualmente cada cita.

### Semantic Scholar
Uso recomendado:
- Buscar papers por tema.
- Revisar citas influyentes.
- Identificar autores y trabajos relacionados.

### Connected Papers / Research Rabbit
Uso recomendado:
- Mapear redes de literatura.
- Encontrar trabajos seminales.
- Encontrar papers recientes conectados.

## Bases academicas primarias
- Scopus
- Web of Science
- IEEE Xplore
- ACM Digital Library
- SpringerLink
- ScienceDirect
- Google Scholar como apoyo

## Cadenas de busqueda iniciales

### SLA y servicios TI
("service level agreement" OR SLA) AND ("IT service management" OR ITSM OR "service management")

### SLI/SLO/SRE
("service level indicator" OR SLI OR "service level objective" OR SLO) AND ("site reliability engineering" OR observability)

### Mesa de ayuda
("service desk" OR "help desk") AND (metrics OR KPI OR "incident management" OR "response time" OR "resolution time")

### Infraestructura y redes
("network service" OR networking OR infrastructure) AND (SLA OR availability OR latency OR "packet loss" OR MTTR)

### KPI y OKR
(KPI OR "key performance indicator" OR OKR OR "objectives and key results") AND ("IT service" OR ITSM OR operations)

### IA y operaciones
(AIOps OR "artificial intelligence for IT operations" OR "incident prediction" OR "anomaly detection") AND (ITSM OR observability OR infrastructure)

## Criterios de inclusion
- Paper revisado por pares.
- Libro tecnico reconocido.
- Documentacion primaria de un framework reconocido.
- Estudios con metodologia clara.
- Surveys o systematic reviews.

## Criterios de exclusion
- Blogs.
- Publicidad comercial.
- Opiniones sin metodologia.
- Referencias imposibles de verificar.
- Contenido generado por IA sin fuente primaria.

## Campos obligatorios por paper
- Titulo
- Autores
- Anio
- Venue
- DOI o URL primaria
- Base donde se encontro
- Tipo de estudio
- Conceptos relacionados
- Aporte
- Limitaciones
- Relacion con DDIA
- Decision: incluir, excluir o revisar

## Proceso
1. Buscar con herramientas de descubrimiento.
2. Verificar fuente primaria.
3. Registrar en literature-review-log.md.
4. Agregar BibTeX a bibliography/references.bib.
5. Extraer notas en research/summaries/.
6. Conectar hallazgos con knowledge/ y framework/.
