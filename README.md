# 🧠 AI Smart Nutrition Analyzer

An AI-powered web application that classifies fruits and vegetables from uploaded images and provides their estimated calorie information per 100 grams using a deep learning model.

---

## 📌 Overview

AI Smart Nutrition Analyzer is a Computer Vision project developed using **Python, TensorFlow/Keras, Streamlit, and Flask**. The application can identify **36 different fruits and vegetables** from an image and instantly display the predicted item along with its nutritional calorie information.

The project also includes a REST API for integrating the prediction model into other applications.

---

## 🚀 Features

- 🍎 Classifies **36 different fruits and vegetables**
- 🤖 Deep Learning model built using TensorFlow/Keras
- 📷 Upload image for instant prediction
- 🔥 Displays estimated calories (per 100 grams)
- 🥦 Identifies whether the item is a Fruit or Vegetable
- 🌐 Interactive Streamlit web interface
- 🔗 Flask REST API for prediction

---

## 🛠️ Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Streamlit
- Flask
- Pillow

---

## 📂 Project Structure

```
AI_Smart_Nutrition_Analyzer/
│
├── app.py
├── api.py
├── FV.h5
├── Fruit_Veg_Classification_Mobilenet.ipynb
├── Fruits_Vegetable_Classification.py
├── requirements.txt
├── README.md
├── .gitignore
└── upload_images/
```

---

## 🖥️ Installation

Clone the repository:

```bash
git clone https://github.com/shivkumar-biradar/AI-Smart-Nutrition-Analyzer.git
```

Move into the project folder:

```bash
cd AI-Smart-Nutrition-Analyzer
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 📊 Supported Categories

The model recognizes **36 categories**, including:

- Apple
- Banana
- Beetroot
- Bell Pepper
- Cabbage
- Capsicum
- Carrot
- Cauliflower
- Chilli Pepper
- Corn
- Cucumber
- Eggplant
- Garlic
- Ginger
- Grapes
- Jalapeno
- Kiwi
- Lemon
- Lettuce
- Mango
- Onion
- Orange
- Paprika
- Pear
- Peas
- Pineapple
- Pomegranate
- Potato
- Radish
- Soy Beans
- Spinach
- Sweetcorn
- Sweet Potato
- Tomato
- Turnip
- Watermelon

---

## 📷 Application Workflow

1. Upload an image.
2. Image is preprocessed.
3. Deep Learning model predicts the class.
4. Application displays:
   - Predicted item
   - Fruit/Vegetable category
   - Estimated calories per 100g

---

## 📸 Screenshots

Add screenshots here after uploading images.

Example:

- Home Page
- Prediction Result
- Calorie Information

---

## 📈 Future Improvements

- Multiple object detection
- Nutrition facts (Protein, Carbohydrates, Fat)
- BMI Calculator
- Voice assistance
- Mobile application
- Cloud deployment

---

## 👨‍💻 Author

**Shivkumar Biradar**

Computer Science Engineering Graduate

GitHub:
https://github.com/shivkumar-biradar

