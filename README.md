# 🌱 OptiCrop – Smart Agricultural Production Optimization Engine

OptiCrop is a machine learning-based agricultural recommendation system designed to optimize crop production using soil and environmental parameters. The project integrates machine learning algorithms with a Flask web application to provide intelligent crop recommendations, fertilizer suggestions, and crop disease detection. It aims to assist farmers, agricultural researchers, agribusiness companies, and policymakers in making data-driven farming decisions that improve productivity, sustainability, and resource utilization.

---

## 🚀 Features

- 🌾 Crop Recommendation based on soil nutrients and environmental conditions
- 🌱 Fertilizer Recommendation based on crop and soil information
- 🍃 Crop Benefits using machine learning
- 📊 Data preprocessing and machine learning model evaluation
- 💻 Responsive web interface built with HTML, CSS, and JavaScript
- ⚡ Real-time predictions using trained Machine Learning models
- 🌐 Deployed on Vercel

---

# 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Flask
- Python

### Machine Learning
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Pickle

### Development Tools
- Jupyter Notebook
- Visual Studio Code
- Git & GitHub
- Vercel

---

# 🔗 Project Resources

### 📂 Source Code Repository

**GitHub Repository:**  
https://github.com/Abhi-4363/smart_agriculture

### 🎥 Project Demo Video

**Demo Video:**  
https://drive.google.com/file/d/1p0kNiHHF7aImcYjtNiXX4dBxpo4wne9R/view

---

# 📂 Project Structure

```text
OptiCrop/
│
├── __pycache__/                 # Compiled Python files
├── recordings/                  # Uploaded crop images/recordings
├── static/                      # CSS, JavaScript, Images
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/                   # HTML templates
│
├── README.md                    # Project documentation
├── app.py                       # Main Flask application
├── convert_recordings.py        # Image/recording processing
├── crop_model.pkl               # Trained ML model
├── requirements.txt             # Python dependencies
└── test_app.py                  # Unit testing
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/Abhi-4363/smart_agriculture.git
```

```bash
cd smart_agriculture
```

---

## 2. Create a Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Start the Flask server.

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

# 📊 Machine Learning Workflow

1. Collect agricultural datasets from Kaggle and other reliable sources.
2. Analyze and preprocess the dataset by handling missing values and removing duplicate records.
3. Train multiple machine learning algorithms:
   - Random Forest
   - Decision Tree
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - K-Means Clustering
4. Compare model performance using evaluation metrics.
5. Save the best-performing model as a Pickle (`.pkl`) file.
6. Integrate the trained model into the Flask application.
7. Generate crop recommendations, fertilizer suggestions, and disease detection results.

---

# 🌾 Input Parameters

The Crop Recommendation module accepts the following inputs:

- Nitrogen (N)
- Phosphorous (P)
- Potassium (K)
- Temperature
- Humidity
- pH Level
- Rainfall

The Fertilizer Recommendation module accepts crop and soil details.

---

# 🎯 Application Modules

## 🌾 Crop Recommendation

Predicts the most suitable crop based on soil nutrients and environmental conditions.

---

## 🌱 Fertilizer Recommendation

Suggests the most suitable fertilizer according to crop and soil conditions.

---


# 🤖 Machine Learning Algorithms Used

The following machine learning algorithms were trained and evaluated:

- Random Forest
- Decision Tree
- Logistic Regression
- K-Nearest Neighbors (KNN)
- K-Means Clustering

The best-performing model was selected based on evaluation metrics and saved as a `.pkl` file for deployment.

---

# 🧪 Testing

The application was tested using:

- Different agricultural input values
- Browser-based testing
- Flask Development Server
- Model accuracy evaluation
- Input validation
- Performance testing

---

# 🌐 Deployment

The application is deployed on **Vercel**, making it accessible online through a web browser.

---

# 📸 Website Pages

- Home Page
- Crop Recommendation
- Fertilizer Recommendation
- Disease Detection
- Prediction Results

---

# 📈 Future Enhancements

- Real-time weather data integration
- Market price prediction
- Multilingual support
- GPS-based location recommendations
- User authentication and prediction history
- Continuous model retraining using updated datasets
- Mobile application support

---

# 🎯 Project Outcome

OptiCrop successfully combines Machine Learning and Flask to develop an intelligent agricultural recommendation system. The application provides crop recommendations, fertilizer suggestions, and agricultural benefits based on soil, environmental, and image data. By assisting users with accurate and timely recommendations, the system supports sustainable farming practices and improves agricultural productivity through data-driven decision-making.

---

# 👥 Contributors

- Abhirama Rao Konagalla
- Aishwarya Vacha
- Revanth Kumar Katakam
- Chilakala Manikanta Sai Anurudh
- Suryadevara Mohana Lakshmi