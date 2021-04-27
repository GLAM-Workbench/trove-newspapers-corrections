# Trove newspaper corrections

Current version: [v1.2](https://github.com/GLAM-Workbench/trove-newspapers-corrections/releases/tag/v1.2)

OCR errors in Trove's digitised newspapers can be corrected by users. To help understand patterns in newspaper correction, this dataset has been created to record the number of articles with corrections in each digitised newspaper. By retrieving the total number of articles in each newspaper, it's then possible to calculate the percentage of articles with corrections.

The data was extracted from the Trove API using [this notebook](https://glam-workbench.net/trove-newspapers/Analysing_OCR_corrections/) from the [Trove newspapers](https://glam-workbench.net/trove-newspapers/) section of the GLAM Workbench.

The data is available as a CSV file entitled `corrections_by_title.csv` and contains the following fields:

- `id` – the Trove identitifer of the newsspaper title
- `title` – the name of the newspaper
- `articles_with_corrections` – the number of articles with corrections
- `total_articles` – the total number of articles from the newspaper in Trove
- `proportion` – the proportion of articles with corrections
- `percentage_with_corrections` – the percentage of articles with corrections
- `title_url` – url to the newspaper title page in Trove

----

This repository is part of the [GLAM Workbench](https://glam-workbench.net/).  
If you think this project is worthwhile, you might like [to sponsor me on GitHub](https://github.com/sponsors/wragge?o=esb).
