---
title: "ETL pipeline on GCP — Automated ingestion and transformation"
date: 2026-04-02
summary: "End-to-end pipeline with public API ingestion, BigQuery transformation, Airflow orchestration, and dashboard exposure."
tags: ["GCP", "BigQuery", "Airflow", "ETL", "Python"]
weight: 2
ShowToc: true
homeCategory: "Data pipelines"
homeLabel: "Stabilize an end-to-end pipeline"
clientProblem: "External data has to be collected, transformed, and loaded automatically without multiplying manual handling."
approach: "Build an orchestrated pipeline on GCP with ingestion, raw storage, transformation, and analytical exposure."
value: "A more robust and traceable flow, ready to support reporting or downstream operational use."
---

## Context

This project covers the design of a complete data pipeline on Google Cloud Platform, from ingestion to visualization.

## Architecture

```
Public API -> Cloud Function -> Cloud Storage (raw)
    -> Dataflow (transformation) -> BigQuery (analytics)
        -> Looker Studio (dashboard)
```

Orchestration: Apache Airflow (scheduling, dependencies, alerting)

## Demonstrated skills

- Data ingestion from a REST API
- Structured storage in Cloud Storage
- Transformation and loading into BigQuery
- Task orchestration with Airflow
- Dashboard exposure layer

## Tech stack

`Python` · `GCP` · `BigQuery` · `Cloud Storage` · `Dataflow` · `Airflow` · `Looker Studio`

## Results

*(To be completed when the project is fully published)*

[View on GitHub](https://github.com/PaulaF-source)
