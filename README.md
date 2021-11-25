# Crude-Oil-Price-Prediction-using-Bayesian-Networks
### Abstract
This paper focuses on Crude Oil price prediction and regime detection using probabilistic graphical models. Crude Oil plays a crucial role in global economy and hence is a very critical indicator of industrial growth. Crude oil price depends on various macroeconomic, technical and financial factors. To take into account this causality, this paper uses probabilistic graphical models to learn the structure of the crude oil market. This paper proposes condensing data of numerous Crude Oil factors into a graphical model in the attempt of creating a accurate forecast of the price of crude oil and define an accurate trading strategy for the market players. This paper compares the structure learnt by 2 different structure learning algorithms over 3 different scoring methods in order to find the most accurate structure. Secondly, based on the structure learnt, it predicts the behaviour of the oil market.

### Objective
This paper has two major objectives:

- **Structure Learning:** We have identified various Technical, Economical and Financial factors that affects the crude oil price on a macroeconomic level. We have acquired this time series data from different sources and processed it into a single data frame. We have used this data to define the causality between these factors using correlation and and three different combinations of structure learning algorithms and scoring methods. These are:
  - Algorithm: Hill Climb Search; Scoring Method: K2
  - Algorithm: Hill Climb Search; Scoring Method: BDEU
  - Algorithm: Chow Liu
- **Crude oil price prediction:** From the above section, the model which shows the best performance has been used for predicting the behaviour of the oil market which can be used to decide a trading strategy for the market players.

### Results:

- **Structures Learnt:**
  - ***Hill Climb Search, K2 Scoring***  <img src="https://raw.githubusercontent.com/jds311/Crude-Oil-Price-Prediction-using-Bayesian-Networks/main/Resutls/HC_K2.png">

  - ***Hill Climb Search, BDEU Scoring***  <img src="https://raw.githubusercontent.com/jds311/Crude-Oil-Price-Prediction-using-Bayesian-Networks/main/Resutls/HC_BDEU.png">
  
  - ***Chow Liu Algorithm***  <img src="https://raw.githubusercontent.com/jds311/Crude-Oil-Price-Prediction-using-Bayesian-Networks/main/Resutls/chow_liu.png">

- **Correlation Matrix:**
  <img src="https://raw.githubusercontent.com/jds311/Crude-Oil-Price-Prediction-using-Bayesian-Networks/main/Resutls/CORR_MATRIX.png">
 
- **Regime Prediction**
   <img src="https://raw.githubusercontent.com/jds311/Crude-Oil-Price-Prediction-using-Bayesian-Networks/main/Resutls/pgm oil.png">
  
