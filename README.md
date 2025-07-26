# 🧪 Hypothesis Testing in Python
This project demonstrates how to perform hypothesis testing on a sample dataset using Python. It focuses on evaluating whether a given sample provides enough evidence to reject a known population mean using a one-sample t-test.

🎯 Objective
To test whether the average battery life of a sample differs significantly from a known population mean.

📝 Hypothesis Definition
Null Hypothesis (H₀): The sample mean is equal to the population mean.

Alternative Hypothesis (H₁): The sample mean is not equal to the population mean.

This is a two-tailed test.

📈 Given Data
Sample Mean

Sample Standard Deviation

Sample Size

Population Mean (known)

Significance Level (α) = 0.05

These values were plugged into the t-test formula to calculate the test statistic and compare it to the critical t-value.

🧪 Test Performed
A one-sample t-test was performed because the population standard deviation was unknown and the sample size was small.

The test computed:

The t-statistic

The critical t-value

The p-value

These were then used to evaluate the null hypothesis.

✅ Conclusion
Based on the comparison:

If the p-value < α, we reject the null hypothesis — indicating a significant difference.

If the p-value ≥ α, we fail to reject the null hypothesis — meaning the sample is consistent with the population mean.

The notebook output includes a detailed result explaining the test outcome and statistical decision.

🛠️ Tools Used
scipy.stats for t-distribution and hypothesis testing

# 📊 Chi-Square Test for Independence
This project demonstrates how to perform a Chi-Square Test of Independence using Python. It evaluates whether two categorical variables are statistically independent or related.

🎯 Objective
To determine whether there is a significant association between two categorical variables using a chi-square test.

📝 Hypothesis Setup
Null Hypothesis (H₀): The two categorical variables are independent.

Alternative Hypothesis (H₁): The two categorical variables are dependent.

This is a right-tailed test.

📈 Input Data
A contingency table representing observed frequencies across different categories.

Expected frequencies are calculated under the assumption that the variables are independent.

🧪 Test Performed
A chi-square test was conducted using:

The chi-square test statistic

Degrees of freedom

The p-value

The critical chi-square value

These were compared to assess the validity of the null hypothesis.

✅ Interpretation
If the p-value < α, we reject the null hypothesis — indicating that the variables are dependent.

If the p-value ≥ α, we fail to reject the null hypothesis — suggesting the variables are independent.

The result was clearly interpreted in the output of the notebook.

🛠️ Tools Used
numpy

scipy.stats for performing the chi-square test

