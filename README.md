# abn_project

## A/B/n Test at the University of Montana

#### This project was conducted by Samuel Oliveira.

# 1. Business Problem.

The University of Montana in the United States offers various student support services, including a library that provides several services such as study room allocation, books, computers, group discussions, webinars, among others, through its web page.

From April 3 to April 10, 2013, the library's homepage received 10,819 visitors. The analysis of the page access data showed a large discrepancy in accesses to the different service categories. 

The IT team at the university questioned why the click-through rate on the "Interact" category was very low, just 2%. The hypothesis raised was that the name "Interact" was confusing students. Therefore, four new names were proposed: "Connect", "Learn", "Help", and "Services".

An A/B/n test was conducted from May 29 to June 18, 2013 to validate which of the variations would be more understandable and attractive to students, with the expectation of increasing the click-through rate in this category.

# 2. Business Hypotheses.

The initial hypothesis is that changing the name "Interact" to "Connect", "Learn", "Help" or "Services" will increase the click-through rate in the respective category.

# 3. Solution Strategy.

The strategy to resolve this challenge was:

**Step 01. Data Description:**

The data collected from the website was analyzed. The main components analyzed were the different variants of the "Interact" category and the click-through rate on each one.

**Step 02. Feature Engineering:**

The dataset was manipulated to calculate conversion rates for each variant.

**Step 03. Data Filtering:**

Data was filtered to ensure uniqueness of users in each variant, preventing contamination of results.

**Step 04. Exploratory Data Analysis:**

Analysis of the different groups was carried out, and the conversion rate was calculated for each group.

**Step 05. Data Preparation:**

Data was prepared for the application of the hypothesis test.

**Step 06. Feature Selection:**

The features relevant to the hypothesis test were selected.

**Step 07. Statistical Hypothesis Test:**

A hypothesis test was carried out to determine whether the conversion rate for each variant of the new page was significantly different from the current one.

**Step 08. Interpretation of Results:**

The results of the hypothesis test were interpreted and the decision was made to accept or reject the null hypothesis.

# 4. Statistical Hypothesis Test

A Chi-Square Test was conducted to determine whether there is a significant difference in click-through rates among the variants.

# 5. Top 3 Insights from the Hypothesis Test

**Hypothesis 01:**

The "Connect" variant has a significantly different click-through rate compared to the "Interact" variant.

**True**

**Hypothesis 02:**

The "Services" variant has a significantly different click-through rate compared to the "Interact" variant.

**True**

**Hypothesis 03:**

The "Help" variant has a significantly different click-through rate compared to the "Interact" variant.

**True**

# 6. Business Results

The results of the hypothesis test suggest that the "Connect", "Services", and "Help" variants have significantly different click-through rates compared to the "Interact" variant. This indicates that changing the category name can influence the click-through rate.

# 7. Conclusions

Based on the results of the hypothesis test, it is recommended to change the category name from "Interact" to "Connect", as it exhibited the lowest Type I error rate.

# 8. Lessons Learned

The choice of a category name on a website can significantly influence click-through rates. The A/B/n test is a useful tool for validating design changes and optimizing user experience.

# 9. Next Steps for Improvement

Following the implementation of the "Connect" variant, it is recommended to monitor the click-through rate and conduct additional analyses to confirm the effectiveness of the change.

# LICENSE

# All Rights Reserved - DS Community 2022
