# matplotlib-challenge-

# Pymaceuticals Animal Study Analysis

This project contains the analysis of a recent animal study conducted by Pymaceuticals, Inc., which specializes in developing anti-cancer medications. The study aimed to evaluate the effectiveness of various drug regimens in treating squamous cell carcinoma (SCC), a common form of skin cancer. The primary focus of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

## Overview

In this study, 249 mice diagnosed with SCC tumors were treated with different drug regimens over a 45-day period. Tumor development was observed and measured to assess the effectiveness of each treatment. The study's objective was to provide insights into how Capomulin compares to other treatments in terms of tumor volume reduction and overall efficacy.

## Analysis Overview

The analysis in this repository includes:

- **Data Cleaning and Preparation**: The raw data is processed to remove duplicates and handle missing values.
- **Statistical Analysis**: Calculation of key statistics, including tumor volume changes, quartiles, interquartile ranges (IQRs), and detection of potential outliers.
- **Visualizations**: Various plots and charts, including:
  - Bar plots showing the distribution of treatment regimens
  - Pie charts representing the distribution of male and female mice used in the study
  - Box plots for tumor volume distributions and outlier detection
  - Line plots showing the tumor volume progression over time for each treatment group
- **Outlier Detection**: Identification of any potential outliers based on tumor volume data for each treatment regimen.
- **Top-Level Summary**: Key takeaways and conclusions from the study results, including the performance of Capomulin relative to other treatments.

## Key Findings

- **Capomulin** was found to be one of the most effective treatments, with no significant outliers in the tumor volume data.
- **Infubinol** showed a potential outlier in the tumor volume, which may require further investigation.
- Other treatments like **Ramicane** and **Ceftamin** did not show any outliers and exhibited moderate efficacy.

## Technologies Used

- **Python**: For data analysis and visualization.
  - **Pandas**: For data manipulation and cleaning.
  - **Matplotlib**: For creating various visualizations like plots and charts.
  - **SciPy**: For statistical analysis, including outlier detection and linear regression.
- **Jupyter Notebook**: Used to run the analysis in an interactive environment, allowing for step-by-step exploration and visualization of the data.

## Folder Structure

- `data/`: Folder containing the raw data files.
- `notebooks/`: Jupyter notebooks with the analysis and visualizations.
- `outputs/`: Folder for storing generated figures and reports.
- `scripts/`: Python scripts for performing data cleaning, analysis, and plotting.

## How to Run

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/atnafb/matplotlib-challenge-.git
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and run the Jupyter notebooks in the `notebooks/` folder to view the analysis and visualizations.



---

Thank you for exploring the Pymaceuticals Animal Study Analysis!
