---
title: "Pipeline ETL en GCP — Ingesta y transformación automatizadas"
date: 2026-04-02
summary: "Pipeline end-to-end con ingesta desde una API pública, transformación en BigQuery, orquestación con Airflow y exposición en dashboard."
tags: ["GCP", "BigQuery", "Airflow", "ETL", "Python"]
weight: 2
ShowToc: true
homeCategory: "Pipelines data"
homeLabel: "Estabilizar un pipeline de punta a punta"
clientProblem: "Los datos externos deben recogerse, transformarse y cargarse automáticamente sin multiplicar manipulaciones manuales."
approach: "Construir un pipeline orquestado en GCP con ingesta, almacenamiento raw, transformación y exposición analítica."
value: "Un flujo más robusto y trazable, listo para alimentar reporting u otros usos operativos."
---

## Contexto

Este proyecto cubre el diseño de un pipeline de datos completo en Google Cloud Platform, desde la ingesta hasta la visualización.

## Arquitectura

```
API pública -> Cloud Function -> Cloud Storage (raw)
    -> Dataflow (transformación) -> BigQuery (analytics)
        -> Looker Studio (dashboard)
```

Orquestación: Apache Airflow (scheduling, dependencias, alertas)

## Competencias demostradas

- Ingesta de datos desde una API REST
- Almacenamiento estructurado en Cloud Storage
- Transformación y carga en BigQuery
- Orquestación de tareas con Airflow
- Capa de exposición para dashboard

## Stack técnico

`Python` · `GCP` · `BigQuery` · `Cloud Storage` · `Dataflow` · `Airflow` · `Looker Studio`

## Resultados

*(Se completará cuando el proyecto esté totalmente publicado)*

[Ver en GitHub](https://github.com/PaulaF-source)
