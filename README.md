ML INTERNSHIP TASK 
--
## ABOUT TASKS:
  
  ## HEAR DISEASE PREDICTION:
This project is a web-based Diabetes Risk Predictor built using Gradio to provide an instant health risk assessment from a clean, interactive user interface. The system relies on a Random Forest Classifier to analyze eight health metrics—such as Glucose, BMI, and Age—calculating the exact probability of diabetes and classifying the outcome based on a 50% risk threshold.

To ensure fast deployment, the application first attempts to download a pre-trained model and a StandardScaler directly from a Hugging Face repository. However, if these external files are unavailable, the script includes a smart fallback mechanism that automatically trains a brand-new model from scratch in about five seconds using the classic Pima Indians Diabetes Dataset fetched from GitHub.

Before training this fallback model, the pipeline performs crucial data cleaning by identifying invalid 0 values in columns like Insulin and BMI and replacing them with the column's median value. Once the data is cleaned, the features are normalized using the scaler to prevent larger numbers from distorting the model, and a Random Forest model with 100 decision trees is trained on the spot to ensure the web application remains fully functional.
  Completed these task which help me strenghten my skill as ML Engineer, I got to work with differemt ML algos, Fine-tuining of models, Hyperparametering of models

This repository is testimonial to dedication to my field and 
