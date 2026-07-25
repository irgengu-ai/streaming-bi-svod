# Streaming Platform Business Intelligence Analysis

## Project Overview

This project analyzes the content strategies of major streaming video-on-demand platforms, including Netflix, Hulu, Prime Video, and Disney+.

The analysis combines movie and TV show datasets to compare platform content volume, genre distribution, release-year patterns, and audience ratings. Netflix was selected for the platform-level strategic analysis.

This project was completed as part of the Open Avenues Foundation Build Fellowship.

## Business Objective

The objective of this project is to identify strategic opportunities for Netflix based on its content portfolio and competitive position.

The analysis addresses the following questions:

- How does Netflix's content library compare with competing platforms?
- Which genres and content types dominate each platform?
- How does Netflix perform based on IMDb and Rotten Tomatoes ratings?
- What strategic action could improve Netflix's competitive position?
- Which business metrics could be affected by the recommendation?

## Dataset

The project uses two publicly available datasets:

- Movies on Streaming Platforms
- TV Shows on Streaming Platforms

The datasets contain information including:

- Title
- Release year
- Genre
- IMDb rating
- Rotten Tomatoes rating
- Platform availability
- Movie or TV show classification

The raw datasets were cleaned and standardized before analysis. Key numeric fields were converted into appropriate formats, and records with missing essential fields were handled during the cleaning process.

The cleaned datasets used for analysis are included in the `Data/` folder.

## Methodology

The project follows five main stages:

1. Data exploration
2. Data cleaning and preparation
3. Industry-level exploratory data analysis
4. Streaming platform comparison
5. Netflix strategic analysis and recommendation

Python and Pandas were used for data preparation and analysis. Matplotlib was used to create the visualizations.

## Key Findings

- Netflix has one of the largest content libraries among the platforms in the dataset.
- Netflix emphasizes high content volume and broad genre coverage.
- Disney+ has a stronger concentration in franchise-driven and family-oriented content.
- Netflix's large catalog does not always produce the strongest average audience ratings.
- Netflix could benefit from placing greater emphasis on high-quality content rather than maximizing content quantity alone.

## Strategic Recommendation

Netflix should reduce its emphasis on catalog expansion and invest more selectively in higher-quality future titles.

This recommendation is supported by the platform comparison, which indicates that Netflix has a large catalog but does not consistently achieve the strongest average ratings compared with selected competitors.

A stronger focus on content quality could:

- Improve audience satisfaction
- Increase content engagement
- Strengthen platform differentiation
- Reduce subscriber churn
- Support long-term subscriber retention

## Expected Business Impact

| Metric | Expected Impact |
|---|---|
| Content engagement | Users may spend more time watching higher-quality content |
| Retention rate | Satisfied subscribers may be more likely to remain subscribed |
| Churn rate | Improved content quality may reduce cancellations |
| Brand differentiation | A stronger portfolio of high-quality content can improve Netflix's competitive identity |
| Revenue | Higher retention may support recurring subscription revenue |

The expected impact is directional and should not be interpreted as a guaranteed financial forecast.

## Repository Structure

~~~text
streaming-bi-svod/
├── Data/
├── notebooks/
├── figures/
├── presentation/
├── src/
├── requirements.txt
└── README.md
~~~

## Repository Guide

| Folder or File | Description |
|---|---|
| `Data/` | Cleaned streaming datasets used for analysis |
| `notebooks/` | Jupyter notebooks used for cleaning and analysis |
| `figures/` | Exported charts and visualizations |
| `presentation/` | Final presentation files |
| `src/` | Reusable Python scripts and helper functions |
| `requirements.txt` | Python package requirements |
| `README.md` | Project overview and documentation |

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

1. Clone the repository.

~~~bash
git clone https://github.com/irgengu-ai/streaming-bi-svod.git
cd streaming-bi-svod
~~~

2. Create a virtual environment.

~~~bash
python -m venv .venv
~~~

3. Activate the virtual environment on Windows.

~~~bash
.venv\Scripts\activate
~~~

4. Install the required packages.

~~~bash
pip install -r requirements.txt
~~~

5. Launch Jupyter Notebook.

~~~bash
python -m notebook
~~~

6. Open the notebooks and run them in numerical order.

## Author

**Naqiao Gu**

M.S. in Applied Business Analytics  
Boston University