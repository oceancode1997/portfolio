# PORTFOLIO
Here are some of the projects I worked on the past. 

# [Project 1: South Bend temperature predictions](https://github.com/oceancode1997/southbendtemperature)
- In this project, I Will use Linear regression model to analyze what environment factors are best to be used as predictors for -temperature in South Bend area. <br />
- Create a tool to predict the average temperature in the area using significant environment factors. Using this tool, one can predict the temperature in an area using:  albedo, fraction of low cloud, specific humidity, and incoming shortwaveflux. A prediction in South Bend temperature is featured below (MSE = 6.15). <br />
![](image/fitted%20value.PNG)  <br />
# [Project 2: Opioid use in Indiana](https://github.com/oceancode1997/opioid-use-in-Indiana)
- In this project, I use the opioid sales data from the [Washington Post](https://www.washingtonpost.com/graphics/2019/investigations/dea-pain-pill-database/) to find out what risk factors are significantly associate with opioid use in Indiana.  <br />
- The assocciated risks factor are mainly collected in [bureau census](https://www.census.gov/library/publications/2011/compendia/usa-counties-2011.html#POP) and a few other sources.  <br />
- By using the spatial temporal model for data from 2006-2011, I was able to find that unemployment rate and white proportion are the most significant risk factors. Counties that have higher unemployment rate consume higher opioid on average, and counties that have higher white population consume less opioid on average.  <br />
- Using the model, I also predicted the average opioid use in Indiana in 2012 and get MSE of 28.2. The prediction the model produced is shown below. <br />
![](image/prediction%20vs%20actual%20data%20in%202012.png)
# [Project 3: S&P 500 time series analysis](https://github.com/oceancode1997/SP500priceprediction)
- Using  different time series model to find the best model that can predict the log return of SP 500. <br />
We use SP 500 data from 1986 to 2018. We split data from 1986-2017 as training data, 2017-2018 as our test data. We also see if the best model works from 2018-2019. <br />
- The best model has forecast MSE of 0.0012 and accurately predicts the log return of S&P within 2 yearperiod within 2%. The model is shown below. <br />
![](image/SP500%20model.PNG)
# [Project 4: Simulation study: what criterion is best for linear model selection](https://github.com/oceancode1997/Stimulation-study-what-criterion-is-best-for-linear-model)
- Use simulation to find among popular criterion for model selection: AIC, BIC, Radjusted, PRESS, Mallow Cp. what is the best criterion to use when performing linear model selection. <br />
- Found that BIC outperforms other criterion is various settings. <br />
### Some of the smaller projects/competition I worked on
- (Titanic Survival Analysis)[https://www.kaggle.com/oceancode/titanic-survival-analysis-how-to-do-it-in-r]
- (Housing prediction using multiple linear regression)[https://www.kaggle.com/oceancode/linear-regression-for-house-prediction]
- (Digit recognizer using convolutional neural network)[https://www.kaggle.com/oceancode/digit-recognizer]
- (space invader game)[https://github.com/oceancode1997/spaceinvader]
