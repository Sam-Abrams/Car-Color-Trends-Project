# Automotive Color Trends Analysis

## Overview
Comprehensive analysis of automotive color diversity trends using 537,062 vehicle auction records spanning 1982-2015, examining the industry-wide shift from colorful to monochromatic vehicle offerings.

## Dataset
- **Source**: US automotive auction records
- **Original Records**: 558,811
- **Clean Records**: 537,062 (96.1% retention)
- **Time Period**: 2014-2015 sales data
- **Vehicle Years**: 1982-2015 model years
- **Geographic Coverage**: All 50 US states

## Key Findings

### 🏆 Manufacturer Strategy Drives Color Trends
- **Japanese brands led adoption** by 3-7 years (Nissan 1997, Honda 1998, Toyota 1999)
- **American brands lagged** significantly (Ford 2002, Chrysler 2004)
- Individual brand decisions mattered more than market positioning

### 📊 What Doesn't Influence Color Strategy
- **Vehicle Type**: No significant differences across sedan, SUV, pickup segments
- **Price Tier**: Luxury vs mainstream brands showed similar timing (1.3-year spread)
- **Geography**: No statistically significant regional differences (ANOVA p = 0.219)

### 🔍 Methodological Rigor
- Shannon diversity index for quantitative color measurement
- Statistical significance testing (ANOVA)
- Minimum sample thresholds (100+ vehicles for brand-year analysis)
- Data consolidation (Ram merged with Dodge for consistency)

## Project Structure
```
├── 01 Data Exploration and Cleaning.ipynb    # Initial data assessment
├── 02 Merging Data.ipynb                     # Data consolidation  
├── 03 EDA - Color Trends and Brand Adoption.ipynb  # Research Questions 1 & 2
├── 04 EDA - Vehicle Type and Regional Analysis.ipynb  # Research Questions 3 & 4
├── README.md                                 # Project documentation
└── requirements.txt                          # Python dependencies
```

## Research Questions Answered

### 1. Monochrome Evolution ✅
Tracked the industry-wide shift from colorful to monochromatic vehicles, identifying timing and patterns.

### 2. Manufacturer Leadership ✅
- **2A**: Color diversity analysis via Shannon diversity index
- **2B**: Early adopter identification - Japanese brands pioneered the trend
- **2C**: Brand tier analysis - no significant timing difference by price segment

### 3. Vehicle Type Patterns ✅
Found minimal variation across consumer vehicle segments (0.2-point diversity range).

### 4. Regional Variations ✅
Confirmed no statistically significant regional differences in color preferences.

## Technical Implementation

### Tools & Libraries
- **Python 3.8+**
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **scipy**: Statistical analysis (ANOVA testing)
- **matplotlib & seaborn**: Data visualization
- **jupyter**: Interactive development environment

### Key Methods
- **Shannon Diversity Index**: Quantified color variety accounting for richness and evenness
- **ANOVA Testing**: Statistical significance testing for regional differences
- **Data-driven Classification**: Price-based brand tiers using actual auction values

## Running the Analysis

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Launch Jupyter**:
   ```bash
   jupyter notebook
   ```

3. **Run notebooks in sequence**:
   - Start with `01 Data Exploration and Cleaning.ipynb`
   - Follow numerical order through `04 EDA - Vehicle Type and Regional Analysis.ipynb`

## Key Insights for Business

### Strategic Recommendations
- **Monitor Japanese brand strategies** as early indicators of industry trends
- **Implement color strategies nationally** without regional variation
- **Focus on brand-level differentiation** rather than segment-specific approaches

### Market Implications
- Color strategy decisions transcend traditional market segmentation
- Geographic location has minimal impact on color preferences
- Individual manufacturer decisions drive industry patterns more than demographic factors

## Data Quality & Limitations

### Strengths
- Large sample size (537K+ records)
- Comprehensive geographic coverage (all 50 US states)
- 34-year temporal span for trend analysis
- Statistical rigor with significance testing

### Limitations
- Auction data may not fully represent retail market
- Limited to US market only
- 2014-2015 sales period for vehicles spanning 1982-2015
- Missing condition data for some economic analyses

## Contact & Portfolio
- [Portfolio](www.sam-abrams.com)
- [LinkedIn](https://www.linkedin.com/in/samabrams15/)
---

**Analysis demonstrates rigorous methodology in testing industry assumptions about automotive color preferences, providing data-driven insights for strategic decision-making.**
