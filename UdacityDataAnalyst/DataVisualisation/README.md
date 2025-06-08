# Prosper Loan Data Exploration

## Dataset

The dataset for this exploration can be accessed from this [online storage service](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000), kindly uploaded by Udacity. Detailed documentation on the features can be found [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000).

## Summary of Findings

During the exploration phase, I hypothesized that two features, "Employment Status" and "Verifiable Income Sources," would be strong predictors of my variable of interest. However, upon observing the distribution of "Verifiable Income Sources" concerning the variable of interest, I had to drop it from consideration.

By the end of the exploration, I deduced that individuals who meet the following conditions are more likely to complete their loans:

1. Employed, whether full-time, part-time, or employed.
2. Loan taken for personal reasons.
3. Average credit score between 650 and 750.
4. Recommendations count greater than or equal to 10.

In addition to the main variable of interest, I also observed some relationships between certain numeric variables. Notably, the "Recommendation Count" had a positive correlation with the count of investment from friends, indicating that more recommendations led to more friends investing in the loan. Additionally, there was a slight correlation between the "Average Credit Score Range" (averaged from the upper and lower credit score range) and the "Amount of Principal Payments Made Before Charged Off."

## Key Insights for Presentation

For the presentation, I focused on the variables "Employment Status," "Average Credit Score," and "Recommendations Count." I began by examining the distribution of the variable of interest, "Loan Status," followed by the distribution of "Employment Status."

Further investigations included plotting the distributions of other variables with histograms. Lastly, I explored the impact of these variables on the interaction between loan status and employment status using both boxplots and point plots.