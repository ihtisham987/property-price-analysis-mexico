# 🏡 Property Price Analysis in Mexico

This project explores how property sale prices in Mexico are influenced by **property size** and **location** using data from the real estate platform [Properati.com](https://www.properati.com.mx). 

The analysis is performed on a dataset of 21,000 property listings to answer the core question:

> 🧠 *Are property prices in Mexico more influenced by the size of the property or its location?*

---

## 📊 Project Goals

- Clean and prepare the data using `pandas`.
- Visualize relationships using scatter plots and box plots with `matplotlib` and `seaborn`.
- Investigate the correlation between property size, location, and price.
- Provide insights and conclusions using exploratory data analysis (EDA).

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```bash
property-price-analysis-mexico/
│
├── data/
│   └── properties_mexico.csv           # Raw dataset (21,000 listings from Properati)
│
├── notebooks/
│   └── 01-data-cleaning.ipynb          # Data cleaning and preprocessing
│   └── 02-exploratory-analysis.ipynb   # Data visualization and insights
│
├── images/
│   └── boxplots.png
│   └── scatterplots.png
│
├── README.md
└── requirements.txt
