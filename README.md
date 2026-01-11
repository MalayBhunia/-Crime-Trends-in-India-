# 🚔 India Crime Data Analysis (2020 - 2024)

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a comprehensive dataset of crime reports in India. Covering the period from **January 2020 to July 2024**, the analysis aims to uncover patterns in criminal activities, identify high-risk cities, and understand victim demographics and police responsiveness.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:**
  - `Pandas` & `NumPy`: For data cleaning and numerical processing.
  - `Matplotlib` & `Seaborn`: For generating static, high-quality statistical plots.
  - `Plotly`: For interactive data exploration.
  - `Squarify`: For treemap visualizations of crime domains.

## 📁 Data Source
The data was sourced from **Kaggle** (referenced in the notebook as `crime_dataset_india.csv`). 
- **Dataset Size:** 40,160 entries.
- **Timeline:** January 2020 – July 2024.
- **Key Features:** Report Number, Location (City), Crime Description, Victim Age/Gender, Weapon Used, Crime Domain, Police Deployed, and Case Status.

## 🧹 Key Data Processing Steps
- **Date Standardization:** Converted reporting and occurrence dates from strings to DateTime objects for time-series analysis.
- **Handling Missing Values:** Managed null entries in `Weapon Used` and `Date Case Closed` (representing open cases).
- **Categorization:** Streamlined crime descriptions and domains for clearer visualization.

## 🔍 Key Insights & Analysis
1. **Top Crime Hubs:** Identified the top 10 cities with the highest reported crimes, with **Delhi, Mumbai, and Bangalore** leading the list.
2. **Crime Demographics:** Analysis of victim age groups and gender distribution across different crime types.
3. **Police Efficiency:** Correlation analysis between the number of police deployed and the rate of "Case Closed" status.
4. **Temporal Trends:** Yearly and monthly crime reports to identify seasonal peaks or declining trends in major cities.
5. **Crime Domains:** Breakdown of "Violent Crime" vs "Other Crimes" using treemaps.

## 📈 Sample Visualizations
- **Bar Charts:** Top 10 cities by crime volume.
- **Line Graphs:** Year-over-year crime reports for major metros (Delhi, Mumbai, Kolkata, etc.).
- **Categorical Plots:** Experience-level vs. Sector demand (relevant to job-related subsets if applicable).

## 🚀 How to Use
1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/your-username/india-crime-analysis.git](https://github.com/your-username/india-crime-analysis.git)
2. Ensure you have the `.ipynb` and `crime_dataset_india.csv` in the same folder.
3. Run using Jupyter Notebook or VS Code.


## ✍️ Author
**Malay Bhunia**
- GitHub: [@Malay Bhunia](https://github.com/MalayBhunia)
- LinkedIn: [https://www.linkedin.com/in/malay-bhunia-14ab712a6/]
- Portfolio: [https://malaybhunia.github.io/Data_Analyst/]
