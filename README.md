# microburbs-ilr-metric
# Investment Livability ROI (ILR) Metric  
**Prepared by Nixon Tom – Data Analyst Candidate**

---

## 🏠 Overview  
The **Investment Livability ROI (ILR)** metric helps Australian residential property investors identify suburbs that balance **high financial returns** with **low livability risk**.  
It combines yield and growth with real-world livability data such as crime, schools, and commute — helping investors make data-driven yet practical decisions.

---

## 📊 Metric Formula  

\[
\text{ILR} = \frac{(\text{Rental Yield Score} + \text{Capital Growth Score})}{2} \times (1 - \text{Livability Risk Index})
\]

| Component | Description |
|------------|-------------|
| **Rental Yield Score** | Normalised median rental yield |
| **Capital Growth Score** | Normalised 5-year house price growth |
| **Livability Risk Index (LRI)** | 0–1 index combining crime rate, commute time, vacancy, and school variance |

---

## 🧮 Example  

| Suburb | Rental Yield | 5Y Growth | LRI | ILR | Investment Type |
|---------|---------------|-----------|-----|-----|----------------|
| Oxley, QLD | 4.6% | 3.8% | 0.22 | 0.74 | Balanced Growth |
| Sunnybank, QLD | 3.9% | 5.5% | 0.28 | 0.72 | Growth Focused |
| Ipswich, QLD | 6.1% | 2.1% | 0.35 | 0.65 | Yield Heavy |

---

## 💻 Tech Stack  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook** (for computation and explanation)  

---

## 🧠 Insights  
- **Balanced investors** should target ILR > 0.70 (strong returns, moderate livability risk).  
- **Yield-focused** investors may accept ILR 0.60–0.70 if yields exceed 5%.  
- **Growth-focused** investors prioritise low LRI even at moderate yield (3–4%).  

---

## 📁 Repository Structure  
