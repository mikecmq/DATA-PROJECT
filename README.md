# DATA-PROJECT
Initial Results 

In this section, all the main attributes will be explored, including attributes distributions, outlier check, correlation between order(y) and each attribute(x), correlation among each other, and split the data into training and test, after this section, three different regression models will be applying and evaluated to the data and conclusions will be drawn based on the models comparation.
1.Attributes distribution
             
2.outlier analysis 
Month, Day, Order, Color, Price, page,
      





3.coorelation between order and each other attributes
            





4.Correlation between attributes 
 







Modeling and result 
Model Type	RMSE	MAE	R-Square	Mean of Error	AIC
Multiple regress	24.69	20.31	0.057	0.062	925867.3
Regression tree	9.679	6.316	0.0017	0.319	N/A
KNN Regression	10.179	6.369	0.457	0.467	N/A
After running and evaluated each model, the performance as below:



Conclusion and Finding 
Regression tree model will be the best fit for this data set prediction purpose.
1.	Time, country, session.ID, page, color, location, and page have big impact for the order, but price and photography don’t have too much impact.
2.	Sales is much bigger in the first half month
3.	Czech Republic and Poland has the highest sales 
4.	Skirts have the highest average price of all goods, but trousers sell the highest number of units and generate the most dollars in sales by a significant margin. Sales items bring in the least money, but generate more sales than either blouses or skirts.
5.	Pages one and two have the highest priced items, and account for over 80% of all sales and dollars. Page 5 accounts for the fewest sales, but it is unknown if it has as many items shown as pages 1-4. Page 3 has the least expensive items of all pages.
     
