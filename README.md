# [E-Commerce revenue prediction](https://github.com/parakhpushkar/Data/blob/main/Ecommerce%20data%20-%20Linear%20Regression.ipynb)

The data here is an Ecommerce Customers csv file. It has Customer info, suchas Email, Address, and their color Avatar. Then it also has numerical value columns:

•	Avg. Session Length: Average session of in-store style advice sessions.<br>
•	Time on App: Average time spent on App in minutes.<br>
•	Time on Website: Average time spent on Website in minutes.<br>
•	Length of Membership: How many years the customer has been a member.<br>

So what are we looking for here? Our basic purpose behind this exercise would be to answer these two question:

**1. What should the company focus on to increase their revenue?**<br>
**2. How will the factors identified affect the revenue?**

**Let us look at the correlation between the numerical values to get an idea of important parameters.**

![](images/ecmm%20corr.png)

**Based off this plot it looks like 'Length of Membership' is a clear winner followed by 'Time on App'.<br> But this is where it gets tricky!**<br>
We will re-visit this later in our conclusion. 

This answers our first question to an extent. We will use Machine Learning to answer our second question.

We will look into the coefficients we obtained through our Linear Regression Model to answer our second question.
![](images/ecomm%20coeff.PNG)<br>
Interpreting the coefficients:

- Holding all other features fixed, a 1 unit increase in **Avg. Session Length** is associated with an **increase of 25.98 total dollars spent**.
- Holding all other features fixed, a 1 unit increase in **Time on App** is associated with an **increase of 38.59 total dollars spent**.
- Holding all other features fixed, a 1 unit increase in **Time on Website** is associated with an **increase of 0.19 total dollars spent**.
- Holding all other features fixed, a 1 unit increase in **Length of Membership** is associated with an **increase of 61.27 total dollars spent**.

**Conclusion**<br>
There are two ways to think about this: Develop the Website to catch up to the performance of the mobile app, or develop the app more since that is what is working better. This sort of answer really depends on the other factors going on at the company so there is still a lot more exploring that can be done before coming to a conclusion!<br> But on the surface of it, we have answered our questions.
