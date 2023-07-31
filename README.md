# Website Redesign A/B Test Results

## Background
Welcome to the summary of our recent website redesign A/B test! Our early-stage startup in Germany has been working on improving our landing page to increase user engagement and conversions. We conducted a few weeks of testing to measure the impact of the changes and determine if they can be attributed to randomness or if they are statistically significant.

## The Data
We collected data on user interactions with different versions of the landing page:

- "treatment" - Indicates if the user saw the new version of the landing page ("yes" or "no").
- "new_images" - Indicates if the page used a new set of images ("yes" or "no").
- "converted" - 1 if the user joined the site, 0 otherwise.

## Task 1: Analyzing Conversion Rates
To begin, we analyzed the conversion rates for each of the four groups representing different combinations of design and images.

The conversion rates for each group are as follows:
- Control Group (Old Design, Old Images): 10.71%
- Group 1 (Old Design, New Images): 11.25%
- Group 2 (New Design, Old Images): 12.00%
- Group 3 (New Design, New Images): 11.37%

## Task 2: Testing for Statistical Significance
To determine if the observed increases in conversion rates are statistically significant, we performed A/B tests comparing each experimental group against the control group.

- Group 1 vs. Control Group: P-value = 0.2163 (Not statistically significant)
- Group 2 vs. Control Group: P-value = 0.0037 (Statistically significant)
- Group 3 vs. Control Group: P-value = 0.1330 (Not statistically significant)

## Conclusion
Based on the results of our A/B tests, we can draw the following conclusions:

1. **Group 2 (New Design with Old Images)**: The observed increase in conversion rate for Group 2 is statistically significant, indicating that the changes made in this group had a real impact on user engagement. Therefore, we recommend using this version of the website.

2. **Group 1 (Old Design with New Images)** and **Group 3 (New Design with New Images)**: The observed increases in conversion rates for these groups were not statistically significant. While there might be some improvement, we cannot confidently attribute the changes to the redesign.

## Final Decision
Our recommendation is to implement the **Group 2 version of the website (New Design with Old Images)**. This version showed both statistical significance and a meaningful improvement in conversion rates compared to the control group.

As with any A/B test, it's essential to consider the context and business implications of the findings. We encourage continuous testing and optimization to further enhance user experience and achieve even better results.

Thank you for following along with our A/B test analysis! If you have any further questions or need additional insights, feel free to reach out.
