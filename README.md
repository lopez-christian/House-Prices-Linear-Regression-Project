## Multi-Variate Linear Regression Model 

# Building a Multi-Variate Linear Regression Model using King County,WA House Prices Dataset
# Using Scikit-Learn 

<p align="center">
<img width="279" alt="Screen Shot 2020-04-27 at 10 03 24 PM" src="https://user-images.githubusercontent.com/53641091/80449054-f4cff300-88d2-11ea-80fb-7e6afd8e6d8d.png">
</p>

This project will make use of Pandas, and NumPy for the data exploration phase as well as using Matplotlib and Seaborn to form visualizations. We will then be using Scikit-Learn to model our multi-variate linear regression. We will incorporate some dummies datasets creation to deal with categorical data as well as log-transformation methodology to deal with the continuous features of the dataset. 

# Columns we will be examining:

<img width="611" alt="Screen Shot 2020-04-25 at 6 14 27 PM" src="https://user-images.githubusercontent.com/53641091/80294763-b1ce1e00-8720-11ea-9f56-c51276265b29.png">

# Example of dataframe head and tail:

<p align="center">
<img width="995" alt="Screen Shot 2020-04-25 at 6 12 02 PM" src="https://user-images.githubusercontent.com/53641091/80294717-47b57900-8720-11ea-9141-b6f832eb29ef.png">
</p>

# Purpose of project:

The purpose of this project is to come up with ways in which to maximize profitability for sellers attempting to sell a home in King County,WA. We will search for actionable insights that will serve guidance to these sellers, but we need a thorough understanding of the dynamics of the housing market in order to drive our calculated decisions.

# 3 Recommendations I would suggest to sellers: 

**Recommendation # 1:**

<p align="center">
<img width="236" alt="Screen Shot 2020-04-25 at 6 27 13 PM" src="https://user-images.githubusercontent.com/53641091/80294902-9c59f380-8722-11ea-8dee-247a46846fb5.png">
</p>

My first recommendation to sellers would be to make living space square footage their focal point. Correlation between square footage of living space and price of the home is fairly high compared to the other features. It is clear that larger homes mandate higher asking prices. Selling homes on the larger-end of the spectrum are guaranteed to generate the most revenue. 

**Recommendation # 2:** 

<p align="center">
<img width="875" alt="Screen Shot 2020-04-25 at 6 35 30 PM" src="https://user-images.githubusercontent.com/53641091/80294997-90226600-8723-11ea-9691-3886b4e045c8.png">
</p>

My second recommendation would be to pay particular attention to the locality of the home. House prices are clustered according to zipcode. Many factors and variables, tied into the zipcode, may influence the price either positively or negatively and we must be mindful of that. 

**Recommendation #3:** 

<p align="center">
<img width="405" alt="Screen Shot 2020-04-25 at 6 41 15 PM" src="https://user-images.githubusercontent.com/53641091/80295072-5dc53880-8724-11ea-9fba-64d650a94087.png">
</p>

My third recommendation would be to attend to the grade given by King County to the home. It is very influential in the price of the home. In general, as the grade increases, the price increases as well. This highlights the positive linear correlation between the two. 

<p align="center">
<img width="391" alt="Screen Shot 2020-04-25 at 6 50 05 PM" src="https://user-images.githubusercontent.com/53641091/80295186-99143700-8725-11ea-93e6-d8da153679d4.png">
</p>

*Sidenote: The grade distribution follows a normal curve, which suggests that they are being issued in a forthright and diligent manner. If interested it would be engaging to see what goes into the grading component of the homes. But that's a project for another time.*

<p align="center">
<img width="392" alt="Screen Shot 2020-04-25 at 6 58 08 PM" src="https://user-images.githubusercontent.com/53641091/80295376-0d9ba580-8727-11ea-9006-cccffa1205dc.png">
</p>

This correlational heatmap was used throughout the project to guide me in the feature selection process and may be very helpful and finding other interesting correlational to experiment with. 

# Multi-variate linear regression model using Scikit-Learn:

<p align="center">
<img width="951" alt="Screen Shot 2020-04-25 at 7 11 13 PM" src="https://user-images.githubusercontent.com/53641091/80295595-daf2ac80-8728-11ea-8b18-899f855c3c80.png">
</p>

<p align="center">
<img width="453" alt="Screen Shot 2020-04-25 at 7 11 32 PM" src="https://user-images.githubusercontent.com/53641091/80295596-dd550680-8728-11ea-8610-7c90ece028ed.png">
</p>

<p align="center">
<img width="453" alt="Screen Shot 2020-04-25 at 7 11 42 PM" src="https://user-images.githubusercontent.com/53641091/80295599-e1812400-8728-11ea-9957-72a3c4455965.png">
</p>

<p align="center">
<img width="953" alt="Screen Shot 2020-04-25 at 7 13 02 PM" src="https://user-images.githubusercontent.com/53641091/80295603-e47c1480-8728-11ea-9355-6748e7665958.png">
</p>

<p align="center">
<img width="953" alt="Screen Shot 2020-04-25 at 7 13 16 PM" src="https://user-images.githubusercontent.com/53641091/80295606-e7770500-8728-11ea-9953-4d8a1ff15fc2.png">
</p>

## Please take a look at the jupyter notebook file included with this repository. I include bonus recommendations and future work/research to keep in mind if you hope to expand on my work. 

# Key takeways:

**1. Make living space square footage your number one feature to look out for.**

**2. Location is an extremely important feature when evaluating the price of a home.**

**3. The grade given to a home by the King County Housing Department is very influential in the price.** 
