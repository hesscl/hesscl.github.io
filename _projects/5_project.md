---
layout: page
title: quackrfss
description: Fast access to BRFSS survey data (1990–2024) via DuckDB
importance: 5
category: software
---

[quackrfss](https://github.com/hesscl/quackrfss) is a Python package that provides fast, analyst-friendly access to the Behavioral Risk Factor Surveillance System (BRFSS) — the CDC's annual telephone survey on health behaviors, chronic conditions, and preventive care, covering 1990 through 2024.

**Features:**
- Download and cache BRFSS annual files automatically
- Query across years using DuckDB for high-performance in-process analytics
- Harmonized variable names across survey waves
- Filter by year, state, and demographic variables without loading full datasets into memory

**Use cases:** Longitudinal health behavior research, state-level public health analysis, studying trends in chronic disease prevalence, veteran and military subgroup health analyses.
