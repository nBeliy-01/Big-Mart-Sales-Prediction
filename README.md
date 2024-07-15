# Big Mart Sales Prediction Using XGBRegressor
This repository contains a Jupyter Notebook for predicting sales in different outlets of a big mart using machine learning techniques, specifically the XGBRegressor model. This notebook received 43rd place at the <a href="https://www.kaggle.com/competitions/ml-competition-2024-for-ukrainians/leaderboard" target="_blank">Machine Learning Competition</a> and model get RMSLE error score 0.70165

### Here are some points for better understaning
<ul>
  <li>Data processing for both test and train datasets</li>
  <li>Pay attention on <b>Item_Fat_Content</b> variable</li>
  <li>Try to transform all possible variable values into normal distributed data</li>
  <li>Replace all object values into numerical mean or median target values</li>
  <li>Logarithmise your target values</li>
</ul>

### Final model's resulsts:
<ul>
  <li><b>R2 score:</b> 0.3193076191316865</li>
  <li><b>MAE score:</b> 0.5106070958560762</li>
  <li><b>MSE score:</b> 0.7040263705998989</li>
  <li><b>RMSLE score:</b> 0.70165</li>
</ul>
