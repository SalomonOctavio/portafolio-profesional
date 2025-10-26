# Módulo de Promociones (WOM, 2015–2017)

**Rol y alcance:** Product Manager Desarrollo · transversal con Marketing/Desarrollo, TI y CRM/Billing.  
**Sistemas:** Ericsson **BSCS iX**, Oracle **Siebel CRM**, ALU **8610 ICC**, Huawei **UPCC (PCRF)**, MicroStrategy (reporting).

## Contexto
Promociones basadas en **eventos** (altas, cambios de plan, recargas, compras de bolsas), con necesidad de trazabilidad y menos configuraciones manuales dispersas.

## Objetivo de negocio
Impulsar **upsell/retención** y mejorar **CX** habilitando reglas automáticas por segmento/evento.

## Problema
- Promociones manuales y desalineadas entre sistemas.  
- **Baja trazabilidad** y time-to-market lento.  
- Riesgo de **errores operativos**.

## Hipótesis/Propuesta
Diseñar un **módulo orquestador de promociones** orientado a eventos, con catálogo versionado de reglas y flujos de validación/UAT E2E para salida segura a producción.

## Enfoque y ejecución
- **Definición de reglas** por evento/segmento (condiciones, vigencias, límites).  
- **Integraciones** con BSCS/CRM/ICC/PCRF y mapeos de datos para gatillar beneficios.  
- **Backlog** y criterios de aceptación; planificación y **UAT end-to-end** (negocio + TI).  
- **Catálogo de promociones** con versionado y control de cambios.  
- **Comunicaciones de lanzamiento** y playbooks de soporte post–Go-Live.

## Resultados (KPIs/Outcomes)
- **Time-to-market**: nuevas promociones configurables en *horas/días* (antes semanas). *(estimado)*  
- **Calidad**: reducción de **errores manuales** y mayor **trazabilidad** por evento/segmento. *(cualitativo)*  
- **Negocio**: tendencia **positiva** en upsell/retención en campañas gatilladas por eventos. *(cualitativo)*

> Si más adelante encuentras cifras en PPT/reportes, reemplazamos “estimado/cualitativo” por números.

## Estabilidad y soporte post
Monitoreo inicial, corrección temprana de incidencias y checklist de **Go-Live**; coordinación con Operaciones, Atención y Reportería para cierre de brechas.

## Aprendizajes
- Mantener **versionado de reglas** y matriz de dependencias por sistema evita “derivas” comerciales.  
- Los **criterios de aceptación** ligados a medición (eventos/segmentos) aceleran validación y reporting.

## Artefactos
- `diagrams/` As-Is/To-Be del flujo de evento → regla → beneficio.  
- `uat/` plan y casos E2E; bitácora de hallazgos/fixes.  
- `docs/` catálogo de promociones y matrices.  
- `comms/` comunicaciones de lanzamiento y post.

## Créditos y roles
Marketing/Desarrollo, TI (CRM/Billing/Red), Procesos, Atención; proveedores de plataforma (ALU/Nokia, Huawei).
