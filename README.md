# 🏅 Nobel Prize Data Analysis

## 📖 Project Background
This project analyzes historical **Nobel Prize** data to uncover trends, patterns, and insights about laureates across time, countries, genders, and categories. The notebook follows a guided exploratory data analysis (EDA) approach, combining data cleaning, visualization, and interpretation.

The analysis is inspired by Alfred Nobel’s vision of rewarding those who contribute the *greatest benefit to humankind*.

---

## 🎯 Project Objectives

- Explore and clean Nobel Prize data  
- Analyze long-term trends in Nobel awards  
- Study country and category dominance  
- Examine gender representation  
- Investigate age patterns of laureates  
- Practice real-world exploratory data analysis  

---

## 📂 Dataset

**Dataset file:** `nobel_prize_data.csv`

The dataset contains:

- Laureate name  
- Gender  
- Birth date  
- Country of birth  
- Award year  
- Prize category  
- Prize share  
- Individual vs organization winners  

> Note: Some birth dates were estimated where exact data was unavailable.

---

## 🛠 Libraries Used

| Library | Purpose |
|--------|---------|
| pandas | Data manipulation & cleaning |
| numpy | Numerical operations |
| plotly | Interactive visualizations |
| matplotlib | Data plotting |
| seaborn | Statistical visualization |
| ydata-profiling | Automated EDA report |

---

## ⚙️ Notebook Structure

### 1️⃣ Setup & Context
- Introduction to the Nobel Prize history  
- Library imports  
- Environment setup  

### 2️⃣ Data Loading
- Reading dataset into a pandas DataFrame  
- Initial inspection of data  

### 3️⃣ Data Exploration & Cleaning
- Checking dataset dimensions  
- Inspecting column names  
- Finding first and latest Nobel Prize year  
- Detecting duplicates  
- Identifying missing values  
- Preparing data for analysis  

### 4️⃣ Exploratory Data Analysis (EDA)

#### 📅 Nobel Prizes Over Time
- Number of prizes awarded per year  
- Historical trends  

#### 🧪 Prize Categories
Distribution of awards across:
- Physics  
- Chemistry  
- Medicine  
- Literature  
- Peace  
- Economics  

#### 🌍 Country Analysis
- Countries with the most laureates  
- Global research dominance  

#### 👩‍🔬 Gender Representation
- Male vs female laureates  
- Trend of female participation  

#### 🎂 Age Analysis
- Age of laureates at time of award  
- Youngest and oldest winners  

#### 👤 Individuals vs Organizations
- Comparison between institutional and individual laureates  

---

## 📊 Visualizations

The notebook includes:

- Time-series charts  
- Category distribution graphs  
- Country comparison charts  
- Gender distribution visuals  
- Interactive Plotly dashboards  

---

## ▶️ How to Run

1. Install required packages:

```bash
pip install pandas numpy plotly matplotlib seaborn ydata-profiling
ter or Google Colab and run the cells.
