# Crop Prediction System

![](https://github.com/arjunrpai/Crop-Prediction-System/blob/main/prediction_output.png)

## Overview
Agriculture is a cornerstone of our society, but farmers often face challenges in choosing the most suitable crop due to changing weather conditions, soil characteristics, and market demands.  

To help farmers make **data-driven decisions**, this project presents a **Crop Prediction Model** that uses **machine learning algorithms** and **data analysis techniques** to recommend the best crop based on local environmental parameters.


## Features
- **Predicts the optimal crop** based on historical data and local environmental conditions.  
- **Provides details on fertilizers, seeds, and market prices** for the recommended crop.  
- **Estimates potential yield** (in quintals per acre) for the selected crop.  
- **User-friendly web interface** for easy input of local parameters and quick access to recommendations.  
- **Real-time weather integration** to enhance prediction accuracy.


## Dataset
The Crop Prediction Model is trained using the **Crop Recommendation Dataset** from Kaggle.  
This dataset includes detailed information on various crops, such as nutrient requirements, weather conditions, and other relevant factors.  
The data has been preprocessed and structured to serve as high-quality input for training the machine learning model.

**Dataset Source:** [Kaggle Crop Recommendation Dataset]([https://www.kaggle.com](https://www.kaggle.com/code/prasadchaskar/crop-prediction-99-accuracy))

![](https://github.com/arjunrpai/Crop-Prediction-System/blob/main/model_output.png)

## Technology Stack
- **Programming Language:** Python  
- **Machine Learning Framework:** Scikit-learn  
- **Web Framework:** Flask  
- **Frontend:** HTML, CSS, JavaScript
  
## Run the Flask app
Go to the Terminal, type  the below command
```bash
  python app.py
```



## Usage
1. Open the web application.  
2. Enter local parameters such as soil nutrients, temperature, humidity, pH, and rainfall.  
3. Click the **“Predict”** button.  
4. View the recommended crop along with details including fertilizers, seeds, market prices, and expected yield.



