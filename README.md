## 👥 Aksi Hijau - Capstone Project Bangkit 2023
Group = C23-PS329 

Member =
- (ML) M160DSX0257 –  Irfan Divi Zianka 
- (ML) M282DSY0240 – Vina Maulida Junia 
- (CC)  C287DSX0741 – Juan Angela Alma 
- (CC)  C287DSX0883 – Yusril Isra Mahendra 
- (MD) A360DKX4118 – Reynhard Powiwi 
- (MD) A287DKX3849 – Rayyan Nur Fauzan 

## 🌳 Aksi Hijau App
Aksi Hijau App is an application designed to assist communities in conducting campaigns with a focus on tree planting. The app includes features such as soil analysis using Machine Learning 📊 and recommendations for suitable tree species 🌱 to plant. It is built using various technologies including Retrofit 🌐, SharedPreferences 🔐, ViewBinding 🔗, TensorFlow Lite 🧠, Material Components 💎, RecyclerView ♻️, and many more.
 
# EDA & Data Preparation 

Our dataset include 6 type of soil ( Aluvial, Andosol, Mediteran, Organosol, Podsolik, Regosol ) in Indonesia and total dataset is 570 images.

# Data Processing 

Our dataset separated with 2 folders ( train and validation ) , because our dataset is small, we use a technique called image augmentation to increase the accuracy of the model.

# Machine Learning Model

We use model MobileNetV2 for training data and create layer model ( keras layer and dense layer ) , and get accuracy > 96 % for soil classification type and save the model with keras model h5.

# Model Deployment

After model already, we use tensorflow lite to convert the model and ready deploy to Android Studio


