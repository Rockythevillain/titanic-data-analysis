# Titanic Data Analysis 🚢

## Project Overview
Complete exploratory data analysis of the Titanic passenger dataset 
to identify key factors that affected survival rates.

## Business Questions Answered
1. How many passengers survived vs died?
2. Did gender affect survival rate?
3. Did passenger class affect survival rate?
4. Did age group affect survival rate?
5. What factors correlate most strongly with survival?
6. What was the fare distribution across classes?

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Skills Demonstrated
- Data loading and exploration
- Data cleaning — missing values, duplicates, type conversion
- Feature engineering — age group creation using pd.cut()
- Exploratory data analysis
- Data visualisation — bar charts, heatmaps, boxplots
- Correlation analysis
- Insight storytelling

## Key Findings
- Only 38% of passengers survived the disaster
- Women had 74% survival rate vs only 19% for men
- 1st class passengers had 63% survival vs 24% for 3rd class
- Children had highest survival rate at 50%
- Seniors had lowest survival rate at only 22%
- Sex and Pclass were the strongest predictors of survival
- Higher fare paying passengers had better survival chances

## Data Cleaning Steps
- Filled 177 missing Age values with mean age
- Dropped Cabin column (77% missing)
- Filled 2 missing Embarked values with mode
- Converted Sex column from text to numeric (male=0, female=1)
- Removed duplicate rows

## Conclusion
Survival on the Titanic was strongly influenced by gender and 
passenger class. Being female was the single biggest factor in 
survival. Class based discrimination in safety provision cost 
hundreds of lives. Children were prioritised but Seniors had 
the worst survival outcomes.

## Files
- titanic-analysis.ipynb — complete Python analysis notebook
