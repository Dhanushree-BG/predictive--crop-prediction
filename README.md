# predictive -crop prediction
 TOP Crops repository
# Crop Prediction using Machine Learning
 TOP Crops prediction


 # OVERWIEW 

 This project aims to develop a machine learning based crop-prediction model to support farmers in making informed decisions about crop selection, planting, and harvesting. The model was trained on a large dataset of historical crop and weather data, using deep learning techniques. The results of the model showed high accuracy in predicting crop yield, surpassing the performance of traditional crop prediction methods. The model has been deployed with user-friendly interface, thus enabling farmers to input a few values and obtain informed decisions about when and what to plant. This project represents a significant step forward in using ML to improve the efficiency and profitability of agriculture.

# Data

 The data used to train the model was collected from the Crop Prediction dataset. The dataset consists of 2200 samples of 22 different crops whose predictions are made using 7 features: nitrogen, phosphorus, potassium, and pH content of the soil, temperature, humidity and rainfall. The dataset is perfectly balanced, with each crop having 100 samples. The Rainfall in India datset is used to cross reference geolocations to corresponding rainfall values. The data was pre-processed to ensure consistency and cleaned to remove any missing values. The data includes information on various crop types, weather patterns, and soil types. 

# Model

The model is built using Deep Neural Networks(DNNs). The architecture we have chosen consists of 3 hidden layers with 64, 128 and 64 neurons respectively, and an output layer of 22 neurons, each corresponding to one type of crop. The activation function in the input and hidden layers is SeLU, while the activation function for the output layer is softmax. The model was created using PyTorch framework.


# Training
The model is built using Deep Neural Networks(DNNs). The architecture we have chosen consists of 3 hidden layers with 64, 128 and 64 neurons respectively, and an output layer of 22 neurons, each corresponding to one type of crop. The activation function in the input and hidden layers is SeLU, while the activation function for the output layer is softmax. The model was created using PyTorch framework.

# Results
The model achieved an accuracy of 99% on the train data, and an accuracy of about 99% on the test data, indicating a high level of accuracy in its predictions.


# Testing

The following data is collected from the end-user to make predictions:

N, P, K, pH content of the soil.
Geolocation (State and District)
Month(Season) of cultivation
