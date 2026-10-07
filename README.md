# ORIE-5256-Lopez-de-Prado-Financial-Machine-Learning

[One-sentence summary of what this project does and why it exists.]

## Quickstart

From zero to running:

```bash
# 1. Clone
git clone https://github.com/mmy32/ORIE-5256-Lopez-de-Prado-Financial-Machine-Learning-.git && cd ORIE-5256-Lopez-de-Prado-Financial-Machine-Learning-

# 2. Install dependencies
python -m venv .venv && source .venv/bin/activate && pip install -e ".[dev]"

# 3. Run tests
pytest
```

## Usage

```python
from src.data_loader import load_data

data = load_data("data/raw/example.csv")
```

## Architecture

[High-level overview: how the major components (data_loader, data_processing, feature_registry, transformations) connect. Include a diagram or flow description.]

## Project Structure

```
├── src/
│   ├── config/             # Settings, paths, constants
│   ├── models/             # Data models, schemas
│   ├── data_loader/        # Ingestion from files, APIs, databases
│   ├── data_processing/    # Cleaning, validation, normalization
│   ├── feature_registry/   # Feature definitions, metadata, versioning
│   ├── transformations/    # Reusable transform functions
│   └── utils/              # Logging, timing, helpers
├── tests/                  # Mirrors src/
├── data/                   # raw/ interim/ processed/ (gitignored)
├── scripts/                # Standalone utility scripts
├── notebooks/              # Exploration and prototyping
├── research/               # Notes, literature, exploration findings
└── reports/                # Generated reports
```
