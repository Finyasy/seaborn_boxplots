## 📊 Synthetic Titanic Data Simulation & EDA

### Overview
Generation of **synthetic passenger data (100 rows)** with realistic relationships between features.

### Features
- **class**: First / Second / Third  
- **deck**: A–G (correlated with passenger class)  
- **age**: Bounded, normally distributed  
- **fare**: Right-skewed, dependent on class and deck  
- **alive**: Survival indicator  

### Visual Analysis
Boxplots are used to compare **age** and **fare** distributions across:
- Passenger class
- Deck
- Survival status  

### Key Concepts Illustrated
- How boxplots summarize distributions (median, IQR, outliers)
- Encoding realistic feature dependencies in synthetic data
- Multi-dimensional EDA using `hue` and categorical variables

### Purpose
This notebook is useful for **learning data visualization**, **exploratory data analysis (EDA)** techniques, and **building intuition before modeling**, without relying on the original Titanic dataset.
