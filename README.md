# 🦠 COVID-19 Data Analysis – Project 2

Exploratory data analysis (EDA) of COVID-19 statistics for **225 countries**, using Python, Pandas, Seaborn and Matplotlib.

The project cleans the dataset, ranks countries by cases, deaths and death percentage, compares continents, and explores relationships between variables with scatter plots and a Spearman correlation heatmap.

---

## 📂 Repository Structure

```
├── COVID19_Project2.ipynb      # Main analysis notebook
├── COVID-19_Coronavirus.csv    # Dataset (225 rows × 10 columns)
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 📊 Dataset

The dataset contains **225 rows and 10 columns**:

| Column | Description |
|---|---|
| Country | Country name |
| Other names | Alternate country name |
| ISO 3166-1 alpha-3 CODE | 3-letter country code (renamed to `Iso_Code`) |
| Population | Total population |
| Continent | Continent / region |
| Total Cases | Total confirmed COVID-19 cases |
| Total Deaths | Total COVID-19 deaths |
| Tot Cases//1M pop | Total cases per 1 million people |
| Tot Deaths/1M pop | Total deaths per 1 million people |
| Death percentage | Deaths as a percentage of total cases |

---

## 🔍 What the Notebook Covers

1. **Data loading and inspection**: shape, `head()`, `tail()`, `info()`
2. **Data cleaning**: found 1 missing value in `Other names` (Montenegro) and filled it; renamed `ISO 3166-1 alpha-3 CODE` to `Iso_Code`
3. **Descriptive statistics** using `describe()`
4. **Country rankings** (with bar plots):
   - Top 5 and bottom 5 countries by total cases
   - Top 5 and bottom 5 countries by total deaths
   - Top 5 countries by death percentage
5. **Continent-wise analysis** of total cases using `groupby()`
6. **Relationship analysis**:
   - Population vs Total Cases (scatter plot)
   - Total Cases vs Total Deaths (scatter plot)
   - Spearman rank correlation matrix (heatmap)

---

## 📈 Key Findings

- **Most cases:** USA (81.8M), followed by India (43.0M), Brazil (30.0M), France (26.0M) and Germany (21.6M)
- **Most deaths:** USA (about 1.01M), followed by Brazil (660K), India (521K), Russia (370K) and Mexico (323K)
- **Highest death percentage:** Yemen (18.15%), followed by Western Sahara (10.0%), Sudan (7.92%), Peru (5.98%) and Mexico (5.71%)
- **By continent:** Europe recorded the most total cases (about 180.3M), followed by Asia (141.0M), Northern America (85.4M), Latin America and the Caribbean (67.5M), Africa (11.8M) and Oceania (5.6M)
- **Lowest cases:** Micronesia (1), Saint Helena (2), Marshall Islands (7), Niue (7) and Western Sahara (10)
- **Zero reported deaths:** Cook Islands, Falkland Islands, Macao, Marshall Islands and Micronesia
- Raw case counts and death percentage tell different stories: a country with fewer reported cases can still show a very high death percentage.

---

## 🛠️ Tech Stack

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. Install the dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter and open the notebook
   ```bash
   jupyter notebook COVID19_Project2.ipynb
   ```

Make sure `COVID-19_Coronavirus.csv` is in the same folder as the notebook.

---

## 💡 Skills Demonstrated

- Data cleaning and handling missing values
- Exploratory data analysis (EDA)
- Aggregation with `groupby()`
- Data visualisation (bar plots, scatter plots, heatmap)
- Correlation analysis (Spearman)

---

## 🙏 Acknowledgement

Thank you to **[Sir's Name]** for the guidance and support throughout this project.

---

## 👤 Author

**[Your Name]**
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) | 💻 [GitHub](https://github.com/your-username)

---

⭐ If you found this project useful, consider giving it a star!
