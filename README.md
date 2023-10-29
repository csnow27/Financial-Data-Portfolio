# Financial Data Portfolio

## About
Hi, my name is Chris and I am an aspiring financial data analyst. I double majored in finance and business analytics at Boston College, developing a passion for solving problems through quantitative analysis. This repository will contain some of my independent investment/finance related projects to showcase my relevant skills.

When I began college, I only intended to major in finance, but I added a business analytics major after my sophomore year because I recognized the increasing prevalence and importance of data-driven decision making in the world. I was captivated by how organizations, specifically sports teams at first, were harnessing the potential of data to make informed decisions and unlock untapped opportunities. Adding that major has set me on a trajectory to pursue a career in the field of data analytics, preferably in finance to maximize my skillset.

## Portfolio Projects

### Brown Forman Stock Price Prediction Model
**Code**: [BF_stock_price_prediction.ipynb](https://github.com/csnow27/Financial-Data-Portfolio/blob/main/BF_stock_price_prediction.ipynb)

**Description**: Using Facebook's Prophet Model, a procedure for forecasting time series data, I created a program in Python that predicts the stock price for Brown-Forman ($BF-B) based on its last five years of trading data from Yahoo Finance. Steps to complete this analysis included loading the data from Yahoo Finance with pandas, cleaning and querying, exploratory data analysis, ensuring the Durbin Watson and Augmented Dickey-Fuller tests were passed, splitting the training and testing data, creating visualizations with MATPLOTLIB and evaluating model performance with forecast error terms and cross-validations. 

**Outcome**: While there isn't one specific conclusion to be made when evaluating a stock price prediction model, I did save the most recent 60 days of closing stock prices (August 4, 2023 to October 27, 2023) of $BF-B to use as a test set. No model is going to be 100% perfect, but my goal in this project was to build a solid framework to continue doing forecasting analyses in the future. My emphasis was on model evaluation - I wanted to ensure I was following all the steps and checking all the boxes before building the model itself and testing its accuracy. I was pleasantly surprised with its performance - my model's MAE (mean absolute error) was 5.56, which means that if I were to choose a random day from my test set (say August 8th) I would expect my model to predict the stock price to be $5.56 away from its true value. It's far from perfect and can almost certainly be improved upon (10 year sample size, larger test set, etc.) but for my first independent analysis I was pleased.

**Technical Skills Utilized**: Python, Jupyter Notebook, NumPy, Pandas, Seaborn, Matplotlib, Statsmodels, Sklearn, Prophet Model for Forecasting (Non-linear regression)
