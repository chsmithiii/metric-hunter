# Metric Hunter [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) ![Status](https://img.shields.io/badge/Project-Template-lightgrey)
Map any process → inventory signals → propose KPIs (leading/lagging) → expose levers.

## Problem
Teams ship features without shared definitions of success. Metrics drift; dashboards don’t drive action.

## Method (playbook)
1) Intake & context map  
2) Signal inventory (events, states, user paths)  
3) Metric proposals (validity, sensitivity, latency)  
4) Causality checks (A/B, DiD, ITS)  
5) Adoption plan (owners, alerts, reviews)

## Templates
- `/templates/metric_spec.yaml` – metric contract (owner, grain, formula, SLO)
- `/templates/sample_signals.csv` – toy signals for demo

## Reproduce
```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
