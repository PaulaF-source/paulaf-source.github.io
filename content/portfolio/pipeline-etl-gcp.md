---
title: "Pipeline ETL sur GCP — Ingestion et transformation automatisées"
date: 2026-04-02
summary: "Pipeline end-to-end : ingestion depuis une API publique, transformation dans BigQuery, orchestration avec Airflow, visualisation dans Looker Studio."
tags: ["GCP", "BigQuery", "Airflow", "ETL", "Python"]
weight: 2
ShowToc: true
homeLabel: "Fiabiliser un pipeline de bout en bout"
clientProblem: "Des données externes doivent être collectées, transformées et chargées automatiquement sans multiplier les manipulations manuelles."
approach: "Mise en place d'un pipeline orchestré sur GCP avec ingestion, stockage brut, transformation et exposition analytique."
value: "Un flux plus robuste, plus traçable et prêt à alimenter le reporting ou d'autres usages métier."
---

## Contexte

Construction d'un pipeline de données complet sur Google Cloud Platform, de l'ingestion à la visualisation.

## Architecture

```
API publique → Cloud Function → Cloud Storage (raw)
    → Dataflow (transformation) → BigQuery (analytics)
        → Looker Studio (dashboard)
```

Orchestration : Apache Airflow (scheduling, dépendances, alerting)

## Compétences démontrées

- Ingestion de données depuis une API REST
- Stockage et organisation dans Cloud Storage
- Transformation et chargement dans BigQuery
- Orchestration de tâches avec Airflow
- Dashboard de visualisation

## Stack technique

`Python` · `GCP` · `BigQuery` · `Cloud Storage` · `Dataflow` · `Airflow` · `Looker Studio`

## Résultats

*(À compléter quand le projet sera réalisé)*

🔗 [Voir sur GitHub](https://github.com/PaulaF-source)
