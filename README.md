# 🎵 Music Classifier – AI-based Song Recommendation Tool

This project is a GUI-based **AI music classification system** built with **Python**. It uses **Decision Tree** and **Neural Network (MLPClassifier)** models to predict whether a user would **like a song** based on various attributes like artist, genre, year, gender, and age.

The app provides:
- Model performance metrics (accuracy, recall, precision)
- List of songs the user may like
- GUI-based user input testing
- Visual feedback via a styled Tkinter interface

---

## 🚀 Features

- 🎧 Classify music preferences using:
  - Decision Tree Classifier
  - Multi-Layer Perceptron (Neural Network)
- 📊 Performance metrics displayed in GUI:
  - Accuracy
  - Recall
  - Precision
- 🧠 Interactive predictions based on manual user input
- 📋 Displays songs the user is predicted to like
- 🖼 Background image & styled GUI layout using Tkinter
- 💡 Categorical data encoding via one-hot and label encoders

---

## 🛠 Tech Stack

- Python 3
- `pandas`, `numpy`, `scikit-learn`
- `tkinter`, `Pillow` for GUI and image display
- Models: `DecisionTreeClassifier`, `MLPClassifier` (Neural Network)

---

## 🖥 GUI Screenshots

> _(Add your screenshots here)_  
Example:
- Main interface
- User input window
- Accuracy and song output display

---

## 📁 Files Included

- `music_classifier.py`: Main GUI application file
- `Training-data.csv`: Training dataset for both models
- `music.jpg`: Background image used in the app
- `README.md`: Project overview and instructions

---

## 📊 How It Works

### Input Features:
- Artist name
- Song title
- Genre (Type)
- Release year
- Listener gender
- Listener age group (20s, 30s, 40s–50s)

### Output:
- **Liked Song?** (`Yes` or `No`)
- Predicted list of songs user would like

### Models:
- **Decision Tree**: Handles one-hot encoded input
- **Neural Network (MLPClassifier)**: Uses label-encoded input

---

## 📦 Requirements

Install dependencies:

```bash
pip install pandas numpy scikit-learn pillow

▶️ How to Run
bash
Copy
Edit
python music_classifier.py

🔍 Future Enhancements
Export predictions

Add more genres

Use a larger and more diverse dataset

Deploy as a web app using Flask or Streamlit

