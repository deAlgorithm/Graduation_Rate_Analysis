<h2>👩‍🎓🎓Graduation Rate Analysis📊</h2>

![people](https://github.com/deAlgorithm/graduation_rate/assets/131563995/a7dc781b-ae83-4295-9d01-c0387b363754)


This dataset can be downloaded <a href="#"> Here </a>

# Graduation Rate Dataset Analysis

## Overview
This project analyzes a dataset on students' graduation rates and their influencing factors such as ACT scores, SAT scores, parental education, parental income, high school GPA, and college GPA. The objective of this analysis is to identify patterns and trends in the data to understand the factors affecting graduation rates.

## Table of Contents
- Overview
- Data Description
- Tools Used
- Analysis and Insights
- How to Use This Repository
- Key Questions Answered
- Conclusion
- Future Improvements

## Data Description
The dataset used for analysis consists of various attributes related to students' academic performance and parental background. It comprises records across multiple columns, including ACT composite score, SAT total score, parental level of education, parental income, high school GPA, college GPA, and years to graduate. The dataset provides comprehensive insights into the factors influencing students' graduation rates.

## Tools Used
The tools used for this analysis are:
- Python (including pandas, matplotlib, seaborn)

## Analysis and Insights
From the imported dataset, the dataframe consists of the following columns:
- `ACT composite score`
- `SAT total score`
- `parental level of education`
- `parental income`
- `high school gpa`
- `college gpa`
- `years to graduate`

### Key Insights:
- **Correlation Analysis:** The correlation matrix helps identify the relationships between different numeric variables.
- **Distribution Analysis:** Histograms and box plots visualize the distribution of various numeric attributes.
- **High School GPA vs. College GPA:** A scatter plot highlights the relationship between high school GPA and college GPA.
- **Impact of Parental Education:** Box plots show how different parental education levels affect students' academic performance and graduation time.

## How to Use This Repository
Provide instructions on how to clone, install dependencies, and run your code locally. For example:
1. Clone the repository:
   ```
   git clone https://github.com/deAlgorithm/graduation-rate-analysis.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
## Key Questions Answered
1. **What is the average ACT composite score and SAT total score of students?**
   ```
      Average ACT Composite Score: 28.607
      Average SAT Total Score: 1999.906
   ```
3. **How does parental level of education impact students' high school and college GPA?**
   ![image](https://github.com/deAlgorithm/graduation_rate/assets/131563995/d0d744af-8355-4d6f-9eb0-6214620295d2)
  
   ![image](https://github.com/deAlgorithm/graduation_rate/assets/131563995/cc0c039e-4d4f-4f7b-8edf-78f4af56e69e)

   

   
   `
The analysis shows that parental level of education has a noticeable impact on       students' GPAs. Specifically, the box plots illustrate that students whose parents have higher levels of education, such as associate's degrees or master's degrees, tend to have higher high school and college GPAs on average. This trend suggests that parental education level could be a significant factor influencing academic performance.
   `
5. **Is there a correlation between parental income and students' academic performance?**
   ![image](https://github.com/deAlgorithm/graduation_rate/assets/131563995/070747eb-2ae2-42c2-aeec-d2d0ec3e0873)
```
The correlation between parental income GPA and college GPA is 0.27
```
   ![image](https://github.com/deAlgorithm/graduation_rate/assets/131563995/083fc732-18fd-40fd-ba13-7548e8758d61)
```
The correlation between parental school GPA and college GPA is 0.46
```

   ``
While there is a positive correlation between both parental income and parental school GPA with students' college GPA, the correlation is stronger for parental school GPA. This implies that parental academic performance (as measured by their GPA) might be a better predictor of their children's academic performance than parental income.
   ``
7. **What is the average number of years taken to graduate?**
```
Average Number of years taken to graduate: 4.982
```
9. **How do high school GPA and college GPA correlate?**
```
The correlation between high school GPA and college GPA is 0.52
```
10. **How does the GPA ratio (college GPA / high school GPA) vary across different parental education levels?**
```
A higher GPA ratio indicates that students performed relatively better in college compared to high school, while a lower ratio indicates the opposite.
```
12. **What factors most strongly correlate with a higher college GPA?**

## Conclusion
### Summary of Findings
1. **Correlation Analysis:** Certain factors such as parental income and high school GPA show strong correlations with college GPA and years to graduate.
2. **Distribution Trends:** The distributions of ACT scores, SAT scores, and GPAs provide insights into the academic performance of the student population.
3. **Parental Influence:** Parental education and income significantly impact students' academic success and graduation timelines.

### Implications
- **Educational Support:** Insights can help educational institutions identify students who might need additional support based on their backgrounds.
- **Policy Making:** Policymakers can use this data to create programs aimed at improving graduation rates by addressing key influencing factors.

## Future Improvements

### Potential Enhancements and Analyses
1. **Predictive Modeling:**
   - Develop predictive models to forecast students' graduation rates based on their academic and parental backgrounds.
2. **Detailed Segmentation:**
   - Perform deeper segmentation to identify specific student personas based on their academic performance and parental background.
3. **Longitudinal Study:**
   - Extend the analysis to include longitudinal data to understand how students' academic performance evolves over time.
4. **Intervention Strategies:**
   - Propose targeted intervention strategies to help students who are at risk of delayed graduation or poor academic performance.

