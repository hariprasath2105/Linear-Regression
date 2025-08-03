
# 🎯 Student Score Predictor

A simple web application built with Python and Gradio that predicts a student's exam score based on the number of hours studied, using a **Linear Regression model**.

---

## 🧠 Overview

This project demonstrates how to use Linear Regression for predicting numerical outcomes. It takes input as **hours studied** and predicts the **score** using a pre-trained model (`model.pkl`) trained on a dataset of student scores.

---

## 📂 Project Structure

```
student-score-predictor/
│
├── model.py               # Script for training and saving the Linear Regression model
├── model.pkl              # Trained and serialized model
├── student_scores.csv     # Dataset used for training
├── requirements.txt       # Dependencies for the project
├── .gradio/               # Gradio app and config
└── README.md              # Project documentation
```

---

## 🧪 Dataset

**File**: `student_scores.csv`

**Features**:
- `Hours`: Number of hours studied
- `Scores`: Marks obtained

---

## 🚀 Features

- Input number of study hours and get predicted exam scores.
- Built using Python, scikit-learn, and Gradio.
- Trained using simple Linear Regression.
- Lightweight and easy to deploy.

---

## 🛠 Tech Stack

| Technology     | Use                  |
|----------------|----------------------|
| Python         | Core language        |
| scikit-learn   | Machine Learning     |
| Pandas         | Data manipulation    |
| NumPy          | Numeric operations   |
| Gradio         | Web-based UI         |

---

## 🛠 Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/hariprasath2105/Linear-Regression.git
cd Linear-Regression
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Train the Model (if needed)
```bash
python model.py
```

---

## 💡 Usage

Once everything is set up, run the Gradio interface:

```bash
python model.py
```

A browser window will open with the UI where you can enter study hours and get score predictions.

---

## 📸 Screenshots

### 📥 Input UI
![Student Score Predictor - Input](./screenshots/input_ui.png)

### 📈 Output Prediction
![Student Score Predictor - Output](./screenshots/output_ui.png)

> Place your screenshots in a `screenshots/` folder and name them `input_ui.png` and `output_ui.png`.

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🙋‍♂️ Author

**Hari Prasath S**  
[GitHub Profile](https://github.com/hariprasath2105)

---
