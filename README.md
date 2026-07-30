# Streaming Platform Business Intelligence Analysis

## Project Overview

This project compares the content libraries of Netflix, Hulu, Prime Video, and Disney+.

I used movie and TV-show datasets to look at content volume, genre distribution, release years, IMDb ratings, and Rotten Tomatoes scores. After comparing the four platforms, I selected Netflix for the final strategy analysis.

This project was completed as part of the Open Avenues Foundation Build Fellowship.

## Business Objective

The main goal of this project is to identify a realistic strategic opportunity for Netflix based on its current content library and its position against other streaming platforms.

The analysis focuses on the following questions:

- How large is Netflix's content library compared with its competitors?
- What types of content and genres are most common on each platform?
- How does Netflix compare based on IMDb ratings and Rotten Tomatoes scores?
- Where does Netflix have a clear weakness or opportunity?
- What business results could be affected by the recommendation?

## Dataset

The project uses two public datasets:

- Movies on Streaming Platforms
- TV Shows on Streaming Platforms

The datasets include information such as:

- Title
- Release year
- Genre
- IMDb rating
- Rotten Tomatoes score
- Platform availability
- Movie or TV-show classification

Before starting the analysis, I cleaned and standardized the datasets. Numeric columns were converted into usable formats, and records with missing important values were handled during the cleaning process.

The cleaned datasets are stored in the `data/` folder.

## Methodology

The project was completed in five stages:

1. Data exploration
2. Data cleaning and preparation
3. Industry-level exploratory analysis
4. Cross-platform comparison
5. Netflix strategy analysis

Python and Pandas were used for data preparation and analysis. Matplotlib was used to create the charts.

## Key Findings

- Netflix has one of the largest content libraries in the dataset.
- Movies make up about two-thirds of Netflix's catalog.
- Netflix has a broad range of genres and a strong concentration of newer titles.
- Disney+ has a smaller catalog with a stronger focus on family and franchise content.
- Netflix's average movie Rotten Tomatoes score is 54.4.
- This is lower than Hulu's score of 60.4 and Disney+'s score of 58.3.
- Netflix's average TV-show Rotten Tomatoes score is 53.6, which is still competitive in this comparison.
- The results suggest that Netflix's main issue is not the size of its movie catalog, but the average quality of its movies.

## Strategic Recommendation

Netflix should put less emphasis on adding more movies and more emphasis on improving the quality of future movie releases.

The data shows that Netflix already has a large movie catalog. However, its average movie Rotten Tomatoes score is lower than Hulu's and Disney+'s.

Because of this, simply adding more movies may not create a stronger advantage. A better approach would be to invest more selectively in future movies with stronger quality potential.

This could help Netflix:

- Improve audience satisfaction
- Increase content engagement
- Strengthen its competitive position
- Reduce subscriber churn
- Support long-term subscriber retention

## Expected Business Impact

| Metric | Possible Impact |
|---|---|
| Content engagement | Users may spend more time watching higher-quality content |
| Retention rate | Satisfied users may be more likely to keep their subscriptions |
| Churn rate | Better content may reduce cancellations |
| Brand differentiation | Stronger movies may help Netflix stand out from competitors |
| Revenue | Higher retention may help protect subscription revenue |

### Illustrative Revenue Scenario

To show the possible financial importance of retention, I created a simple scenario using Netflix's 2021 figures.

- Average paying memberships: 210.8 million
- Illustrative retained-membership scenario: 1%
- Additional paying memberships retained: about 2.1 million
- Average monthly revenue per paying membership: $11.67
- Annual revenue per paying membership: $140.04
- Estimated annual streaming revenue protected: about $295 million

This is only an illustrative estimate. It is not a financial forecast.

**Source:** Netflix 2021 Annual Report.

## Repository Structure

```text
streaming-bi-svod/
├── data/
├── figures/
├── notebooks/
├── presentation/
├── src/
├── .gitignore
├── README.md
└── requirements.txt
```

## Repository Guide

| Folder or File | Description |
|---|---|
| `data/` | Cleaned datasets used in the analysis |
| `notebooks/` | Jupyter notebooks for data cleaning and analysis |
| `figures/` | Charts created during the project |
| `presentation/` | Final PowerPoint presentation |
| `src/` | Reusable Python scripts and helper functions |
| `requirements.txt` | Required Python packages |
| `README.md` | Project overview and instructions |

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git
- GitHub
- Microsoft PowerPoint

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/irgen-gu1/streaming-bi-svod.git
cd streaming-bi-svod
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the virtual environment on Windows

```bash
.venv\Scripts\activate
```

### 4. Install the required packages

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
python -m notebook
```

### 6. Run the notebooks

Open the notebooks and run them in numerical order, starting with data exploration and ending with the final strategy analysis.

## Author

**Naqiao Gu**

M.S. in Applied Business Analytics  
Boston University
