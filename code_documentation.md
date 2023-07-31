# Code Documentation: Website Redesign A/B Test

## 1. Data Loading and Conversion Rate Analysis
The code begins by importing the necessary libraries and loading the data from the CSV file into a pandas DataFrame (`df`). It then calculates the conversion rates for each group (combination of treatment and new_images) using the `groupby` function and the `mean` method. The conversion rates are stored in the `conversion_rates` variable and are printed to the console.

## 2. Grouped Bar Chart for Conversion Rates
The code proceeds to create a grouped bar chart to visualize the conversion rates for each group. It uses matplotlib to plot the bars for each group, with different colors representing different combinations of treatment and new_images. The labels for each bar are formatted for better readability.

## 3. A/B Test for Statistical Significance
Next, the code prepares the data for conducting the A/B test. It separates the DataFrame into four subsets representing each group (control_group, group_1, group_2, and group_3). Then, it defines a function `perform_ab_test` to conduct the two-sample t-test using `scipy.stats.ttest_ind` to compare each experimental group against the control group.

## 4. P-Values and A/B Test Results
The code performs the A/B tests for each experimental group (Group 1, Group 2, and Group 3) against the control group (No Treatment and No New Images). The p-values are calculated and printed to the console. The p-values indicate the probability of obtaining the observed differences in conversion rates between groups due to randomness alone.

## 5. Bar Plot for A/B Test Results
Finally, the code creates a bar plot to visualize the A/B test results. It uses the p-values obtained in the previous step to color the bars based on the significance level (p-value < 0.05). A red dashed line is added to represent the significance level (alpha = 0.05). The plot helps to identify which experimental groups have statistically significant differences in conversion rates compared to the control group.
