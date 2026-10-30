Motor Insurance Claims — Synthetic Sample Dataset

This archive contains synthetic sample data for testing the project pipeline.
It does not contain real customer information or real insurance transactions.

Extract the `data` folder into the inner project root (the same directory as
`run_pipeline.py` and `requirements.txt`). The expected paths are:

data/raw/customers.csv
data/raw/vehicles.csv
data/raw/policies.csv
data/raw/claims.csv
data/raw/payments.csv

Then run:
    python run_pipeline.py

And launch the dashboard:
    python -m streamlit run app/streamlit_app.py

Note: The supplied validation code may have additional expectations in other
modules. If the pipeline reports an error, share the full traceback so it can
be diagnosed.
