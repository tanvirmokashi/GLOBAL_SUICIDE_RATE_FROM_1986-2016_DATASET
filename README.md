# Global Suicide Rate Analysis (1986-2016)

## Objective / Abstract

This project analyzes global suicide rates over a 30-year period (1986-2016), identifying trends and patterns across different countries, genders, age groups, and socio-economic factors. The analysis provides actionable insights to guide mental health policies and initiatives aimed at reducing suicide rates globally.

**Key objectives include:**

- Understanding the factors influencing suicide rates across countries.
- Analyzing the impact of economic indicators like GDP per capita on suicide rates.
- Identifying high-risk demographic groups to support targeted interventions.

---

## Dataset Summary

The dataset contains **27821 rows** and **12 columns**, providing detailed information on global suicide rates categorized by country, gender, age group, and economic indicators. Key columns include:

| **Column Name**         | **Description**                                  |
|--------------------------|-------------------------------------------------|
| `Country`               | Name of the country                             |
| `Year`                  | Year of recorded data                           |
| `Sex`                   | Gender of the individual                        |
| `Age Group`             | Age group of the individual                     |
| `Suicides/100k Pop`     | Suicide rate per 100,000 population             |
| `GDP per Capita`        | Economic indicator per capita                   |
| `HDI`                   | Human Development Index (if available)          |
| `Population`            | Total population of the country                 |
| `Generation`            | Generation of individuals in the data           |
| `Continent`             | Continent where the country is located          |
| `Total Suicides`        | Total suicides in the country for the year       |
| `GDP Total`             | Total GDP of the country for the year            |

---

## Questions Explored

1. **Top Countries**: Which countries have the highest and lowest suicide rates per 100k population?
2. **Gender Differences**: How do suicide rates differ by gender globally? *(Pie Chart)*
3. **Age Group Trends**: How do suicide rates vary across age groups? *(Line Chart)*
4. **Historical Trends**: How have global suicide rates changed over time? *(Line Chart)*
5. **Generational Insights**: Which generations have the highest suicide rates? *(Pie Chart)*
6. **Distribution Analysis**: What is the distribution of average suicide rates across countries? *(Histogram)*
7. **Economic Factors**: What is the relationship between GDP per capita and suicide rates? *(Bar Chart with Line)*
8. **Correlation Analysis**: What is the correlation between suicide rates and factors like GDP per capita, HDI, and population? *(Heatmap)*

---

## Key Findings & Conclusion

### Top and Bottom Countries
- **Highest Rates**: Lithuania, Russia, Belarus (25-35 per 100k population).
- **Lowest Rates**: Dominica, Saint Kitts and Nevis, Jamaica (0.3-0.5 per 100k population).

### Gender Differences
- Males account for 76.9% of global suicides, with significantly higher rates than females.

### Age Group Insights
- Suicide rates peak in older age groups (75+ years), driven by isolation, health issues, and economic challenges.

### Economic Insights
- Mid-range GDP countries (1001-2000 per capita) face higher suicide rates due to transitional stress, while high-GDP nations (>2500 per capita) show reduced rates.

---

## Technologies Used

- **Python**: For data analysis, cleaning, and visualization.
- **SQL (MySQL Workbench)**: For database management and integration.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib, Seaborn**: For creating visualizations.
- **Jupyter Notebook**: For exploratory data analysis.
- **OS Module**: For handling file paths dynamically.

### SQL Integration
The project integrates with MySQL to store and query the dataset. The following steps were performed:

1. The `global_suicide_rate_dataset.csv` was processed using Python and imported into a MySQL database (`global_suicide_rate`) with a table named `suicide_data`.
2. Table creation and data insertion were automated by dynamically mapping column data types.
3. This integration enables efficient querying and further analysis of the dataset.

---

## How to Use

**1. Clone the repository:**
   git clone https://github.com/your-username/global-suicide-analysis.git

   
******2.  Install required Python libraries:**
pip install -r requirements.txt


****3.Set up the MySQL database:**
Create a database named global_suicide_rate.
Use the provided Python script to import the dataset into the suicide_data table.


**4.Run the Jupyter Notebook:
**
jupyter notebook GLOBAL_SUICIDE_RATE_ANALYSIS(1986-2016).ipynb


**Resources**
Dataset: https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016
Python Scripts: For data analysis and SQL integra****tion.
MySQL Workbench: Used for database management.**
