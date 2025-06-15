
# 🌍 Energy Consumption Analysis & Projection

This project performs **data cleaning and linear regression-based projections** for global energy consumption by country. It is built using Python and Jupyter Notebook, leveraging `pandas` for data manipulation and `scikit-learn` for forecasting.

---

## 📊 What This Project Does

- Cleans raw energy consumption data for multiple countries.
- Selects the **top energy-consuming countries** for focused analysis.
- Applies **linear regression** per country to estimate energy consumption trends.
- Projects each country's energy consumption up to the year **2028**.
- Compares projected 2028 consumption with **actual 2023 values** (if available).
- (Optional) Calculates **percentage change** between 2023 and 2028.

---

## 📁 Project Structure

```
📦 project/
├── 📒 Energy Consumption Data Cleaning.ipynb
├── 📁 Data/
├── 📁 .ipynb_checkpoints/
├── .gitignore
└── README.md
```

---

## ✅ Requirements

- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📈 Conclusion

The analysis reveals **clear energy consumption trends** across the top countries. By projecting forward using linear regression, we can anticipate how global demand may shift over the next few years. This allows policymakers and researchers to:

- Identify rapidly growing energy consumers,
- Assess sustainability goals,
- Plan infrastructure and energy policy accordingly.

---

## 🔧 Next Steps

- Incorporate other prediction models (e.g., exponential, polynomial)
- Compare against renewable energy share
- Visualize projections with interactive plots

---

## 📜 License

MIT License.
