### Observations and self notes ###

# Have to be more aware and should practice SVR
# SVR and Random forest seem to be more accurate but their training time seems to be longer.
# Increasing the 'degrees' in polynomial regression seems to also increase the training time as the data set is already big and it's creating more features by exponentiating all the columns. Makes sense
# Multiple linear regression and Decison tree regression seem to have pretty good accuracy (90<) but decision tree feels suspicious for some reason and I don't think it will do just as well with new data, i will have to learn more about it.

# One-hot encoding makes dummy variables they do not possess any order of importance. (Categories are independent with no order)
1  0  0
0  1  0
0  0  1

# Labeled encoding is the opposite of One-hot, it is used when categories have an order 
0 
1
3
2
