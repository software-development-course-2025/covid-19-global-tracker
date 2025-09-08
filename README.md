# COVID-19 Global Data Tracker

### Author
- **Name:** Augusto Mate
- **GitHub:** https://github.com/Augusto047

---

### Project Overview

This project is an in-depth data analysis of global COVID-19 trends. The goal was to process, analyze, and visualize data related to cases, deaths, and vaccinations across selected countries. The final report is presented in a Jupyter Notebook, combining code, visualizations, and a narrative summary of key findings.

---

### 📋 Table of Contents
- [Project Objectives](#project-objectives)
- [Files and Data Source](#files-and-data-source)
- [Tools and Libraries](#tools-and-libraries)
- [Conclusions and Insights](#conclusions-and-insights)
- [How to Run the Project](#how-to-run-the-project)
- [Pertinent Observations](#pertinent-observations)
- [License](#license)

---

### 🎯 Project Objectives

- **Data Processing:** Import and clean a real-world COVID-19 dataset.
- **Exploratory Data Analysis (EDA):** Analyze time-series trends and compare key metrics across countries.
- **Data Visualization:** Create insightful charts and a choropleth map to illustrate the metrics.
- **Insight Communication:** Present findings in a clear and well-structured report.

---

### 📂 Files and Data Source

Due to GitHub's file size limit, the `compact.csv` dataset (~150 MB) could not be uploaded to this repository. The file is available for download from its original source:

**[Download the COVID-19 Dataset (compact.csv)](https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv)**

To run the notebook successfully, please download this file and place it in the project's root folder.

- **`covid_analysis.ipynb`**: The Jupyter Notebook containing all the code and analysis.

---

### 🛠️ Tools and Libraries

-   Python
-   `pandas` (for data manipulation and analysis)
-   `matplotlib` (for time-series plotting)
-   `plotly.express` (for interactive visualizations, including the map)
-   Jupyter Notebook

---

### 🧠 Conclusions and Insights

#### Overview of Cases and Deaths

The initial analysis of cumulative case and death data reveals that the United States and India had the highest absolute totals among the countries studied. This outcome is not surprising given their large populations, which make them key reference points for understanding the scale of the pandemic.

#### Mortality Rate: An Indicator of Severity

Although Brazil's total case and death counts do not surpass those of the U.S. and India, the analysis of the **mortality rate** (total deaths / total cases) offers a different perspective. With a rate of **6.99%**, Brazil showed the highest proportion of deaths relative to confirmed cases. This figure is crucial for understanding the severity of the pandemic’s impact, demonstrating that the seriousness of the disease in a country can be high regardless of the total case volume.

#### Linking Vaccination to Case Trends

The vaccination analysis highlights differing adoption and distribution trends across countries. India showed a sharply accelerating vaccination curve. In contrast, the vaccination in South Africa appeared to experience a slowdown, and the data from Brazil and the United States indicates that mass vaccination reached a plateau by 2023. A visual correlation can be observed between increased vaccination and the stabilization or decline in case and death curves in some countries, suggesting a positive impact from vaccination campaigns.

---

### 🚀 How to Run the Project

1.  **Clone the Repository:** `git clone https://github.com/software-development-course-2025/covid-19-global-tracker.git`
2.  **Download the Dataset:** Download the `compact.csv` from the link above and place it in the same folder.
3.  **Install Dependencies:** `pip install pandas matplotlib plotly jupyter`
4.  **Run the Notebook:** `jupyter notebook covid_analysis.ipynb`

---

### 📝 Pertinent Observations

- This project was conducted as part of the Python module in a broader Software Development curriculum. 
- The data is based on public records and may be subject to updates. 
- The analysis reflects the data available up to the last download date.

---

### License

This project is licensed under the MIT License.  
For more details, see the [LICENSE](.LICENSE) file.
