# 🥗 NutriDoc – AI-Powered Nutritionist

NutriDoc is a Generative AI-powered nutrition analysis web application built with **Python, Streamlit, and Google Gemini**.

The application analyzes uploaded food images, estimates calories, provides nutritional insights, and generates personalized dietary recommendations based on the user's profile, BMI, health issues, and dietary preferences.

---

## 🚀 Features

### 📸 Food Image Analysis
Upload an image of a food item and use Generative AI to identify the food and estimate its calorie content.

### 🔢 Calorie Estimation
Provides an approximate calorie estimation for the identified food and serving size.

### 🥦 Nutritional Analysis
Generates information about:
- Carbohydrates
- Protein
- Fats
- Sodium and sugars
- Vitamins and minerals

### 👤 Personalized Recommendations
Recommendations are generated using information such as:
- Dietary preference
- BMI
- Health-related inputs
- User profile

### 🍎 Healthier Alternatives
Suggests ways to improve the nutritional quality of a meal and provides healthier alternatives where applicable.

### 💬 AI-Generated Insights
Generates personalized nutrition-related advice and additional food insights using Generative AI.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Google Gemini API**
- **Generative AI**
- **Matplotlib**
- **Pytesseract**
- **Pillow**
- **python-dotenv**

---

## 🏗️ Project Structure

```text
NutriDoc/
│
├── app.py
├── requirements.txt
├── packages.txt
├── README.md
├── .gitignore
│
├── .streamlit/
│   └── config.toml
│
└── pages/