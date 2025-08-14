# Car Color Trends Analysis
Analysis of automotive auction data to identify color trends and market opportunities across 1982-2015.

## Dataset
- **Source**: US automotive auction records  
- **Original Records**: 558,811
- **Clean Records**: 537,062 (96.1% retention)
- **Time Period**: 2014-2015 sales data
- **Vehicle Years**: 1982-2015 model years
- **Geographic Coverage**: All 50 US states

## Project Status
**Phase 3: EDA** - 50% Complete

### Research Questions Progress

**Question 1 - Monochrome Evolution** ✅ **COMPLETED**
- Identified industry-wide shift from colorful to monochrome vehicles

**Question 2 - Manufacturer Leadership** ✅ **COMPLETED**
- **2A**: Color diversity analysis via Shannon diversity index and heatmap visualization
- **2B**: Early adopter identification - Japanese brands (Nissan 1997, Honda 1998, Toyota 1999) led trend
- **2C**: Brand tier analysis - no significant timing difference by price segment

**Question 3 - Vehicle Type Patterns** 🔄 **IN PROGRESS**
- Compare color evolution across body types (sedan, SUV, pickup, etc.)

**Question 4 - Regional Variations** ⏳ **PENDING**
- Analyze geographic color preference patterns

## Key Findings
- **Universal trend**: All major brands shifted to monochrome, timing varied by individual strategy
- **Japanese leadership**: Nissan, Honda, Toyota pioneered monochrome adoption 1997-1999
- **No tier effect**: Luxury vs mainstream brands showed similar adoption patterns (1.3-year spread)
- **American lag**: Ford, Chrysler adopted trend 3-7 years after Japanese brands

## Files
- `03 Scripts/01 Data Exploration and Cleaning.ipynb` - Data cleaning and exploration ✅
- `03 Scripts/02 EDA.ipynb` - Manufacturer leadership analysis ✅
- `03 Scripts/03 EDA.ipynb` - Vehicle type and regional analysis 🔄

## Technical Highlights
- **Shannon Diversity Index** for quantitative color variety measurement
- **Statistical rigor**: 100+ vehicle minimum for brand-year analysis
- **Data quality**: Ram/Dodge brand consolidation for consistency
- **35 major brands** analyzed (1000+ vehicles each)

---
*Last updated: Research Question 2 completed - December 2024*