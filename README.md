# Case NPS - Analista de Planejamento

Professional Python project for profiling an NPS planning case. The original notebook is preserved and reusable pipeline code now lives in `src/nps_case/`.

## Staff Data Engineer assessment

This project is useful because it combines customer-experience metrics, operational segmentation and text exploration. The main engineering gap was that business rules and transformations were not separated from the notebook.

## How to run

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m pytest
python -m nps_case.pipeline --input data/raw/input.xlsx --output data/processed
```

## Current limitations

- The source Excel file is not committed.
- NPS metric definitions, quadrants and quartile rules should be documented as explicit contracts.
- Text processing should be extracted into tested functions in a later PR.
