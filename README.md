# Machine Learning Path - Classification Soil Type 

Team ID : C23-PS329
M160DSX0257 - Irfan Divi Zianka
M282DSY0240 - Vina Maulida Junia
 
# EDA & Data Preparation 

Our dataset include 6 type of soil ( Aluvial, Andosol, Mediteran, Organosol, Podsolik, Regosol ) in Indonesia and total dataset is 570 images.

# Data Processing 

Our dataset separated with 2 folders ( train and validation ) , because our dataset is small, we use a technique called image augmentation to increase the accuracy of the model.

# Machine Learning Model

We use model MobileNetV2 for training data and create layer model ( keras layer and dense layer ) , and get accuracy > 96 % for soil classification type and save the model with keras model h5.

# Model Deployment

After model already, we use tensorflow lite to convert the model and ready deploy to Android Studio


