In this particular project, we are using the flight fare dataset that contains information like airline, Date of journey, source, destination, route, departure time, arrival time, price etc and using that to predict the price of the flight. The process includes data cleaning, handling missing value and then applied Machine learning regression model to predict the price.

Label encoding applied to convert categorical data into numerical data. Data divided in training and testing with 80% data in training and 20% data in testing. We applied various Machine Learning regression algorithms to get best accuracy. From which it was identified that Random forest regressor is giving best accuracy. With hyper parameter tuning we are able to know that for n_estimators=400, max_depth=20, min_samples_split=5, min_samples_leaf=2, max_features= auto we are getting the best training and testing accuracy.

Training Set Accuracy: 92%
Testing Set Accuracy: 84%
