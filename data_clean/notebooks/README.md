## Analysis Notebooks

This directory contains the full analytical pipeline for the Airport Capacity Stress Test project.

### Notebook Flow

### 1. `01_ingest_validate.ipynb`
- Load raw flight data in chunks
- Enforce schema and data types
- Validate missing values, duplicates, and time gaps
- Export clean dataset

### 2. `02_peak_hour_analysis.ipynb`
- Compute hourly traffic density
- Generate weekday × hour heatmap
- Identify top congestion windows

### 3. `03_scenario_simulator.ipynb`
- Simulate traffic smoothing
- Shift peak-hour demand
- Measure congestion reduction impact
