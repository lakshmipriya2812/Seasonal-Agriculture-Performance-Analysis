Seasonal Agriculture Performance Analysis
1. Project Overview
Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability and market conditions. This project analyzes agricultural data across different seasons to identify meaningful patterns, trends, relationships and variations in agricultural performance.
The analysis focuses on yield, production, profitability, revenue, resource usage, water efficiency, irrigation methods, environmental conditions, crop-season differences and disease/pest risk.
2. Problem Statement
Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability and market conditions. As a result, agricultural performance may differ from one season to another. However, raw agricultural data does not clearly explain how agricultural performance changes across seasons or what patterns can be observed in different seasonal conditions.
The problem is to analyze the given agricultural dataset and investigate seasonal differences in agricultural performance by identifying meaningful patterns, trends, relationships and variations within the available data.
3. Importance of the Problem
Understanding seasonal patterns through data analytics can help stakeholders:
Understand variations in agricultural performance
Identify important seasonal trends
Compare performance across different periods
Understand changing environmental conditions
Examine differences in resource usage
Identify areas requiring further investigation
Support evidence-based agricultural planning
4. Objectives
Explore and understand the dataset.
Clean and prepare the data for analysis.
Examine how agricultural performance varies across seasons.
Identify important seasonal patterns and trends.
Investigate relationships between seasonal conditions and agricultural outcomes.
Compare relevant groups within different seasons.
Identify significant differences or unusual patterns.
Apply appropriate statistical and visualization techniques.
Interpret findings based on evidence.
Develop meaningful conclusions and data-driven recommendations.
5. Dataset
The dataset represents agricultural activities across different seasons, geographical areas and farming conditions. It contains information related to farming practices, environmental conditions, crop production, resource usage and economic performance.
The dataset contains 4,000 farm records across Kharif, Rabi and Zaid seasons.
Main variable categories include farm information, crop and season, environmental conditions, soil conditions, farming practices, agricultural performance, economic variables, water usage and disease/pest risk.
6. Analytical Questions
How does agricultural performance vary across seasons?
What major seasonal patterns can be observed?
Which characteristics change between seasons?
What differences exist between agricultural activities in different seasons?
Are there noticeable variations in resource usage across seasons?
Are there relationships between seasonal environmental conditions and agricultural performance?
How do economic outcomes vary across seasons?
Are some seasonal patterns consistent across different regions or categories?
Are there unusual or unexpected seasonal patterns?
What insights can be derived from observed seasonal differences?
What conclusions can reasonably be drawn from the available data?
How could findings support better seasonal agricultural planning?
7. Technology Used
Technology	Purpose
Python	Data analysis and processing
Jupyter Notebook	Analysis environment
Pandas	Data loading, cleaning and aggregation
NumPy	Numerical operations
Matplotlib	Data visualization
SciPy	Kruskal-Wallis statistical testing
Git	Version control
GitHub	Repository and documentation
PowerPoint	Project presentation
8. Data Cleaning and Preparation
The workflow includes loading the dataset, inspecting its structure, checking data types and missing values, preparing numerical variables, creating grouped datasets, preparing visualizations and statistical tests, and exporting the cleaned dataset.
The cleaned analytical dataset contains 4,000 rows and 28 columns.
Missing observations were identified in selected variables including Rainfall, Soil Moisture and Yield. Median imputation was used for affected numerical variables.
9. Exploratory Data Analysis
The project performs seasonal, crop, production, yield, profit, revenue, irrigation, water-efficiency, environmental, disease/pest-risk and correlation analysis.
10. Seasonal Performance
Average Yield by Season
Season	Average Yield
Kharif	5.63 tonnes/ha
Rabi	5.04 tonnes/ha
Zaid	4.64 tonnes/ha
Kharif has the highest observed average yield and Zaid the lowest.
11. Economic Performance
Aggregate Profit by Season
Season	Aggregate Profit
Kharif	Approximately ₹318.3M
Rabi	Approximately ₹142.7M
Zaid	Approximately -₹14.7M
Kharif has the strongest aggregate economic outcome. Zaid is the only season with negative aggregate profit.
12. Crop Analysis
Sugarcane has a much higher average yield than the other crops.
Sugarcane strongly influences overall averages.
Chilli is another relatively strong profitability performer.
Crop mix should be considered before making broad seasonal conclusions.
13. Irrigation Analysis
Drip irrigation has the highest average yield.
Drip irrigation also has the highest average profit.
Rainfed farming has the highest average water-efficiency value.
These are associations observed in the dataset and do not establish causation.
14. Environmental and Resource Analysis
The project examines rainfall, temperature, humidity, sunlight, soil pH, soil moisture, nitrogen, phosphorus, potassium, fertilizer usage, pesticide usage, water usage and water efficiency.
15. Correlation Analysis
A correlation matrix was generated for numerical variables. Correlation helps identify the strength and direction of associations between numerical variables.
Correlation does not establish causation. Some variables may also have mathematical relationships with one another.
16. Statistical Testing
The Kruskal-Wallis test was used to examine seasonal differences in:
Yield
Profit
Revenue
Water efficiency
Disease/Pest Risk
For the supplied dataset, the tests indicate statistically detectable seasonal differences at the 0.05 significance level. Disease/Pest Risk has especially strong effect size, while the effect sizes for yield, profit, revenue and water efficiency are much smaller.
Statistical significance should not automatically be interpreted as a large practical effect.
17. Key Findings
The dataset contains 4,000 farm records across 3 seasons.
Kharif is the strongest overall season in this dataset for average yield, production, water efficiency and aggregate profitability.
Kharif has the highest average yield at 5.63 tonnes/ha.
Rabi has an average yield of 5.04 tonnes/ha.
Zaid has the lowest average yield at 4.64 tonnes/ha.
Zaid has the weakest economic outcome, with negative aggregate profit.
Kharif has approximately ₹318.3M aggregate profit.
Rabi has approximately ₹142.7M aggregate profit.
Zaid has approximately -₹14.7M aggregate profit.
Environmental conditions vary substantially across seasons.
Sugarcane strongly influences overall averages because its yield and profit are much higher than those of most other crops.
Drip irrigation has the highest average yield and average profit.
Rainfed farming has the highest average water-efficiency measure, but not the highest profit.
Seasonal differences are statistically detectable for yield, profit, revenue, water efficiency and disease/pest risk.
Relationships between variables should be interpreted as associations, not causal proof.
18. Evidence-Based Recommendations
Prioritize season-specific planning.
Use Kharif as a benchmark for identifying practices associated with stronger performance.
Investigate why Zaid has negative aggregate profitability.
Examine Zaid's cost, crop-selection and resource-use patterns.
Evaluate drip irrigation where the objective is higher yield and profit, considering water availability and crop type.
Examine crop-level performance before making broad seasonal decisions.
Monitor disease/pest risk separately because it shows substantial seasonal variation.
Combine multi-year, location-specific and market data in future analysis.
19. Limitations
The dataset contains only the supplied observations and does not provide a multi-year time series.
Some records contain missing values, which were median-imputed for analysis.
Several variables are mathematically related, so correlation can be influenced by formula relationships.
The analysis is observational and should not be interpreted as proving causation.
Seasonal averages can be influenced by differences in crop composition.
The project focuses on descriptive and diagnostic analytics rather than deploying a predictive model.
Findings should be interpreted within the scope of the supplied dataset.
20. Conclusion
This project provides an end-to-end analysis of seasonal agricultural performance using data cleaning, exploratory analysis, visualization, correlation analysis and statistical testing.
The analysis identified differences in observed yield, profitability, water efficiency and disease/pest risk across Kharif, Rabi and Zaid. Kharif showed the strongest overall performance in the supplied dataset, while Zaid showed comparatively weaker economic performance and negative aggregate profitability.
Crop-level analysis showed that Sugarcane strongly influences overall averages. Irrigation analysis showed that Drip irrigation had the highest average yield and average profit, while Rainfed farming had the highest average water-efficiency measure.
The Kruskal-Wallis analysis indicated statistically detectable seasonal differences for yield, profit, revenue, water efficiency and disease/pest risk.
Overall, agricultural performance should be evaluated using multiple dimensions rather than a single metric. Season, crop type, irrigation, environmental conditions, resource utilization and economic factors should be considered together.
21. Future Scope
Add multi-year and location-specific agricultural data.
Build an interactive dashboard for season, crop and region filtering.
Evaluate predictive models for yield, profitability or disease/pest risk.
Use controlled statistical models to separate crop, season, irrigation and environmental effects.
Add market-price and weather forecasts for decision support.
Validate findings with field-level agricultural expertise.
22. Repository Structure
```text
Seasonal-Agriculture-Performance-Analysis/
├── Seasonal\_Agriculture\_Performance\_Analysis.ipynb
├── seasonal\_agriculture\_performance\_dataset.csv
├── cleaned\_agriculture\_dataset.csv
├── outputs/
│   └── charts/
│       ├── average\_profit\_by\_crop.png
│       ├── average\_profit\_by\_season.png
│       ├── average\_yield\_by\_crop.png
│       ├── average\_yield\_by\_season.png
│       ├── correlation\_matrix.png
│       ├── irrigation\_yield.png
│       ├── irrigation\_yield\_by\_season.png
│       ├── production\_by\_crop\_and\_season.png
│       └── profit\_by\_crop\_and\_season.png
└── README.md
```
23. Analysis Outputs
Generated charts are stored in `outputs/charts/`:
average_profit_by_crop.png
average_profit_by_season.png
average_yield_by_crop.png
average_yield_by_season.png
correlation_matrix.png
irrigation_yield.png
irrigation_yield_by_season.png
production_by_crop_and_season.png
profit_by_crop_and_season.png
24. End Users
Farmers and Agricultural Planners: Understand seasonal performance and compare crop and irrigation outcomes.
Agricultural Analysts: Compare crops, seasons, resources and economic outcomes.
Resource Managers: Evaluate water usage, irrigation methods and water-efficiency patterns.
Policy and Program Stakeholders: Identify areas requiring further investigation and support evidence-based planning.
Students and Educators: Demonstrate an end-to-end real-world Data Analytics workflow.
25. Project Files
Jupyter Notebook: `Seasonal\_Agriculture\_Performance\_Analysis.ipynb` — complete analysis workflow.
Original Dataset: `seasonal\_agriculture\_performance\_dataset.csv` — original agricultural dataset.
Cleaned Dataset: `cleaned\_agriculture\_dataset.csv` — processed dataset used for analysis.
Charts: `outputs/charts/` — generated analysis visualizations.
26. GitHub Repository
https://github.com/lakshmipriya2812/Seasonal-Agriculture-Performance-Analysis
27. Project Context
VOIS AICTE Batch 1 (2026–2027)
Major Project: Seasonal Agriculture Performance Analysis
This project demonstrates the application of Data Analytics techniques to a real-world agricultural dataset, with emphasis on seasonal performance, agricultural resources, economic outcomes, visualization and evidence-based interpretation.
28. Author
Lakshmi Priya Bodla
B.E. – Artificial Intelligence and Data Science
Stanley College of Engineering and Technology for Women, Hyderabad
AICTE STU ID: STU66157b3e0e9a91712683838
29. Acknowledgement
This project was completed as part of the VOIS AICTE Batch 1 (2026–2027) Major Project and applies Data Analytics concepts and tools to seasonal agricultural performance analysis.
