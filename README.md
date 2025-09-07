### Global Layoff Trends

### Introduction
I analyzed a global layoffs dataset (2020–2025) to uncover trends across industries, countries and company stages. Used Python for data cleaning, exploratory analysis and correlation studies, creating clear visualizations to highlight year-over-year changes, sector specific impacts and the weak relationship between funding levels and job security.


### Dataset

The dataset contains information about company layoffs and includes the following columns:

| Column Name         | Data Type   | Description |
|--------------------|------------|------------|
| `company`           | object     | Name of the company |
| `location`          | object     | Location of the company or office affected |
| `total_laid_off`    | float64    | Total number of employees laid off |
| `date`              | object     | Date of the layoff event |
| `percentage_laid_off` | object   | Percentage of workforce laid off |
| `industry`          | object     | Industry sector of the company |
| `source`            | object     | Source of layoff information |
| `stage`             | object     | Funding or growth stage of the company (eg: Series A, Startup) |
| `funds_raised`      | object     | Amount of funds raised by the company (if any) |
| `country`           | object     | Country of the company |
| `date_added`        | object     | Date when the record was added to the dataset |

