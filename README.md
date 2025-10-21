Project Overview: The Air Quality Index (AQI) is an essential indicator of environmental health, directly affecting the well-being of people. This project aims to develop a machine learning model to predict AQI levels based on real-time environmental data. The goal is to create an accurate, reliable, and user-friendly system that can help authorities and individuals make informed decisions regarding air quality management.

Problem Statement: Air pollution is a growing concern in many urban and industrial areas. The ability to predict AQI can significantly improve public health awareness and policy-making by providing timely alerts and actionable insights. However, accurately predicting AQI is challenging due to the complex interplay of various environmental factors such as temperature, humidity, wind speed, and pollutant concentrations (PM2.5, PM10, NO2, SO2, CO, O3).

Data Collection: 
1. Government environmental monitoring agencies. •
2. Online APIs providing real-time air quality and weather data. 
3. Kaggle

Neural networks model: In our neural network model, we’re using a Multi-layer Perceptron (MLP) regressor, which is a feedforward artificial neural network commonly used for regression tasks.
Activation Function: ReLU (Rectified Linear Unit): ReLU is used because it helps to avoid vanishing gradient issues and speeds up the training process. It transforms the weighted sum of inputs into the output f(x)=max⁡(0,x). This means all negative inputs are zeroed out, and positive inputs remain unchanged

Hidden Layer Sizes: (50, 25)
The first hidden layer has 50 neurons.
The second hidden layer has 25 neurons. This structure allows the model to learn complex relationships in the data by progressively refining its features in each layer.

Learning Rate: 0.001
Max Iterations: 1000









