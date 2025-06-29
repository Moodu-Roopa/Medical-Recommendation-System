🩺 Medical Recommendation System
A machine learning-based system that recommends medical treatments or classifications based on input symptoms or patient data. It compares the performance of multiple classifiers like Naive Bayes, Random Forest, and SVM to assist in health-related decision-making.
This is an AI-powered web application that predicts diseases based on user-provided symptoms and offers **personalized health recommendations**, including **precautions**, **medications**, **diets**, and **workouts**. The system uses a machine learning model (SVM) and is built with Python and Flask.

## 💡 Features

✅ Predict diseases based on symptoms  
✅ Input symptoms manually or via **speech recognition**  
✅ Get detailed health info:
- Disease description
- Precautions to follow
- Recommended medications
- Diet suggestions
- Workout tips

✅ Clean UI using **Bootstrap 5**  
✅ Modal popups for categorized results  
✅ Flask-based backend  
✅ Trained on a medical dataset with 40+ diseases

---

## 🧠 Technologies Used

- Python 3.x
- Flask
- Scikit-learn (Support Vector Classifier)
- Pandas & NumPy
- HTML5, CSS3, Bootstrap 5
- JavaScript (Speech Recognition)

## 🚀 How to Run the Project
1. Create a Virtual Environment (Optional but Recommended)

python -m venv venv

source venv/bin/activate   # On Windows: venv\Scripts\activate
2. Install Required Packages
pip install -r requirements.txt
3. Run the Flask App
python main.py
4. Access the App
Open your browser and visit:
http://127.0.0.1:5000/


📊 Model Details
Model Type: Support Vector Classifier (SVC)

Input: Binary vector of symptoms (0/1)

Output: Predicted disease

Training Data: Training.csv (symptoms → disease)

🎤 Speech-to-Text Input
The app supports speech recognition via webkitSpeechRecognition (Chrome only).

Click the mic button and say your symptoms (e.g., "itching, fever, cough").

🙋‍♀️ Developer
Moodu Roopa
AI/ML Engineer | Data Scientist | Healthcare Technologist
📧 moodroopa1169@gmail.com

📍 Hyderabad, Telangana, India

📢 Acknowledgements
Dataset collected and curated for academic use

Frontend powered by Bootstrap

Inspired by the need to make healthcare information more accessible

