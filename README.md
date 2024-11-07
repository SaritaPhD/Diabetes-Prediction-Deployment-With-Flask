# Diabetes Prediction Web Application
Business Objective
The objective of this project is to deploy a machine learning model through a Flask-based web application to predict whether a patient is diabetic or non-diabetic based on their medical details, such as glucose level, BMI, age, and other health indicators. This application aims to provide healthcare providers and patients with a tool to easily and quickly assess the likelihood of diabetes, aiding in early detection and intervention.   

## Business Constraints
- Real-time Prediction: The application should respond quickly to user input for an efficient and seamless experience.
- Scalability: The application may need to handle multiple users simultaneously.
- Model Compatibility: Compatibility of the deployed model with the production environment is critical, as differences in library versions may affect functionality.
- User Privacy: Patient data used for prediction should be handled securely to maintain confidentiality.
## Business Success Criteria
- User Experience: The application should have a user-friendly interface, allowing easy input of medical details and interpretation of results.
- Reliability: The app should perform consistently and return accurate predictions without downtime or errors.
- Interpretability: The prediction results ("Diabetic" or "Non-Diabetic") should be presented in a way that is easy for non-technical users to understand.
- Machine Learning Success Criteria
- Prediction Accuracy: The model should correctly classify patients as diabetic or non-diabetic based on the provided input data.
- Scalability: The model should support scaling up to handle increasing loads of prediction requests without significant degradation in response time.
## Project Structure
- application.py: The main Flask application script containing routes for the homepage and data prediction.
- Model/standardScalar.pkl: Pre-trained scaler object to standardize input features.
- Model/modelForPrediction.pkl: Pre-trained machine learning model used for diabetes prediction.
- templates/index.html: HTML template for the application's homepage.
- templates/single_prediction.html: HTML template for displaying individual prediction results.
- templates/home.html: HTML template for additional application pages if needed.
- Dataset/diabetes.csv: Dataset
## Running the Application
- Install required dependencies: pip install -r requirements.txt
- Run the Flask application: python application.py
- Access the app by navigating to http://localhost:5001 in your web browser.
## Dependencies
- Flask, Numpy, Pandas, Scikit-learn

