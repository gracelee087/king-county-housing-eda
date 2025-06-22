# 🏠 King County Housing Data Analysis


## 📘 Project Overview  
This project is part of a Data Science Bootcamp and focuses on **Exploratory Data Analysis (EDA)** of King County housing data.  
The main objective is to extract actionable insights and make recommendations for a specific client profile.

- **Dataset**: King County Housing Data (via `eda` schema)
- **Tools Used**: Python, Pandas, Seaborn, Matplotlib, SQL (DBeaver + SQLAlchemy), Jupyter Notebook

### 👤 Client Profile

- **Name**: Nicole Johnson  
- **Demographics**: Single, Male, No prior home purchases  
- **Budget**: $411K – $707K (mid-range)  
- **Priorities**: Location > Size  
- **Preferred Neighborhoods**: Walkable and vibrant areas

---

## 🛠 Project Structure

```
king-county-eda/
├── data/ # Raw CSV data (excluded from repo)
├── notebooks/
│ ├── EDA.ipynb # Main EDA notebook
│ └── 1_Fetching_the_data_eda.ipynb
├── presentation/
│ └── EDA_FINAL.pdf # Client presentation (final slides)
├── column_names.md # Dataset column descriptions
├── README.md # Project overview and documentation
```

---

## 🔍 Methods & Libraries

### 🗂️ Database & Querying
- DBeaver, SQL, SQLAlchemy for data extraction and inspection

### 🐍 Python Libraries
- `pandas`: Data cleaning, transformation, handling missing values (`isna()`), basic stats (`describe()`)
- `numpy`: Numerical operations
- `matplotlib`, `seaborn`: Visualization (histograms, scatterplots)
- `datetime`: Date parsing and year extraction (`pd.to_datetime()`, `.dt.year`)

### 🔎 Key Analytical Techniques
- `df.describe()` – Summary statistics (mean, std, quartiles)
- `sns.histplot()` – Price distribution with KDE
- `sns.scatterplot()` – Price vs. square footage analysis
- Derived metrics: `price_per_sqft` for standardized comparison
- Time series analysis based on year of sale

---

## 📎 Deliverables

- ✅ Jupyter Notebooks with full EDA and insights
- ✅ GitHub repo with organized file structure

---

## 👩‍💼 Assumptions

- **City Core**: Defined using ZIP codes in Downtown, Belltown, Capitol Hill, and First Hill
- **Affordability**: Determined by Nicole’s budget range and average square footage
- **Contextual Factors**: Economic indicators (employment, interest rate) referenced from 2014–2015 data

---

## 📌 Future Improvements

- 📅 Expand analysis to include 2016 housing data
- 🤖 Apply machine learning for price prediction
- 📈 Include rent-vs-buy decision analysis for broader insights
