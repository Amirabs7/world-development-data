# 🌍 World Development Data Analysis

This project analyzes global development indicators such as life expectancy, GDP per capita, literacy, and income class. It uncovers key social and economic patterns across countries using data cleaning, filtering, and interactive visualizations.
This dataset presents a compilation of averaged world development indicator data spanning the years **2015 to 2018**, amalgamated from various reputable sources:

The World Bank - Providing data on population, income classification, pollution levels, access to electricity, life expectancy, and more.
World Happiness Report - Offering insights into social support, generosity, and freedom to make life choices.
Transparency International - Source of data regarding the corruption perceptions index.

---

## What this project shows
- Multi-source global dataset analysis and cleaning using Python (pandas, matplotlib, plotly)
- Socio-economic insights and identification of countries at risk or performing well
- Reproducible project for data interpretation for policy/research

---

## 📁 Dataset & Scope

Dataset source : https://www.kaggle.com/datasets/keithvincentburca/world-development-data
This data has already been manipulated, cleaned and transformed by the author. Further data processing might be required. 

---

## 🧪 Methods & Tools  

- pandas
- plotly.express	
- matplotlib.pyplot	
- seaborn
- colab.files	

---

## 📌 Project Features

- ✅ Cleans and prepares world development data
- 📊 Compares Norway, India, and Brazil across key development indicators
- 📉 Identifies countries failing basic needs (electricity, literacy, GDP, water, life expectancy)
- ⚠️ Flags countries with risky social indicators (e.g., high alcohol + low support)

---

# 📊 Key Visualizations

### GDP vs Life Expectancy
![GDP and Life Expectancy](https://raw.githubusercontent.com/Amirabs7/world-development-data/main/GDP%20per%20capita%20vs%20life%20expectancy.png)


### Correlations Between Variables
![Correlations Analysis](https://raw.githubusercontent.com/Amirabs7/world-development-data/main/Correlations%20btw%20variables.png)


---


## 📊 Key Insights from the Data

Our analysis of global development indicators uncovered several compelling trends—and a few red flags:

1- Wealth & Well-Being, GDP per Capita ↔ Happiness
- There's a clear positive correlation—richer countries tend to report higher happiness levels.

2- Income Class ↔ Happiness
- A country’s income classification is a strong predictor of happiness. High-income nations are generally more satisfied.

3- People & Place -Population Density ↔ Happiness
- The data shows a weak or no correlation—being densely populated doesn't significantly impact national happiness.

4- Country-Level Variation
- Even within the same income class, happiness levels vary widely. Culture, governance, and social trust likely play major roles.

5-Educated but Still Poor: The Human Capital Paradox
- Some countries—like Kyrgyzstan and Uzbekistan—have achieved near-universal literacy, yet remain economically underdeveloped. This reveals a major underutilization of human capital. It’s a red flag: education alone isn’t enough without robust economic opportunities, governance, and innovation ecosystems.

---


## 🚀 How to Run the Project

1. Clone this repository
git clone <repo-link>

2. Install dependencies
pip install -r requirements.txt

3. Run the analysis
python world_development_data.py



---


## 👩‍💻 Author

**Amira Ben Salem**  
📫 Email: besamira77@gmail.com  
📍 Berlin, Germany  






