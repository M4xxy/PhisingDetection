# PhisingDetection
Machine Learning Project
This application allows you to check if a website is likely phishing by analyzing its URL. 

**Features:**
* Enter a website URL.
* Select a prediction model (All, Random Forest, Gradient Boosting, AdaBoost).
* Get a prediction on whether the website is classified as "Phishing" or "Benign".
* Optionally, see predictions from all three models.

**Requirements:**

* Python
* Streamlit library 
* Scikit-learn library 
* Pre-trained phishing website detection models 
* Pandas library 

**Instructions:**

1. Install required libraries using `pip install -r requirements.txt`.
2. Replace the placeholder functions (`load_model` and `predict_phishing`) in `main.py` with your actual model loading and prediction logic. 
    * Ensure your models are saved in a format compatible with scikit-learn.
    * The `predict_phishing` function should take the URL and a loaded model as input and return a prediction ("Phishing" or "Benign").
3. Run the app using `streamlit run main.py`.

**Note:**

* This is a basic example for educational purposes only. 
* Train your own phishing detection models on a relevant dataset before deployment in a real-world setting.
* This app should not be solely relied upon for real-world phishing detection.
