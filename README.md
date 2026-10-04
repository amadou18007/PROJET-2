# Do Highly Rated Books Tend to Be More Expensive?

## Research Question

Do highly rated books tend to be more expensive?

## Objective

This project investigates whether there is a relationship between book ratings and prices.

The analysis aims to determine whether books with higher ratings tend to have higher prices.

## Data Collection

The dataset was collected through web scraping using Python.

The data was scraped from:

https://books.toscrape.com/

The collected information includes book titles, prices and ratings.

## Methodology

The project follows several steps:

1. Web scraping of book data
2. Data cleaning and preparation
3. Exploratory data analysis
4. Visualization of ratings and prices
5. Comparison of prices across rating levels
6. Statistical testing

A boxplot was used to compare price distributions across different rating levels.

A statistical test was also performed to assess whether the observed difference in prices was significant.

## Variables

The main variables used in the analysis are:

- **Title** — Book title
- **Price** — Book price
- **Rating** — Book rating from 1 to 5

## Potential Confounding Factors

Several factors could influence both book ratings and prices, including:

- Genre
- Author
- Publisher
- Book length
- Production cost

These potential confounders were considered through a conceptual Directed Acyclic Graph (DAG).

## Results

The analysis found a **weak relationship between book ratings and prices**.

The statistical test resulted in a **p-value of 0.251**, which does not provide sufficient evidence to conclude that book ratings are significantly associated with prices. :chatgpt-content-reference{index="1"}

The boxplot also shows that price distributions overlap substantially across rating levels. :chatgpt-content-reference{index="2"}

## Tools & Technologies

- Python
- BeautifulSoup
- Requests
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Key Takeaway

Highly rated books are not necessarily more expensive.

The analysis suggests that rating alone does not explain book prices, and other factors such as genre, author, publisher or production costs may play a role.

## Files

- `PriceRatings.ipynb` — Main analysis and web scraping
- `databooks.csv` — Scraped dataset
- `codebook` — Variable documentation

## Author

**Amadou Sow**
