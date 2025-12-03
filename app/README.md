# GradePilot: Advanced Analytics for Educational Performance Prediction

## Project Overview
GradePilot is an AI-powered web application designed to predict student performance in Mathematics and Portuguese courses. Using machine learning, it provides early identification of at-risk students, enabling educators to intervene before failure occurs. The system achieves 90.5% accuracy using a Random Forest model and a streamlined, user-friendly interface.

## Features
- Binary Pass/Fail prediction (≥10 = Pass, <10 = Fail)
- 17 essential input fields for student data
- Real-time prediction and risk assessment
- Actionable recommendations for improvement
- Interactive web dashboard (HTML/CSS/JS)
- FastAPI backend for ML inference
- Docker-ready deployment

## Folder Structure
```
app/
├── assets/           # Frontend files (index.html, style.css, script.js)
├── datasets/         # Source data (Maths.csv, Portuguese.csv)
├── models/           # Trained model files (rf_model.pkl, scaler.pkl, label_encoder.pkl)
├── server.py         # FastAPI backend
├── requirements.txt  # Python dependencies
├── Untitled.ipynb    # Jupyter notebook (ML pipeline)
```

## Installation & Usage
1. **Clone the repository**
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the app**:
   ```bash
   uvicorn server:app --reload
   ```
4. **Access the web interface**:
   Open `localhost:8000` in your browser

## Model Training
- See `Untitled.ipynb` for full data analysis, preprocessing, model training, and evaluation.
- The final Random Forest model is saved in `models/rf_model.pkl`.

## Deployment
- Dockerfile included for containerized deployment
- All static assets served from the `assets/` folder

## Dataset Source
This project uses the Student Performance dataset from Kaggle:
https://www.kaggle.com/datasets/whenamancodes/student-performance

## Team Members
- PATAJO, Odrei John C.
- DE LEON, Queenie A.
- NOVELOZO, Racell Jay C.
- MANAHAN, John Felix R.
- OCHOCO, John Patrick B.

## License
This project is released under the MIT License for all code and assets.
The dataset is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0) from Kaggle.
See LICENSE file for details.

## Contact
For questions or collaboration, please open an issue or discussion on the GitHub repository:
https://github.com/Bas1CUBER/Final-Project

Or email the leaeder at:
odreip@gmail.com
