# Loan Data Prosper Exploration

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. However, in this analysis, we reduced the number of the data to just 76,223 loans with 14 variabel due to the fact that there is a missing value and unnecessary variabel to make it into analysis.
This dataset could be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), and with the explanation to each variable [here](https://docs.google.com/spreadsheet/ccc?key=0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE&usp=sharing).

## Summary of Findings

<ul>
    <li>The Borrower APR Rate looks like a normal distribution and with the mean and median value almost slightly the same. But there is some high peak in the range of 30% to 35%.</li>
    <li>There is a strong evidence that Prosper Score and Prosper Rating has a linear realtionship with Borrower APR Rate. With the higher the score or rating is, the lower the Borrower APR Rate would be.</li>
    <li>There is also obvious relationship when comparing Borrower APR Rate againts Loan Status and Income Range, with the more income they earn, the less likely they will get lower APR Rate, and also the most of the borrower who are defaulted tend to have a higher APR Rate than the other who are not defaulted.</li>
</ul>

## Key Insights for Presentation

For the presentation, we just focus on the obvious pattern and relationship of Borrower APR Rate againts another variabel, we start by looking at the distribution of the Borrower APR Rate, After that, we try to compare with another variabel and we get a strong relationshop when comparing Borrower APR with four categorical variabel, those are Prosper Rating, Prosper Score, Income Range, and Loan Status.

##

