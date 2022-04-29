How can we predict the food sales from different markets?
By using several methods of analysis and modeling to find the factors that affect sales

Author: Ashley Grant-Hewitt

Business problem:
Predict the amount of sales for food items sold at various stores

Data:
Data was sourced from https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

Methods:
The data was explored via inspection, cleaning, and visualization. Duplicates were removed, data discrepencies were fixed, and missing data was dropped as well as other columns that did not pertain to solving the buisness problem.

Results:
Number of Food Sales for Each Outlet 

![Screen Shot 2022-04-28 at 11 57 09 PM](https://user-images.githubusercontent.com/96153312/165883292-461985c2-7706-46e7-9d7c-1bda8a6dcc6e.png)

In the graph above, we see that the most food sales are coming from supermarket type 3. We should focus on why this outlet has so many sales. is it because there are more of these outlets? 


Amount of Outlets

![Screen Shot 2022-04-28 at 11 56 31 PM](https://user-images.githubusercontent.com/96153312/165883509-7260f65e-2075-43f1-bd32-906518aa241c.png)

In the graph above, we see the amount of each market type. Supermarket type 1 is the most common but it is not producing as many sales as the type 3 market. If we added different types of markets, would they have higher sales?


Recommendations:
We clearly see that supermarket type 3 is making the most sales. Thus, we want to be able to predict the future food sales of other market types, in order to determine if a new market could perform better or worse than supermarket type 3. Therefore, I created three different models on this data set. (linear regression, simple descion tree, best depth decsion tree)

I recommend the model known as "best_tree" because the R2 value for the training and testing data are close to each other but also over 50%. This model also perfroms better than the regression model which has its R2 values under 60% and better than the regular decision tree because that model was overfit. This model shows low bias and low variance giving the model a good balance which shows it is neither overfit or underfit to the data.


Limitations & Next Steps:
The best model was only able to predict the variance with about 60% accuracy. Ideally a model 80% or higher would be considered the "best". The next step would be to create another type of model that could make better predictions without creating an overfit model. With that information we could predict the future sales of each market type and target what needs to be changed or implemented to encourage more sales.

For further information
For any additional questions, please contact me
