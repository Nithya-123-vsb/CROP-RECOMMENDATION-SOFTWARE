# 🌱 GreenGuide: Crop Recommendation System

GreenGuide is a machine learning-based web application that recommends the most suitable crop to plant based on soil composition and environmental factors. It uses a **Decision Tree Classifier** model trained on agricultural data to provide predictions.

## 🚀 Features

- **Soil Parameters Analysis**: Recommends crops based on Nitrogen (N), Phosphorus (P), Potassium (K), pH, and rainfall.
- **Environmental Parameters**: Takes Temperature and Humidity into account.
- **Simple Web Interface**: Powered by Flask for quick inputs and immediate recommendations.
- **CLI Tool**: A command-line script (`test.py`) for console-based predictions.

---

## 🛠️ Installation & Setup

Follow these steps to run the application locally on your machine.

### 1. Clone the Repository
```bash
git clone https://github.com/Nithya-123-vsb/GreenGuide.git
cd GreenGuide
```

### 2. Set Up a Virtual Environment (Optional but Recommended)
On Windows:
```powershell
python -m venv .venv
.venv\Scripts\activate
```
On macOS/Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
Install the required packages using pip:
```bash
pip install -r requirements.txt
```

---

## 💻 Running the Application

### Web Interface (Flask App)
To start the Flask development server:
```bash
python app.py
```

Once running, the application will be accessible locally. You can open your browser and navigate to:
👉 **[http://localhost:5000/](http://localhost:5000/)** (or **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)**)

### Command Line Interface
To run the CLI test script:
```bash
python test.py
```

---

## 📂 Project Structure
```text
GreenGuide/
│
├── templates/
│   └── index.html             # Web frontend input form
├── Crop_recommendation.csv    # Training dataset
├── app.py                     # Flask web server & model prediction
├── test.py                    # CLI prediction script
├── requirements.txt           # Python package dependencies
├── .gitignore                 # Files excluded from git tracking
└── README.md                  # Project documentation (this file)
```
