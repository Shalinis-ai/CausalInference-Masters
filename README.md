# CausalInference-Masters
# Optimizing Targeted Pricing in E-commerce through Causal Analysis of Pricing Strategies
### Overview
This repository contains the code and data related to my final thesis project titled "Optimizing Targeted Pricing in E-commerce through Causal Analysis of Pricing Strategies". The primary objective of this project is to analyze the causal effects of pricing strategies on consumer purchasing behavior using advanced causal inference models.
### Project Summary
The project addresses a significant challenge faced by e-commerce businesses: how pricing changes influence consumer behavior and sales performance. Traditional pricing strategies often fail to capture the complex dynamics of online shopping environments. To overcome these limitations, this study applies rigorous causal analysis techniques, such as Propensity Score Matching (PSM), Difference-in-Differences (DiD), and DoWhy Framework.
### Key Components:
### Causal Inference Models:
#### Propensity Score Matching (PSM) with balance checks using Standardized Mean Difference (SMD) and Standard Error Difference (SED).
#### Difference-in-Differences (DiD) for assessing the impact of pricing changes over time.
#### DoWhy framework for validating causal assumptions.
#### Quadrant Analysis: Segmentation of consumers into Lost Causes, Sleeping Dogs, Persuadables, and Sure Things based on their responsiveness to price changes.
Dynamic and Personalized Pricing Models: Integration of user segmentation techniques to target specific customer groups with pricing strategies, thereby optimizing conversion rates.
### Data
The dataset consists of event-level interactions from a large multi-category e-commerce store, capturing key attributes such as:
event_time
event_type (view, cart, purchase)
product_id, category_id, category_code, brand
price, user_id, user_session
Preprocessing steps include handling missing values, categorical encoding, feature engineering, and creation of the treatment and control groups for causal analysis.
### Methodology
The core of this project revolves around using causal inference methods to identify the impact of pricing adjustments:
##### PSM: Matches users based on their propensity scores to create equivalent treatment and control groups.
##### DiD: Compares before-and-after outcomes between treated and untreated groups to isolate the effect of price changes.
##### Quadrant Analysis: Classifies consumers into segments, enabling targeted interventions.
##### DoWhy: Ensures robustness by validating the causal assumptions made in the analysis.
### Steps Included:
Data Preprocessing and Feature Engineering
Propensity Score Matching (PSM) with Caliper
Difference-in-Differences (DiD) analysis
User Segmentation through Quadrant Analysis
Visualization of Results through Causal Plots
### Results
The analysis yields insights into how specific pricing strategies affect sales across different consumer segments. The project identifies the causal relationships that drive purchasing decisions and provides actionable recommendations for e-commerce businesses.
### Key Outcomes:
Identification of Persuadables, a key consumer segment highly responsive to price reductions.
Insights into effective pricing strategies tailored to different consumer groups.
Evaluation of the impact of dynamic pricing models on conversion rates and customer satisfaction.
### Tools Used
Python: For data analysis and model implementation.
StatsModels: For regression analysis and DiD implementation.
DoWhy: For causal validation.
Matplotlib/Seaborn: For visualizing results and analysis.
### Conclusion
This project demonstrates the effectiveness of applying causal inference techniques to pricing strategy analysis in e-commerce. The findings provide businesses with a framework for optimizing pricing strategies, ultimately improving sales performance and customer satisfaction.
