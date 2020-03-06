# Comparing Political Snapchat Data (RunTime & Spending vs Impressions) Among Candidates and Time
Is the effect of RunTime on Impressions always statistically insignificant or does it depend on the candidate/year?

Firstly, I decided to create linear regression models using open data on Snapchat political advertisements. For the first part, I created linear regression models using 2020 data for the following candidates: Trump, Pete, Warren, Biden, and Bloomberg. I took the Spending data given and created the variable(RunTime) by subtracting EndDate by StartDate, however this variable was only applicable to Pete, Bloomberg, Warren, and Biden, however, the latter two (Warren and Biden) had too limited political data for RunTime to be useful. Moreover, for the second part of my analysis, I decided to compare the linear regression models of a single advertiser over the three separate years of data given. Thus, I used the 2018, 2019, and 2020 Spending and RunTime data of Voto Latino. Voto Latino was chosen specifically because it marketed political advertisements over the course of all three years. 
# Part 1 - Political Candidates
![Pete](LinearRegression_Pete.PNG) (Figure 1 - Linear Regression Model Comparing Spending and RunTime for Pete)

![Bloomberg](LinearRegression_Bloomberg.PNG) (Figure 2 - Linear Regression Model Comparing Spending and RunTime for Bloomberg)

As seen by figures 4 and 5 (shown at the end), there aren't enough data points to show that Spending is even stastically significant for Warren and Biden. Additionally, Trump, in figure 3 (shown at the end), didn't have any EndDate's for his political ads (whether or not it may be that his ads are still running) so a RunTime could not be calculated. Spending for Trump was statistically significant, as suspected. Moreover, 
