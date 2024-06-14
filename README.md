# SpaceY Falcon 9 Launch Analysis and Prediction

## Project Overview

The commercial space age is here, making space travel more affordable and accessible. Companies like SpaceX have revolutionized space travel by reducing costs, primarily through the reuse of rocket stages. SpaceX's Falcon 9 rocket, with its reusable first stage, is a prime example of this innovation.

This project, undertaken for SpaceY, a new competitor in the space industry founded by billionaire industrialist Elon Musk, aims to analyze and predict the outcomes of Falcon 9 launches. Specifically, we will determine the price of each launch and predict whether the first stage will be successfully reused.

## Objectives

- **Data Collection:** Gather detailed launch data from the SpaceX REST API and web scraping sources.
- **Data Wrangling:** Clean and pre-process the data, handling missing values and transforming the data for analysis.
- **Exploratory Data Analysis (EDA):** Perform statistical analysis and data visualization to uncover insights and relationships between variables.
- **Predictive Modeling:** Build, evaluate, and refine machine learning models to predict the likelihood of first stage reuse.
- **Presentation:** Create informative dashboards and visualizations, and prepare a comprehensive presentation of the findings.

## Data Sources

- **SpaceX REST API:** The primary source of launch data.
    - API Endpoint: `https://api.spacexdata.com/v4/launches/past`
- **Web Scraping:** Supplementary data from Wikipedia and other sources using BeautifulSoup.

## Tools and Technologies

- **Programming Languages:** Python
- **Libraries:** 
    - Data Collection: `requests`, `BeautifulSoup`
    - Data Wrangling and Analysis: `pandas`, `numpy`
    - Data Visualization: `matplotlib`, `seaborn`, `Plotly`
    - Machine Learning: `scikit-learn`
- **SQL:** For querying and analyzing data
- **Visualization Tools:** Tableau, Power BI, or similar

## Project Structure

- **data/**: Directory to store raw and processed data files
- **notebooks/**: Jupyter notebooks for data exploration, analysis, and modeling
- **scripts/**: Python scripts for data collection, cleaning, and pre-processing
- **visualizations/**: Plots, graphs, and dashboards created during the project
- **models/**: Trained machine learning models
- **presentation/**: Final presentation files and visualizations

## Steps to Reproduce

1. **Clone the repository:**

     ```sh
     git clone https://github.com/yourusername/SpaceY-Falcon9-Launch-Analysis.git
     cd SpaceY-Falcon9-Launch-Analysis
     ```
