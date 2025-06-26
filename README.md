# AICUP 2024 - Solar Power Forecasting using LSTM

## Project Overview
As solar energy becomes a significant source of renewable power, its inherent instability poses challenges to the operation of smart grids. The AICUP 2024 competition focuses on predicting the average solar power output at 10-minute intervals based on historical microclimate data. The objective is to minimize the total absolute error between predicted and actual power output values.


## Model Architecture

### Libraries

The model was built using **TensorFlow (Keras API)**, with the following key components:
- `tensorflow.keras.models.Sequential`  
- `tensorflow.keras.layers.LSTM`  
- `tensorflow.keras.layers.Dropout`  
- `tensorflow.keras.layers.Dense`  
- `tensorflow.keras.models.load_model`  
- `tensorflow.keras.models.save_model`


## Evaluation Metric
Final scores were based on the sum of absolute errors between predictions and ground truth. Lower total error resulted in higher rankings.

## Results
- **Private Score**: 2,071,845.76  
- **Rank**: 248/934


## References:  
  - [TensorFlow LSTM API](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)  
  - [AICUP 2024 Competition](https://tbrain.trendmicro.com.tw/Competitions/Details/36)  
  - [Data Preprocessing Tool (YouTube)](https://www.youtube.com/watch?v=8Wvqr-vIh3A&t=724s)