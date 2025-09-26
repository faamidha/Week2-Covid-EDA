# Week2-Covid-EDA

# 📜 COVID-19 Data Exploratory Analysis (EDA)

This repository contains a Jupyter Notebook (`Week2_Covid_19_EDA.ipynb`) that performs a basic Exploratory Data Analysis (EDA) on a snapshot of COVID-19 case data.

The notebook focuses on data cleaning, initial inspection, and visualizing key metrics like global case trends and the distribution of confirmed cases, deaths, and recoveries across different countries and WHO regions.

***

## 📊 Analysis Highlights

The EDA covered in the notebook includes:

* **Data Quality Checks**: Verification of data types, missing values, and duplicate rows.
* **Descriptive Statistics**: Summary statistics for key numerical features (e.g., Confirmed, Deaths, Recovered).
* **Geographical Analysis**: Identifying the **Top 10 Countries** by total confirmed cases and deaths.
* **Visualization**:
    * Plotting the **Global Confirmed Cases Over Time** (using the row index as a proxy for time/day).
    * Bar plot showing the **Top 10 Countries by Total Deaths**.
    * Pie chart illustrating the **Global Ratio of Recovered Cases vs. Deaths**.

***

## 🛠️ Requirements and Setup

To run this notebook, you need a Python environment with the following libraries installed:

* `pandas`
* `matplotlib`
* `seaborn`
* `google.colab` (if running directly in Google Colab)

### Local Setup

1.  **Clone the repository:**
    ```bash
    git clone [Your-Repo-URL]
    cd [Your-Repo-Name]
    ```
2.  **Install dependencies** (if you're not using Colab):
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Data Source**: The notebook expects a CSV file named `covid_data.csv` to be uploaded or placed in the same directory.
4.  **Open the notebook:**
    ```bash
    jupyter notebook Week2_Covid_19_EDA.ipynb
    ```

### Google Colab Setup

1.  Open the `Week2_Covid_19_EDA.ipynb` file directly in Google Colab.
2.  The first code cell uses the `google.colab.files.upload()` function to prompt you to upload the necessary data file (`covid_data.csv`).

***

## 📈 Key Findings from the Notebook

Based on the dataset used:

1.  **Data Integrity**: The dataset was found to have **no missing values** and **no duplicate rows**, ensuring high data quality for the analysis.
2.  **Top Affected Countries**: The top countries by confirmed cases and deaths were clearly identified (e.g., the **US** and **Brazil** consistently lead the lists).
3.  **Global Outcome Ratio**: The global analysis showed that the **Recovered** cases significantly outnumbered the **Deaths** in the provided snapshot.

***


