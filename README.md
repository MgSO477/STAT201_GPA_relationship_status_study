# Statistical Study on the Impact of Relationship Status on Cumulative GPA


## Project Overview
This project investigates the relationship between students' cumulative GPA (CGPA) and their relationship status. The analysis employed hypothesis testing using both bootstrapping and asymptotic methods to evaluate whether there is a statistically significant difference in CGPA distributions between students in relationships and those who are not.

## Dataset
The dataset was sourced from a reputable educational institution, ensuring unbiased and representative sampling. It includes variables such as:
- **Relationship Status**: Binary (in a relationship vs. not in a relationship)
- **Cumulative GPA**: Numeric values representing academic performance

## Methods
1. **Exploratory Data Analysis**:
   - Descriptive statistics and visualizations to summarize the data.
2. **Hypothesis Testing**:
   - Null Hypothesis: There is no significant difference in the proportion of students with CGPAs ≥ 3.0 based on relationship status.
   - Significance Level: 0.05
   - Methods: Bootstrapping and asymptotics were used to calculate p-values and confidence intervals.
3. **Comparison of Methods**:
   - Bootstrapping: Provides robust estimates but is computationally intensive.
   - Asymptotics: Relies on the Central Limit Theorem and is computationally efficient.

## Results
- **Bootstrapping**: p-value = 0.964
- **Asymptotics**: p-value = 0.958
- Both methods yielded similar results, confirming the validity of the findings.

### Key Insights
- No statistically significant evidence was found to suggest a difference in CGPA based on relationship status.
- The conditions for the Central Limit Theorem were satisfied, validating the use of asymptotic methods in this case.

## Discussion
Our analysis suggests that being in a relationship does not significantly impact a student's academic performance, as measured by CGPA. This challenges common perceptions that relationships might negatively affect academic outcomes due to time constraints or reduced motivation. However, the study does not conclude that relationships have no effect; rather, it finds insufficient evidence to reject the null hypothesis.

## Future Questions
- How do other factors, such as employment status or extracurricular activities, influence CGPA?
- Can a student’s CGPA be predicted using a combination of relationship status and other covariates?
- Do students in relationships allocate their time differently compared to those who are not?

## Impact
The findings have implications for students and educational institutions:
- **Students**: Encourages balanced decision-making regarding personal relationships and academic responsibilities.
- **Institutions**: Provides insights for developing support programs, such as counseling or workshops, to address students' diverse needs.


## How to Access
To view the full analysis:
1. Clone the repository:
   ```bash
   git clone https://github.com/MgSO477/STAT201_GPA_relationship_status_study.git
   cd stat201-cgpa-study
2. Open the GPA_and_relationship_sudy.html file in a browser to explore the methods, results, and visualizations.
