# Saudi-Arabia-Real-Estate-Rental-Market-EDA-Project-
This project explores a **Saudi Arabian rental property dataset** sourced from Kaggle (~2019–2020 snapshot, pre-COVID era).   The dataset contains **3,718 property listings** across major cities: **Riyadh, Jeddah, Dammam, and Khobar**.  
## 📖 Project Overview
This project explores a **Saudi Arabian rental property dataset** sourced from Kaggle (~2019–2020 snapshot, pre-COVID era).  
The dataset contains **3,718 property listings** across major cities: **Riyadh, Jeddah, Dammam, and Khobar**.  

The goal is to perform **data cleaning, exploratory data analysis (EDA), and visualization** to uncover rental market insights and highlight storytelling with data.

---

## 🔑 Key Highlights
- ✅ **Data Cleaning:** Removed duplicates, handled missing values, and filtered extreme outliers (prices > 1.7M SAR, unrealistic sizes).  
- ✅ **Exploratory Analysis:** Price distributions, city-level averages, size/bedroom trends, correlations.  
- ✅ **Market Alignment:** Dataset reflects **premium villa rentals** (not budget apartments) from ~5 years ago.  
- ✅ **Storytelling:** Numbers align with **pre-COVID premium market ranges** in Saudi Arabia (Jeddah > Riyadh > Khobar > Dammam).  

---

## 🧹 Data Preparation
- Dropped irrelevant columns (`maid_room`, `driver_room`, `elevator`, etc.)  
- Removed **2,197 duplicate rows**  
- Handled minimal missing values (only in `details`)  
- Treated **outliers** in `price` and `size`  

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Price Distribution
- Median: ~70,000 SAR/year  
- Mean: ~87,000 SAR/year  
- Skewed by luxury outliers  

### 2. City-Level Averages
| City     | Avg Rent (SAR) | Median Rent (SAR) |
|----------|---------------|------------------|
| Jeddah   | 112k          | 95k              |
| Riyadh   | 94k           | 80k              |
| Khobar   | 79k           | 75k              |
| Dammam   | 75k           | 60k              |

### 3. Bedrooms & Bathrooms
- Majority: **4–6 bedrooms, 4–5 bathrooms**  
- Rent increases with bedrooms but stabilizes after 5+  

### 4. Size vs Price
- Larger size → higher rent, but weak correlation  
- **City/location is the strongest driver** of price  

### 5. Correlation Heatmap
- Price moderately correlates with `size` and `bedrooms`  
- Strongest relationship: **city → price**  

---

## 📈 Market Context
- Dataset matches **pre-COVID villa rents** in Saudi Arabia:  
  - Jeddah/Riyadh → 80k–120k SAR  
  - Dammam/Khobar → 60k–85k SAR  
- Current 2025 averages differ, but dataset is a **faithful snapshot of the premium market 5 years ago**.  

---

## 🖋️ Key Takeaways
1. Dataset is **villa-heavy and premium-focused**.  
2. Rental hierarchy is consistent: **Jeddah > Riyadh > Khobar > Dammam**.  
3. Outliers needed removal for reliable insights.  
4. Location matters more than size or features in determining rent.  

---

## 🚀 Skills Demonstrated
- Data Cleaning & Preprocessing (Pandas, NumPy)  
- Exploratory Data Analysis (EDA)  
- Data Visualization (Matplotlib, Seaborn)  
- Storytelling with Data  
- Contextualizing findings with real-world market trends  
