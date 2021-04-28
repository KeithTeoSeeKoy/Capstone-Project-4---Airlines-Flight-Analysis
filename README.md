# Capstone-Project-4---Airlines-Flight-Analysis
Capstone Project 4 - Airlines Flight Analysis (Flight Delay Predictive Analysis &amp; Airlines Review Sentiment Analysis)

This Capstone was inspired from our transport minister mentioning about the implementation of TravelBubble plus a <a href="https://static.airhelp.com/pdf/AirHelp+Airports+Score+2018+Methodology.pdf">website</a> I found. I took up the challenge and work out the following analysis. The duration of this Capstone Project (using purely Python) was super short, lasting for 4 weekdays plus Sat and Sun. I was glad that I pulled it through, putting up something decent enough. But of course, it could have been better given more time (as the saying goes).

This analysis consists of 2 parts:
1) Flight Delay Predictive Analysis. In this analysis, the dataset is downloaded from Kaggle. It is a pretty huge dataset of close to 6 million rows of data (Details are found in the slides below. Since the analysis is looking at predicting the flight delay, regressors model are being used. Extensive ETL and preprocessing are being done on the dataset, including feature engineering using SelectKBest, before subjecting it to do model evaluation and final prediction.

2) Airline Review Sentiment Analysis. Extending from Part 1, I went on to download tweets (from twitter) based on the Airline that I'm analyzing. In this case, I have chosen Delta Airline. After cleaning up the tweets, some EDA was done before the data was input into a LSTM model.

---
[Airlines Flight Analysis Presentation](https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/pdf/Airlines%20Flight%20Delay.pdf)

---

<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page1.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page2.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page3.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page4.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page5.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page6.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page7.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page8.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page9a.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page9b.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page10.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page11.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page12.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page13.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page14.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page15.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page16.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page17.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page18.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page19.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page20.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page21.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page22.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page23.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page24.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page25.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page26.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page27.JPG" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page28.JPG" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/AirlinesFlightAnalysis_Page29.JPG" width="600"/>
