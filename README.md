# FoodHub Customer & Business Analytics

## Overview
This project analyzes customer orders from FoodHub, an online food delivery platform, to understand ordering behavior, operational performance, and revenue patterns. The goal is to extract actionable insights that can help improve delivery efficiency, customer experience, and business outcomes.

Using exploratory data analysis (EDA), the project examines order values, cuisine preferences, preparation and delivery times, customer ratings, and demand patterns across weekdays and weekends.

## Business Objective
FoodHub aims to improve operational efficiency and customer satisfaction by better understanding how customers interact with the platform. The analysis focuses on identifying key drivers of revenue, operational bottlenecks, and customer engagement patterns.

The project addresses questions such as:
- What types of orders contribute most to revenue?
- How do preparation and delivery times impact the customer experience?
- Are there differences in demand patterns across weekdays and weekends?
- What insights can be derived from customer ratings?

## Dataset
The dataset contains order-level information from the FoodHub platform, including:
- Order value
- Cuisine type
- Restaurant preparation time
- Delivery time
- Customer rating
- Day of the week
- Order identifiers and operational details

Each record represents a single customer order placed through the platform.

## Tools & Technologies
The analysis was conducted using Python and common data analysis libraries:
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Workflow
The project follows a structured exploratory data analysis process:

1. **Data inspection and cleaning**
   - Checking dataset structure and data types
   - Identifying and handling missing values

2. **Univariate analysis**
   - Distribution of order values
   - Frequency of cuisine types
   - Distribution of preparation and delivery times
   - Ratings distribution

3. **Bivariate and multivariate analysis**
   - Relationship between order value and ratings
   - Delivery performance patterns
   - Cuisine demand patterns
   - Weekday vs weekend ordering behavior

4. **Operational insights**
   - Identifying potential delivery bottlenecks
   - Understanding high-value order patterns
   - Examining rating trends

## Key Insights
Some key observations from the analysis include:

- A small proportion of higher-value orders contributes significantly to overall revenue.
- Weekend demand is generally higher than weekday demand, suggesting different operational requirements.
- Delivery time variability is a potential bottleneck affecting customer experience.
- Customer ratings are skewed toward higher values and contain a notable portion of missing feedback.

## Recommendations
Based on the analysis, the following recommendations can support improved business performance:
- Optimize delivery logistics during high-demand periods, particularly weekends.
- Prioritize operational efficiency for high-value orders that drive a larger share of revenue.
- Improve mechanisms for collecting customer feedback to obtain more complete rating data.
- Monitor delivery time variability to identify opportunities for operational improvements.

## Repository Contents
- **[FoodHub Data Analysis Notebook](FoodHub_Data_Analysis_Notebook.ipynb)** — Full exploratory data analysis notebook

