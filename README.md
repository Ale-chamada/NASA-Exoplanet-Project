# 🌌 Exoplanet Data Analysis: Observational Constraints & Detection Patterns

## 📌 Overview
This project analyzes exoplanet data to explore relationships between planetary characteristics, stellar properties, and detection methods.  

Rather than treating the dataset as a direct representation of reality, the analysis focuses on how **observational limitations and detection techniques influence what we observe**.

---

## 🎯 Objectives
- Analyze relationships between stellar and planetary variables  
- Investigate how detection methods vary across conditions  
- Examine how distance and orbital properties affect observations  
- Identify patterns across different planet types  
- Apply structured data analysis techniques to a real-world scientific dataset  

---

## 📊 Dataset
The dataset includes confirmed exoplanets with features such as:

- **Planetary properties**
  - Orbital period (`pl_orbper`)
  - Radius (`pl_radj`)
  - Mass (`pl_bmassj`)

- **Stellar properties**
  - Mass (`st_mass`)
  - Radius (`st_rad`)
  - Temperature (`st_teff`)
  - Distance (`st_dist`)

- **Detection metadata**
  - Discovery method (`pl_discmethod`)

---

## 🛠️ Data Preparation
- Filtered columns based on missing data thresholds  
- Retained critical variables for analysis  
- Removed rows with missing key features  
- Applied basic assumptions where required for completeness  

---

## ⚙️ Feature Engineering
- **Relative Size Metric**
  - `size_comparison_ratio` = planet radius / star radius  

- **Planet Classification**
  - Earth-like → Gas Giant (based on radius bins)

- **Distance Cohorts**
  - Near, Moderate, Far, Very Far (percentile-based grouping)

- **Extreme Systems**
  - Top 5% in distance or orbital period  

---

## 📈 Analysis Approach

### Correlation Analysis
Examined relationships between stellar and planetary variables to identify structural patterns.

### Cross-Tabulation
Compared:
- Detection method vs planet type  
- Detection method vs distance groups  

### Cohort Analysis
Grouped planets by distance to evaluate how detection methods vary across observational ranges.

### Percentile Analysis
Identified extreme systems to study edge cases and observational limits.

### Multi-Dimensional Analysis
Combined multiple variables (method, distance, planet type) to uncover interaction effects.

---

## 📊 Visualizations
- Correlation heatmaps  
- Stacked bar charts (distribution comparisons)  
- Distance-based cohort plots  
- Detection method distributions  

---

## ⚠️ Limitations
- Missing values across several variables  
- Uneven representation of planet types  
- Detection methods have different sensitivities  
- Dataset reflects observational constraints, not a complete population  

---

## 🧠 Conclusion
This analysis demonstrates that observed exoplanet data is shaped by both **underlying physical properties and the limitations of detection methods**.  

Understanding these constraints is essential for correctly interpreting patterns in the dataset.

---

## 🚀 Future Work
- Improve handling of missing data  
- Model detection likelihood across conditions  
- Apply clustering to identify planetary regimes  
- Extend analysis with additional astrophysical features  

---

## 🗂️ Project Structure
