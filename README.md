# Trove newspaper corrections

Current version: [v2.1](https://github.com/GLAM-Workbench/trove-newspapers-corrections/releases/tag/v2.1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12507383.svg)](https://zenodo.org/doi/10.5281/zenodo.12507383)

OCR errors in Trove's digitised newspapers can be corrected by users. To help understand patterns in newspaper correction, this dataset has been created to record information about the number of articles with corrections.

The data was extracted from the Trove API using [this notebook](https://glam-workbench.net/trove-newspapers/Analysing_OCR_corrections/) from the [Trove newspapers](https://glam-workbench.net/trove-newspapers/) section of the GLAM Workbench.

There are three files in the dataset:

- `corrections_by_year.csv` – number of articles corrected in each publication year
- `corrections_by_category.csv` – number of articles corrected in each Trove category
- `corrections_by_title.csv` – number of articles corrected in each newspaper

The files are in CSV format and contain the following fields.

## `corrections_by_year.csv` 

- `term` – the publication year
- `total_results` – the number of articles with corrections
- `total_articles` – the total number of articles
- `proportion` – the proportion of articles with corrections

## `corrections_by_category.csv` 

- `term` – the category name
- `total_results` – the number of articles with corrections
- `total_articles` – the total number of articles
- `proportion` – the proportion of articles with corrections

## `corrections_by_title.csv` 

- `id` – the Trove identitifer of the newsspaper title
- `title` – the name of the newspaper
- `articles_with_corrections` – the number of articles with corrections
- `total_articles` – the total number of articles from the newspaper in Trove
- `percentage_with_corrections` – the percentage of articles with corrections

----

This repository is part of the [GLAM Workbench](https://glam-workbench.net/).  
If you think this project is worthwhile, you might like [to sponsor me on GitHub](https://github.com/sponsors/wragge?o=esb).
