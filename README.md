# ApexPlanet Task 4 – Data Storytelling & Statistical Validation

## Project Overview
This project focuses on e-commerce sales analysis, data storytelling, and statistical validation as part of the ApexPlanet Data Analytics Internship.
The objective is to analyze sales across product categories, visualize key findings, and use hypothesis testing to determine whether there is statistically significant evidence of differences in category-wise sales.

## Tools and Technologies
- Python
- Pandas
- Jupyter Notebook
- Statistical hypothesis testing
- Matplotlib and Seaborn
- GitHub

## Project Files
- `Task_4_Hypothesis_Testing.ipynb` – Jupyter Notebook containing the analysis.
- `ApexPlanet_Task4_Hypothesis_Testing_Summary.csv` – Hypothesis-testing results.
- `ApexPlanet_Task4_Final_Statistical_Summary.csv` – Summary of statistical tests.
- `ApexPlanet_Task4_Average_Sales_Confidence_Intervals.png` – Category-wise average sales and confidence intervals.
- `ApexPlanet_Task4_Final_Presentation.pptx` – Final project presentation.

## Hypothesis Testing

**Null Hypothesis (H₀):** The mean sales values are equal across the product categories.

**Alternative Hypothesis (H₁):** At least one product category has a different mean sales value.

A one-way ANOVA test was performed using a significance level of 0.05.

- **F-statistic:** 0.7171
- **P-value:** 0.5803
- **Significance level:** 0.05

### Result
Since the p-value is greater than 0.05, the null hypothesis was not rejected. The analysis did not find statistically significant evidence that mean sales differ across the product categories.
The Kruskal–Wallis test was also performed as a supplementary analysis, and it likewise did not find statistically significant evidence of differences in category-wise sales distributions.

## Key Insights
- Grocery had the highest observed average sales among the categories.
- Electronics had the second-highest observed average sales.
- The ANOVA test did not find statistically significant evidence of differences in mean sales across categories.
- The results should be interpreted with consideration of data distribution, outliers, and the independence assumption.

## Business Recommendations
- Monitor category-wise sales performance over time.
- Investigate customer preferences and product demand within each category.
- Consider additional data, such as profit, discounts, and sales trends, before making business decisions.
- Validate statistical assumptions and collect more data where necessary.

## Conclusion
This project combines exploratory data analysis, visualizations, confidence intervals, and hypothesis testing to communicate e-commerce sales findings clearly.
The results provide a starting point for further analysis and evidence-based business decisions.
