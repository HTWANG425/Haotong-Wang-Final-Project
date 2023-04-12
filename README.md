# Haotong-Wang-Final-Project 
#Description  
This repository contains a collection of Python scripts that perform various tasks, including downloading images from Pexels, generating random geolocation data, generating SMS messages, detecting bank card images, visualizing concentrated geolocation data, and detecting bank card numbers in SMS messages.  
#Features  
Download images from Pexels using their API  
Generate random geolocation data in GPX format  
Generate SMS messages with the help of OpenAI's GPT-3 model  
Train a Convolutional Neural Network (CNN) to detect bank card images  
Visualize concentrated geolocation data using heatmaps  
Train a Long Short-Term Memory (LSTM) network to detect bank card numbers in SMS messages  
#Requirements  
Python 3.6 or higher  
TensorFlow  
Keras  
OpenAI  
gpxpy  
folium  
lxml  
Faker  
requests  
NumPy  
OpenCV (cv2)  
scikit-learn  
#Installation  
To install all the required libraries, run the following command:  
pip install tensorflow keras openai gpxpy folium lxml Faker requests numpy opencv-python-headless scikit-learn  
#Usage  
#Image Downloader  
Get an API key from the Pexels API and replace the API_KEY variable in the script.  
Set the search query, output directory, and other variables.  
Run the script to start downloading images.  
#Random Geolocation Data Generator  
Set the center point coordinates, number of data points, maximum distance, and other variables.  
Run the script to generate the GPX file with random geolocation data.  
The generated GPX file will be saved with the specified filename.  
#SMS Data Generator  
Get an API key from OpenAI and replace the openai.api_key in the script.  
Run the script to generate the XML file containing the SMS messages.  
The generated XML file will be saved with the specified filename.  
#Bank Card Image Detector  
Set the appropriate directories for training and validation images.  
Run the script to train the model and find bank card images in the specified input folder.  
Found images will be saved in the specified output folder.  
#Concentrated Geolocation Data Visualizer  
Replace the path to the GPX file with your own.  
Run the script to generate the map with the concentrated area.  
The generated map will be saved as an HTML file with the specified filename.  
#Bank Card Number Detection in SMS  
Replace the file path with the path to your XML file containing the SMS messages.  
Run the script to train the model and test the prediction function with a sample message.  
The prediction function will return the probability of the sample message containing a bank card number.  
