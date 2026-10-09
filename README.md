# goit-rdb-hw-03

Dataset: Seoul Bike Sharing Demand (UCI Machine Learning Repository)
Official source: https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand

Sample: the full dataset, 8760 rows x 14 columns, fetched with `ucimlrepo` (`fetch_ucirepo(id=560)`) in the notebook and saved to `data/hw3_dataset.csv`.

How to run: Python 3.12 (pgserver does not install on 3.13/3.14). Create a venv, run `pip install pgserver psycopg2-binary sqlalchemy pandas pyarrow ucimlrepo ipykernel`, open `hw3.ipynb` and run Restart & Run All.
