# Analyse-A-B-Test-Results
For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

<b>What Software Do I Need?</b><br>
To complete this project, i'll require the following softwares:
<ul>
<li>Python (Numpy, Pandas, Matplotlib, StatsModels, Scipy)</li><br>
<li>Jupyter Notebook</li><br>
</ul>
<b>Part I - Probability</b><br>
Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

<b>Part II - A/B Test</b><br>
Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%.

The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

<b>Part III - Regression</b><br>
Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

Next, along with testing if the conversion rate changes for different pages, I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.

<b>Conclusions</b><br>
<ol>
<li>There was no evidence suggesting that those who explore either page will neccessary lead to more conversions</li>
<li>The country of the user did not impact the rate of conversion between the two pages</li>
</ol>
