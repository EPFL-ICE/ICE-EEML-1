# ICE-EEML-1
### Human Energy Expenditure Prediction Models Using LSTM Networks


Human energy expenditure is a combination of static and dynamic components, the latter not being easy to define. Thanks to technological improvements, many devices provide us with estimates of our daily energy expenditure, but they are not always accurate. Recent studies have tried to improve energy expenditure estimation by developing machine learning and neural network models. Many of them are based on a general approach, where an unique model is used for many individuals. This study aims to use the Long-Short Term Memory (LSTM) network, the convolutional LSTM network (CNN-LSTM), and an ensemble of CNN-LSTM with a Light Gradient Boosting Model (LSTM-LGBM) to develop a real-time energy expenditure prediction model. We will develop personalized models, where an appropriate set of features from our measurments will be selected each time. It will consider the effect of physical activity, ambient temperature, and food intake of subjects. We conducted three different experiments with 6 test subjects wearing multiple sensors. Various protocols were designed to explore the variation in EE concerning varying ambient temperature, activity levels, and food intake. Our analysis has shown that during low-intensity activities, accelerometry data were sufficient to estimate EE accurately and that the modification of ambient temperature was reflected mostly by the skin temperature variables at the extremities of the body. For medium-intensity activities, heart rate is the most relevant factor, as well as accelerometry. For the effect of food intake on EE, the heart rate and skin temperature reflect well the thermogenesis in men, but the results are not so good for women. Based on our results, the models developed provide a good prediction accuracy during low and medium-intensity activities and food intake in a dynamic environment, with the MAPE, mostly lying in the range of 5-15\% and an RMSE between 0.05 and 0.4 kcal/min. The personalized modeling approach, using an appropriate set of features for each subject and activity, combined with LSTM networks can potentially improve the prediction accuracy compared to the pre-existing models.


### Methodology

Here are our protocols :

- Protocol A: Low activity activity. Change in ambient temperature.
- Protocol B: High intensity activity. Change in ambient temperature.
- Protocol C: Real-life working day, with working sessions in sitting and standing positions. Food intake. 

![Alt text](FIGURES/models.jpg?raw=true "Title")


### Results 
