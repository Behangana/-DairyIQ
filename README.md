# 🐄 DairyIQ – Milk Quality Prediction System

**DairyIQ** is a machine learning-powered web application that predicts the quality of milk based on chemical and physical properties such as pH, temperature, fat content, conductivity, and density.

Developed using:

- 🧠 scikit-learn for machine learning
- 🔥 Flask for the web backend
- 🎨 HTML/CSS for the frontend
- 📒 Jupyter Notebook for model prototyping

---

## 🚀 Features

- ✅ Predicts **High** or **Low** milk quality
- 🧪 Interactive web form for input
- 📈 Built-in machine learning model (`RandomForestClassifier`)
- 🧠 Model saved and reused via `joblib`
- 💻 Easy to run locally

---

## 🛠️ Technologies Used

| Tool/Library     | Purpose                     |
| ---------------- | --------------------------- |
| Python 3.10+     | Core language               |
| scikit-learn     | Model training & evaluation |
| pandas / numpy   | Data manipulation           |
| Flask            | Web framework               |
| Jupyter Notebook | Model prototyping           |
| HTML/CSS         | Frontend UI                 |

---

## 📦 Project Structure

```
dairyiq/
├── app/
│   ├── static/
│   ├── templates/
│   │   └── index.html
│   └── main.py
├── data/
│   └── mock_milk_quality.csv
├── ml_model/
│   └── dairy_model.pkl
├── notebooks/
│   └── milk_quality_model.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📒 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/DairyIQ.git
cd DairyIQ

# 2. Set up virtual environment
python -m venv venv
venv\Scripts\activate    # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app/main.py
```

Then open your browser at:  
🔗 http://127.0.0.1:5000

---

## ✅ To Do / Future Improvements

- [ ] Add confidence score or visual gauge
- [ ] Log user inputs and predictions
- [ ] Deploy on Render or PythonAnywhere
- [ ] Add charts/graphs to report trends
- [ ] PDF export of prediction reports

---

## 🧑‍💼 Author

Developed by **[@Behangana](https://github.com/Behangana)**  
For inquiries: `emmanuelbeha@gmail.com`
