# CNN_Cancer_Detection
# Breast Cancer Detection Web Application

This project aims to detect breast cancer using histopathology images. It includes a web application with APIs for predicting whether an image contains cancerous cells or not.

## Features
- Train a machine learning model to classify histopathology images as positive (cancerous) or negative (non-cancerous).
- Deploy the trained model as a web service, allowing users to upload images and receive predictions.
- Utilize APIs to integrate the model into other applications or platforms.
- Implement web localization to support multiple languages.

## Data Set Link
https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images

## Getting Started
1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the web application using `python flaskapp.py`.
4. Access the application in your web browser at `http://localhost:5000`.

## Usage
1. Upload a histopathology image to the web application.
2. Click the "Predict" button to receive a prediction.
3. View the prediction result, indicating whether the image contains cancerous cells or not.

## Model Training
If you wish to train or retrain the model:
1. Ensure you have the necessary dataset.
2. Use the provided Jupyter Notebook or Python script to preprocess the data and train the model.
3. Save the trained model architecture and weights.
4. Update the deployed model with the new weights and architecture.

## APIs
To use the APIs for prediction:
1. Create an instance of the `Api_service` class, providing the path to the image file.
2. Call the `prediction_function` method to receive prediction results.

## Web Localization
The web application supports multiple languages for user interface localization. 
Users can select their preferred language from the language dropdown menu.

## Notes
- For best results, ensure that the input images are of sufficient quality and resolution.
- The model performance may vary based on the dataset and preprocessing techniques used.

For any questions or issues, please contact dhanushdevadiga1109@gmail.com.
