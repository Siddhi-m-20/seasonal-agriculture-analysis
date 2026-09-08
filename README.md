# Seasonal Agriculture Performance Analysis

**VOIS AICTE Major Project - Batch 1 (2026-2027)**

A comprehensive data analytics project investigating seasonal variations in agricultural performance using Python, statistical analysis, and data visualization.

---

## 📋 Project Overview

This project analyzes 4,000 agricultural records across three Indian seasons to identify meaningful patterns, trends, and relationships in agricultural performance.

### Key Metrics
- **Dataset Size:** 4,000 farm records
- **Geographic Coverage:** Multiple states across India  
- **Crop Variety:** 8 different crops
- **Seasonal Coverage:** Kharif, Rabi, Zaid
- **Features Analyzed:** 28 environmental, resource, and economic metrics

---

## 🎯 Objectives

✓ Analyze how agricultural performance varies across seasons  
✓ Identify important seasonal patterns and trends  
✓ Investigate relationships between seasonal conditions and agricultural outcomes  
✓ Compare relevant groups within different seasons  
✓ Discover significant differences and unusual patterns  
✓ Apply appropriate statistical and visualization techniques  
✓ Interpret findings and develop evidence-based recommendations  

---

## 📊 Key Findings

### Finding 1: Seasonal Performance Variation
| Metric | Kharif | Rabi | Zaid |
|--------|--------|------|------|
| **Yield** | 5.67 T/Ha ⭐ | 4.98 T/Ha | 4.64 T/Ha |
| **Profit** | ₹181,539 ✓ | ₹86,222 | -₹26,636 ✗ |
| **Performance** | Excellent | Good | Poor |

**Key Insight:** Kharif season demonstrates superior agricultural performance with 210% higher profitability than Zaid. Clear seasonal hierarchy exists.

### Finding 2: Environmental Characteristics
| Factor | Kharif | Rabi | Zaid |
|--------|--------|------|------|
| **Rainfall** | 850.66 mm | 436.83 mm | 299.07 mm |
| **Temperature** | 28.44°C | 23.49°C | 31.04°C |
| **Soil Moisture** | 31.20% | 24.07% | 19.18% |

**Key Insight:** Environmental stress increases from Kharif to Zaid, with Zaid facing combined challenges of low rainfall, high temperature, and low moisture.

### Finding 3: Resource Usage & Disease
- **Disease Risk:** Kharif (54.45%) > Rabi (40.52%) > Zaid (38.11%)
- **Water Efficiency:** Zaid requires highest water despite lowest rainfall
- **Irrigation:** Drip irrigation consistently outperforms (5-7 T/Ha vs 3-5 T/Ha for others)

**Key Insight:** Drip irrigation crucial for Zaid; disease management essential for monsoon season.

### Finding 4: Crop Performance
- **Best Performer:** Sugarcane dominates all seasons (38-54 T/Ha)
- **Consistent Pattern:** 14-18% yield decline from Kharif to Zaid across all crops
- **Lowest Performer:** Pulses (0.66-1.04 T/Ha)

**Key Insight:** Crop selection must align with seasonal environmental conditions.

---

## 🛠️ Technology Stack

**Language & Environment:**
- Python 3.x
- Jupyter Notebook

**Data Processing:**
- Pandas (data manipulation)
- NumPy (numerical computations)

**Visualization:**
- Matplotlib (charts and plots)
- Seaborn (statistical visualizations)

**Analysis:**
- Descriptive Statistics
- Correlation Analysis
- Comparative Analysis
- Distribution Analysis

---

## 📁 Project Structure

```
seasonal-agriculture-analysis/
├── Seasonal_Agriculture_Analysis.ipynb          # Main Jupyter Notebook (code, charts, analysis)
├── Seasonal_Agriculture_Analysis_Presentation.pptx # Final project presentation (14 slides)
├── seasonal_agriculture_performance_dataset.csv   # Cleaned 4,000-record dataset
├── visualizations/                               # Generated high-resolution charts
├── README.md                                     # Project overview and documentation
└── requirements.txt                              # Python dependencies
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- pip (Python package manager)
- Jupyter Notebook

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Siddhi-m-20/seasonal-agriculture-analysis.git
   cd seasonal-agriculture-analysis
   ```

2. **Create virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open and run the analysis**
   - Click on `Seasonal_Agriculture_Analysis.ipynb`
   - Run all cells (Kernel → Restart & Run All) or run cells sequentially

---

## 📈 Analysis Workflow

The notebook is structured in logical sections:

1. **Data Import & Exploration** - Load and inspect dataset
2. **Data Cleaning** - Handle missing values and prepare data
3. **Finding 1** - Seasonal performance variation analysis
4. **Finding 2** - Environmental characteristics by season
5. **Finding 3** - Resource usage and disease patterns
6. **Finding 4** - Crop performance across seasons
7. **Statistical Analysis** - Correlation matrix and insights
8. **Profitability Analysis** - Economic performance metrics
9. **Summary** - Key findings and recommendations
10. **Conclusion** - Project outcomes and impact

---

## 📊 Key Visualizations

The analysis generates 9+ professional charts:

1. Average Yield by Season
2. Profitability Comparison
3. Rainfall Patterns
4. Temperature Variations
5. Water Efficiency Analysis
6. Disease/Pest Risk Distribution
7. Yield Variability Distribution
8. Irrigation Method Performance
9. Revenue vs Cost Analysis
10. Correlation Heatmaps
11. Crop Performance Heatmaps

---

## 💡 Evidence-Based Recommendations

### For Farmers & Farm Managers
✓ Prioritize Kharif season for maximum yield and profit  
✓ Adopt drip irrigation for Zaid profitability improvement  
✓ Select crops based on seasonal suitability matrix  
✓ Implement preventive pest management during Kharif  

### For Agricultural Planners
✓ Allocate resources proportionally to seasonal opportunity  
✓ Develop region-specific seasonal strategies  
✓ Invest in irrigation infrastructure for Zaid support  
✓ Create evidence-based crop-season suitability guidelines  

### For Policy Makers
✓ Subsidize drip irrigation adoption  
✓ Create seasonal crop insurance schemes  
✓ Promote climate-resilient farming practices  
✓ Fund disease management research for monsoon season  

---

## 📚 Dataset Information

### Dataset Features (28 total)

**Identifiers:**
- Farm_ID, State, District, Crop, Season

**Environmental Factors:**
- Rainfall_mm, Avg_Temperature_C, Humidity_pct, Sunlight_Hours_Day
- Soil_pH, Soil_Moisture_pct

**Resource Usage:**
- Nitrogen_kg_ha, Phosphorus_kg_ha, Potassium_kg_ha
- Irrigation_Method, Fertilizer_kg_ha, Pesticide_Litre_ha
- Seed_Quality_Score, Water_Used_m3, Water_Efficiency_t_per_1000m3

**Production Metrics:**
- Farm_Area_Hectares, Yield_Tonnes_Ha, Production_Tonnes

**Economic Metrics:**
- Market_Price_INR_Tonne, Total_Cost_INR, Revenue_INR, Profit_INR

**Risk Factors:**
- Disease_Pest_Risk_pct

---

## 🔍 Statistical Summary

### Data Quality
- **Records:** 4,000 farms
- **Missing Values:** < 2% across features
- **Data Completeness:** 98%+ retained after cleaning

### Seasonal Distribution
- **Kharif:** ~1,300 records
- **Rabi:** ~1,300 records
- **Zaid:** ~1,400 records

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

✓ **Data Analysis** - Exploratory data analysis and pattern discovery  
✓ **Python Programming** - Data manipulation with Pandas, NumPy  
✓ **Statistical Analysis** - Descriptive statistics, correlation analysis  
✓ **Data Visualization** - Creating professional charts with Matplotlib & Seaborn  
✓ **Business Intelligence** - Deriving actionable insights from data  
✓ **Report Writing** - Documenting findings and recommendations  

---

## 🤝 Contributing

This is an academic project. For questions or discussions:
- Open an issue on GitHub
- Contact the project author

---

## 📞 Author & Contact

**Author:** Siddhi Ramkrishna Manjarekar  
**College:** Savitribai Phule Pune University  
**AICTE STU ID:** STU654e5442c94401699632194  
**Internship ID:** INTERNSHIP_17830691666a4779eecfe8a  
**Batch:** VOIS AICTE Batch 1 (August Batch 2026)  
**Track:** Data Analytics (VOIS for Tech Program)  
**GitHub:** [Siddhi-m-20](https://github.com/Siddhi-m-20)

---

## 📜 License

Academic project developed for the VOIS AICTE Data Analytics Internship Program. For educational and research purposes.

---

## 🎉 Acknowledgments

- VOIS & Vodafone Idea Foundation for the VOIS for Tech learning track
- Edunet Foundation & AICTE for mentorship and program guidance
- Python open-source data analytics and scientific computing community
