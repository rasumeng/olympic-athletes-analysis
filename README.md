# Olympic Athletes Analysis: Exploratory Data Analysis

[![Kaggle](https://img.shields.io/badge/Kaggle-View%20Notebook-20BEFF?logo=kaggle)](https://www.kaggle.com/code/robertasumeng/olympic-athletes-analysis)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/rasumeng/olympic-athletes-analysis)

## 📊 Project Overview

This project presents a comprehensive exploratory data analysis (EDA) of Olympic medalists spanning **120 years** (1896-2016). The analysis uncovers demographic patterns, performance trends, and fascinating insights into what distinguishes Olympic champions across different sports, countries, and time periods.

**Dataset:** 271,116 Olympic medal records across Summer and Winter Olympics

---

## 🔍 Key Findings

### Demographic Insights

- **Age Range:** Olympic medalists range from **single-digit prodigies** to competitors in their **70s**
- **Average Medalist Age:** ~26 years
- **Extreme Athletes:** The dataset reveals remarkable outliers—young gymnasts and divers competing alongside experienced shooters and equestrian athletes
- **Sport-Specific Patterns:** 
  - Youth-dominant sports: Gymnastics, Diving, Swimming
  - Experience-favored sports: Shooting, Equestrian, Sailing

### Medal Distribution

- **Total Medals Awarded:** 271,116 across three medal types
- **Gold Medals:** Largest category
- **Events Analyzed:** Hundreds of unique Olympic events across 40+ sports

### Country Performance

**Top 10 Medalist Countries (All-Time):**
1. United States - Dominant across multiple Olympic cycles
2. Soviet Union (historical records)
3. Germany (combined)
4. France
5. Italy
6. Sweden
7. Japan
8. Great Britain
9. Romania
10. China

**Notable Achievement:** The United States has earned **thousands of gold medals** throughout Olympic history.

### Physical Characteristics

**Recent Olympics (2016):**
- **Summer Olympic Medalists:** Average height ~5'8", average weight ~70 kg
- **Winter Olympic Medalists:** Distinct physical profiles tailored to winter sports demands

---

## 📈 Analysis Highlights

### Gender & Event Evolution
- Comprehensive tracking of male and female medalists across all Olympic disciplines
- Documentation of sport-specific trends and athlete specialization

### Geographic Dominance
- Clear patterns of medal distribution by nation and NOC (National Olympic Committee)
- Historical tracking from 1896 through 2016, capturing major geopolitical changes

### Longevity in Olympic Sport
- **Story Angle:** Several athletes achieved medals well beyond typical athletic peak years, highlighting resilience and the role of sport type in career longevity
- Supporting evidence: Concentration of older medalists in technical sports like shooting and equestrian disciplines

---

## 🛠️ Technologies & Methods

- **Python 3.x**
- **Pandas:** Data manipulation and analysis
- **Plotly Express:** Interactive visualizations (bar charts, trend analysis)
- **Jupyter Notebook:** Interactive analysis and documentation

---

## 📂 Project Structure

```
olympic-athletes-analysis/
├── olympic-athletes-analysis.ipynb    # Main EDA notebook with complete analysis
├── datasets/
│   └── olympics.csv                   # Olympic medalists dataset (1896-2016)
└── README.md                          # This file
```

---

## 🚀 How to Use

### Prerequisites
```bash
pip install pandas plotly
```

### Run the Analysis
1. Open the Jupyter notebook: `olympic-athletes-analysis.ipynb`
2. Execute cells sequentially to:
   - Load and explore the dataset
   - Perform demographic analysis
   - Generate visualizations
   - Discover trends and patterns

### Key Questions Answered
- Who are the youngest and oldest Olympic medalists?
- Which countries have won the most medals?
- How do athlete characteristics vary by sport?
- What physical characteristics define Olympic success?
- How has Olympic competition evolved over 120 years?

---

## 💡 Data Quality Notes

- **Missing Values:** Age, Height, Weight, and Country fields contain NaN values representing data unavailability (not zero values)
- **Data Scope:** Only includes medalists—non-medaling athletes are not represented
- **Historical Limitations:** Earlier Olympic records (pre-1920s) have more limited demographic data

---

## 🎯 Story Angles & Insights

### Primary Finding: Age & Longevity in Olympic Sport
The analysis reveals a compelling narrative about athletic longevity. While most medalists cluster around age 26, the presence of athletes competing into their 70s challenges conventional wisdom about athletic "prime years." 

**Why It Matters:**
- Different sports reward different life stages
- Technical sports (shooting, equestrian) enable extended careers
- Physical development sports (gymnastics, diving) concentrate talent in youth
- This variation reflects fundamental differences in athletic training pathways

**Supporting Data Points:**
- 10 oldest medalists concentrated in specific sports
- Age distribution shows distinct bimodal patterns by sport type
- Historical continuity of certain athletes across multiple Olympic cycles

---

## 🏆 About the Dataset

The Olympic medalists dataset comes from a comprehensive compilation of historical Olympic records. Each record represents:
- **One athlete's participation in one event where they won a medal**
- Athletes with multiple medals appear multiple times
- Includes both Summer and Winter Olympic Games
- Covers 120 years of international Olympic competition
- Documents 40+ different sports across hundreds of unique events

---

## 📚 Potential Extensions

- Predictive modeling for medal performance based on demographics
- Time-series analysis of country dominance over Olympic cycles
- Network analysis of host cities and performance trends
- Machine learning classification of athlete profiles by sport
- Interactive dashboard for exploring medal distributions

---

## ✅ Analysis Completeness

This EDA provides:
- ✓ Data quality assessment and cleaning
- ✓ Comprehensive demographic profiling
- ✓ Geographic and competitive trend analysis
- ✓ Visual representations of key findings
- ✓ Actionable insights for sports journalism and research

---

## 📝 Author

Created as part of rigorous exploratory data analysis training, demonstrating proficiency in:
- Data cleaning and preparation
- Statistical analysis and interpretation
- Pattern recognition and storytelling with data
- Professional data visualization
- Insight extraction from large datasets

---

## 📄 License

This project uses publicly available Olympic data for educational and analytical purposes.

---

**Last Updated:** January 2026  
**Dataset Period:** 1896-2016
