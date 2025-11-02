# What if Stocks Were Foods?  
### A Nutritional Analysis of the Stock Market  

**Category:** Data Analysis & Visualisation  

---

## Problem Statement / Motivation  

The stock market is a complex ecosystem where investors balance risk and reward much like people balance health and indulgence in their diets. Stable, low-risk stocks act as nutritious staples, while speculative, volatile assets resemble sugary snacks, they are tempting but potentially harmful in excess. This project aims to reframe financial data through the lens of nutrition, offering an intuitive and engaging way to understand investment characteristics. By transforming stock metrics into “nutritional values,” we can provide both novice and experienced investors with a fresh, visual perspective on market behaviour and portfolio composition.

---

## Planned Approach and Technologies  

Using **NASDAQ historical stock data**, I will calculate financial indicators such as returns, volatility, and market capitalization.  
These will be reinterpreted as:  

| Financial Metric | Nutritional Analogy | Description |
|------------------|---------------------|--------------|
| **Returns** | **Calories** | Energy output or growth potential |
| **Volatility** | **Sugar** | Short-term highs and crashes |
| **Market Cap** | **Fat** | Weight or size in the market |

If available, **ESG scores** will add a “nutri-score” dimension representing sustainability and ethical impact.

**Technologies & Libraries:**  
- Data processing: `pandas`, `NumPy`  
- Visualization: `matplotlib`, `seaborn`  

**Planned Visuals:**  
- “Nutrition labels” for individual stocks  
- “Food pyramid of the market” ranking stocks by healthiness  
- Time-series analysis to observe how the “market diet” changes over years  
- Optional: A portfolio simulator comparing the “healthiness” and performance of different investment “meals.”  

---

## Expected Challenges and Solutions  

| Challenge | Approach |
|------------|-----------|
| **Data consistency** | Align datasets by ticker symbols and perform thorough cleaning. |
| **Defining mappings** | Justify and document all metaphorical mappings between financial and nutritional metrics. |
| **Visualization design** | Prototype multiple visual styles to balance aesthetics and clarity before finalizing. |

---

## Success Criteria  

The project will be considered successful if:  
- Stock data is cleaned and transformed into “nutritional” metrics.  
- Visualizations effectively communicate the metaphor (e.g., clear “nutrition labels” and “food pyramid”).  
- Insights can be derived, such as shifts toward “unhealthy” (volatile) market periods.  

---

## Stretch Goals (If Time Permits)  

- Build an **interactive dashboard** using *Streamlit* or *Plotly Dash*.  
- Include **real-time data updates** from financial APIs.  
- Explore **correlations between global economic events** and shifts in the “market diet.”  
