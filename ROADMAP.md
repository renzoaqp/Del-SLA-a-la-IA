# Roadmap - Del SLA a la IA

Este roadmap organiza el proyecto como un Research OS: primero se construye la base documental, luego el framework DDIA, despues los articulos, los casos de estudio y finalmente la linea academica.

## Principio de trabajo

No empezamos escribiendo articulos. Empezamos construyendo una base de conocimiento verificable.

Flujo general:

Servicio -> SLI -> SLO -> SLA -> KPI -> OKR -> Observabilidad -> Analitica -> IA -> Decision

---

## Fase 0: Preparar el Research OS

Objetivo: dejar el repositorio listo para trabajar en VS Code con Codex o ChatGPT.

Entregables:
- PROJECT_MEMORY.md
- AGENTS.md
- CURRENT_TASK.md
- DECISIONS.md
- ROADMAP.md
- Estructura base de carpetas
- Prompts para investigador, redactor, revisor y arquitecto

Estado: iniciado.

---

## Fase 1: Construir el mapa conceptual

Objetivo: definir con precision los conceptos base.

Temas:
- Servicio tecnologico
- SLA
- SLI
- SLO
- Error budget
- KPI
- OKR
- Observabilidad
- AIOps e IA aplicada

Entregables:
- knowledge/SLA.md
- knowledge/SLI.md
- knowledge/SLO.md
- knowledge/KPI.md
- knowledge/OKR.md
- knowledge/Observability.md
- knowledge/AI.md
- glossary.md

Criterio de salida:
Cada concepto debe tener definicion, ejemplo, fuente de datos, errores comunes y relacion con DDIA.

---

## Fase 2: Busqueda y curacion de literatura

Objetivo: obtener insumos cientificos y tecnicos confiables.

Fuentes primarias preferidas:
- Scopus
- Web of Science
- IEEE Xplore
- ACM Digital Library
- SpringerLink
- ScienceDirect
- Google SRE Book y SRE Workbook
- ITIL y normas aplicables cuando corresponda

Herramientas de apoyo permitidas:
- Consensus
- Elicit
- Perplexity
- Semantic Scholar
- Connected Papers
- Research Rabbit
- Google Scholar

Regla critica:
Las herramientas con IA ayudan a descubrir literatura, pero no reemplazan la verificacion humana. Ninguna respuesta generada por IA se considera fuente primaria.

Entregables:
- research/search-strategy.md
- research/literature-review-log.md
- research/papers-screening.csv
- bibliography/references.bib
- research/gap-analysis.md

Criterio de salida:
Tener una matriz inicial de papers con titulo, autores, anio, venue, DOI, base de datos, tema, aporte, limitaciones y relacion con DDIA.

---

## Fase 3: Formalizar DDIA v0.1

Objetivo: convertir DDIA en framework aplicable.

DDIA:
- Define: definir servicio, usuario, valor, alcance y restricciones.
- Design: disenar SLI, SLO, SLA, KPI y OKR.
- Instrument: instrumentar fuentes de datos, dashboards, calculos y validacion.
- Analyze: analizar resultados, brechas, decisiones, automatizacion e IA.

Entregables:
- framework/DDIA.md
- framework/MaturityModel.md
- framework/ServiceEngineering.md
- diagrams/ddia-flow.md
- templates/ddia-service-template.md

Criterio de salida:
DDIA debe poder aplicarse a un servicio de mesa de ayuda y a uno de infraestructura.

---

## Fase 4: Articulo 1 - Mesa de ayuda

Objetivo: construir el primer articulo LinkedIn de la serie.

Titulo tentativo:
Deja de medir disponibilidad unicamente: como disenar SLA, SLI y SLO para una mesa de ayuda.

Enfoque:
Una mesa de ayuda no se mide como una red. Se mide por tiempos, prioridad, capacidad, resolucion, calidad y experiencia.

Datos requeridos:
- Creacion de ticket
- Primera respuesta
- Cambios de estado
- Prioridad
- Categoria
- Resolucion
- Reapertura
- Satisfaccion

Entregables:
- articles/linkedin/01-service-desk.md
- templates/service-desk/sli-catalog.md
- case-studies/service-desk/README.md

Criterio de salida:
El articulo debe explicar como pasar de datos crudos a SLI, SLO, SLA, KPI y decision.

---

## Fase 5: Articulo 2 - Infraestructura y redes

Objetivo: construir el segundo articulo LinkedIn.

Titulo tentativo:
Deja de medir disponibilidad unicamente: como disenar SLA, SLI y SLO para infraestructura.

Enfoque:
El negocio no compra routers, switches, firewalls o Kubernetes. Compra servicios: conectividad, acceso, continuidad y estabilidad.

Datos requeridos:
- Disponibilidad
- Latencia
- Packet loss
- Jitter
- MTTR
- MTBF
- Capacidad
- Incidentes
- Ventanas de mantenimiento

Entregables:
- articles/linkedin/02-infrastructure.md
- templates/networking/sli-catalog.md
- case-studies/networking/README.md

Criterio de salida:
El articulo debe mostrar que un SLA tecnico tiene costo, riesgo, restricciones y evidencia.

---

## Fase 6: Articulo 3 - KPI y OKR

Objetivo: conectar operacion con gestion.

Titulo tentativo:
Cuando medir deja de ser suficiente: como convertir SLA, SLI y SLO en decisiones.

Enfoque:
SLI mide, SLO orienta, SLA compromete, KPI gestiona y OKR transforma.

Entregables:
- articles/linkedin/03-kpi-okr.md
- knowledge/KPI.md
- knowledge/OKR.md
- templates/kpi-okr-template.md

Criterio de salida:
Mostrar ejemplos paralelos para mesa de ayuda e infraestructura.

---

## Fase 7: Articulo 4 - Observabilidad e IA

Objetivo: explicar como la IA entra al final de la cadena, no al inicio.

Titulo tentativo:
La IA no arregla datos malos: por que primero necesitas observabilidad y servicios bien medidos.

Enfoque:
La IA requiere datos historicos, calidad, taxonomia, trazabilidad y contexto.

Casos:
- Prediccion de backlog
- Clasificacion de tickets
- Deteccion de anomalias
- Recomendacion de capacidad
- Resumen ejecutivo de cumplimiento

Entregables:
- articles/linkedin/04-ai.md
- knowledge/AI.md
- methodology/ai-readiness.md

Criterio de salida:
No vender IA como magia. Mostrar requisitos, datos y limites.

---

## Fase 8: Implementaciones tecnicas

Objetivo: convertir el framework en algo ejecutable.

Herramientas:
- Prometheus
- Grafana
- Zabbix
- GLPI
- osTicket
- Azure Monitor
- CloudWatch
- OpenTelemetry

Entregables:
- implementations/prometheus/
- implementations/grafana/
- implementations/glpi/
- implementations/osticket/
- dashboards/

Criterio de salida:
Cada SLI importante debe tener fuente de datos, formula, consulta o forma de implementacion.

---

## Fase 9: Validacion y casos de estudio

Objetivo: probar DDIA en escenarios concretos.

Casos minimos:
- Mesa de ayuda
- Networking
- Infraestructura o cloud

Entregables:
- case-studies/service-desk/
- case-studies/networking/
- case-studies/cloud/
- research/validation-plan.md

Criterio de salida:
Demostrar que DDIA produce decisiones mejores o mas defendibles que operar solo por percepcion.

---

## Fase 10: Linea academica Q1/Q2

Objetivo: convertir el trabajo en articulo cientifico.

Posible titulo:
From SLA to AI: A Data-Driven Framework for IT Service Engineering.

Metodologia posible:
- Design Science Research
- Systematic Literature Review
- Case Study Evaluation

Entregables:
- papers/q1-q2/outline.md
- research/systematic-review.md
- research/gap-analysis.md
- methodology/DesignScienceResearch.md

Criterio de salida:
Tener framework, evidencia, gap analysis y validacion documentada.

---

## Proximo paso inmediato

1. Completar research/search-strategy.md.
2. Buscar literatura con Consensus, Elicit, Perplexity y bases academicas.
3. Registrar todo en research/literature-review-log.md.
4. Fortalecer DDIA con evidencia.
5. Reescribir el articulo 1 con soporte documental.
