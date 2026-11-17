# Data

## Part 1: São Paulo crime reports

1. Download `dataset-limpo.csv` from the [Geospatial São Paulo Crime Database](https://www.kaggle.com/datasets/danlessa/geospatial-sao-paulo-crime-database) on Kaggle.
2. Place it at `data/dataset-limpo.csv`.

The file is not included in this repository: the Kaggle page states no license, and the original file contains personal fields such as IP addresses and street addresses. The notebook only uses the neighborhood (`bairro`), the report time (`created_at`), the coordinates and seven stolen-item columns.

`subprefeituras-sp.geojson` (São Paulo subprefecture boundaries) is included. If it is missing, the notebook downloads it on the first run and caches it here.

## Part 2: Kaggle course exercises (optional)

The reference-only exercises in Part 2 use the [Geospatial Learn Course Data](https://www.kaggle.com/datasets/alexisbcook/geospatial-learn-course-data) bundle (Boston crime data, Philippines/Ghana boundary files, DEC lands shapefile). The "Installing the Kaggle API" cell downloads and extracts it to `data/geospatial_learn/`. Set the `KAGGLE_USERNAME` and `KAGGLE_KEY` environment variables first (see the notebook).
