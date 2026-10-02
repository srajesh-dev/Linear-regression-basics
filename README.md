This is the start of my ML journey. Now that i have a decent understanding of numpy and pandas, i have written my first machine learning algorithm.
It uses Linear Regression, a type of ml to predict continuous data. Here it is marks obtained based on hours studied. 
MSE is mean squared error, an evaluation metric used in linear regression algorithms. 
The lower the MSE, the more accurate the ml. Here, my MSE is 75, which shows that my algorithm is not very accurate.

I was looking into why exactly my algorith isn't accurate and i learned that linear regression is built for linear data. Extreme data points or curves in the data lines
hinder the accuracy of the algorithm. In my dataset, we can observe that the data slowly flattens over time. the reason i made the data like this is because, when u 
study, the first one or two hours will get u a lot of marks, but the more u study, the amount of marks u get will decrease. So the data line 'flattens' slowly. This curves 
the line. Hence, my error margin is large, since linear regression is built for linear data. 
