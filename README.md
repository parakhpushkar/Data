# [E-Commerce revenue prediction](https://github.com/parakhpushkar/Data/blob/main/Ecommerce%20data%20-%20Linear%20Regression.ipynb)

The data here is an Ecommerce Customers csv file. It has Customer info, suchas Email, Address, and their color Avatar. Then it also has numerical value columns:

•	Avg. Session Length: Average session of in-store style advice sessions.<br>
•	Time on App: Average time spent on App in minutes.<br>
•	Time on Website: Average time spent on Website in minutes.<br>
•	Length of Membership: How many years the customer has been a member.<br>

So what are we looking for here? Our basic purpose behind this exercise would be to answer these two question:

**1. What should the company focus on to increase their revenue?**<br>
**2. How will the factors identified affect the revenue?**
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Let us look at the correlation between the numerical values to get an idea of important parameters.**

![](https://github.com/parakhpushkar/Data/blob/main/images/ecmm%20corr.png)

**Based off this plot it looks like 'Length of Membership' is a clear winner followed by 'Time on App'.<br> But this is where it gets tricky!**<br>
We will re-visit this later in our conclusion. 

This answers our first question to an extent. We will use Machine Learning to answer our second question.
