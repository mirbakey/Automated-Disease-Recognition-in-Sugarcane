# Automated-Disease-Recognition-in-Sugarcane
A machine learning algorithm that resides as a rest API on server side and does automated inference for absence or presence of a particular disease in sugarcane crop based on the image uploaded by the android app(included) .

A deep learning model for detection of 5 sugarcane diseases deployed on android
# Steps to run the model
Installation dependencies
1). Fastai v0.7 () 2). MySql 3). Flask-mysql-db for connectivity between database and model 4). Android Studio

# Configuration
Install the above dependencies.
1) Configure mysql with the details in accordance with demo.py file in Server-side dir.

2) Extract the model weights from archive in server-side directory and place them in models dir in your path mentioned in file demo.py

3) Import the app bundle in android studio and configure the util class according to your external ip address of the server.

4) Build the appllication and check for the connection
