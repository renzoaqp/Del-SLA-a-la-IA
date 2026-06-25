# Articulo 2 - Del SLA a la IA: Infraestructura y redes

## Titulo tentativo
Deja de medir disponibilidad unicamente: como disenar SLA, SLI y SLO para infraestructura.

## Idea central
El negocio no compra routers, switches, firewalls o Kubernetes. Compra conectividad, continuidad, acceso y estabilidad.

## Problema de apertura
Un gerente dice que no importa apagar un servidor todo un dia por trabajos electricos, pero al mismo tiempo exige 99.99 por ciento de disponibilidad. Ambas ideas no pueden convivir sin discutir costo, riesgo y necesidad real del negocio.

## Datos necesarios
- Disponibilidad medida desde el usuario o sede.
- Latencia.
- Packet loss.
- Jitter.
- Incidentes.
- MTTR.
- MTBF.
- Capacidad utilizada.
- Ventanas de mantenimiento.

## SLI posibles
- Porcentaje de disponibilidad mensual.
- Latencia p95.
- Perdida de paquetes.
- Tiempo medio de recuperacion.
- Incidentes repetitivos.

## Cierre sugerido
Un SLA de infraestructura no debe empezar por el porcentaje de disponibilidad. Debe empezar por la pregunta: cuanto riesgo esta dispuesto a pagar el negocio?
