# AI Smart Nutrition Analyzer

## Overview

AI Smart Nutrition Analyzer is a deep learning-based web application that classifies fruits and vegetables from uploaded images and displays their estimated calorie information per 100 grams.

The application is built using TensorFlow/Keras for image classification, Streamlit for the user interface, and Flask for providing a REST API.

---

## Features

- Classifies 36 different fruits and vegetables
- Deep learning model built using TensorFlow and Keras
- User-friendly Streamlit interface
- Displays estimated calories per 100 grams
- REST API using Flask
- Image upload support
- Fast image prediction

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Streamlit
- Flask
- NumPy
- Pillow

---

## Project Structure

```
AI_Smart_Nutrition_Analyzer/
│
├── App.py
├── ec2_api.py
├── Fruits_Vegetable_Classification.py
├── Fruit_Veg_Classification_Mobilenet.ipynb
├── FV.h5
├── requirements.txt
├── README.md
├── .gitignore
└── upload_images/
```

---

## Supported Classes

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
- Sweet Corn
- Sweet Potato
- Tomato
- Turnip
- Watermelon

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/AI_Smart_Nutrition_Analyzer.git
```

Move into the project folder

```bash
cd AI_Smart_Nutrition_Analyzer
```

Install the required packages

```bash
pip install -r requirements.txt
```

---

## Running the Streamlit Application

```bash
streamlit run App.py
```

---

## Running the Flask API

```bash
python ec2_api.py
```

---

## Model

The project uses a trained TensorFlow/Keras model (`FV.h5`) to classify fruit and vegetable images.

Input image size:

```
224 × 224 pixels
```

Total classes:

```
36
```

---

## Future Improvements

- Nutritional information beyond calories
- Confidence score for predictions
- Mobile responsive interface
- Food quantity estimation
- Barcode scanning
- Multi-object detection

---

## Author

Shivkumar Biradar

Computer Science and Engineering