# output/data

This folder is the working data directory for the governance pipeline.

Two files required to run the pipeline are too large for GitHub and are distributed as release assets. Download them from the [v1.0.0 release](../../releases/tag/v1.0.0) and place them here before running any scripts.

| File | Size | Description |
|------|------|-------------|
| `calls_clean.csv` | ~307MB | Cleaned and feature-engineered call records prepared for scoring |
| `calls_scored.csv` | ~311MB | Fully scored call records with all six Trust Signal Health dimensions and governance flags |
