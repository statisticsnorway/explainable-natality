# explainable-natality
Explainable AI on natality data to predict birth weight

The Notebook named ´sample-natality-data.ipynb´ retrieves a sample of open natality data from BigQuery, cleans and changes it to numbers, and dumps it in two CSV files.

The Notebook named ´natality-ai-explanations.ipynb´ is based on Google Cloud Platform example notebook for explainable AI. It has been updated to fix some bugs, and it is also changed to accomodate the Natality data rather than the default data google used in the example. Run this notebook after the ´sampple-natality-data.ipynb´ notebook has created the ´train.csv´ and ´eval.csv´ files. This notebook is configured to work with a specific GCP project, so if you want to run it yourself you have to go through the cells and change some values.

The Notebook named ´ai-explanations-tabular.ipynb´ is a notebook that is very close to the original GCP Explainable AI example notebook which is about prediction of the length of bike rides. This version of the notebook has been debugged and updated to function in september 2021, which Googles own example did not.
