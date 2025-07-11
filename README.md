# Responsible-AI-Framework-for-Healthcare-Diagnosis
#AI Medical Diagnosis System – Responsible AI Prototype

This project demonstrates a simple AI-powered **medical diagnosis system** built using Python and machine learning. It predicts possible medical conditions based on user-provided symptoms and outputs both a textual report and a visual image.

 **Disclaimer**: This tool is intended for educational purposes only and must not be used for real medical diagnosis or treatment decisions. Always consult a licensed healthcare professional.

---

 Project Overview

- **Input**: Patient symptoms (e.g., "fever, cough, fatigue")
- **Output**: Predicted medical diagnosis + confidence score
- **ML Model**: Naive Bayes Classifier using `scikit-learn`
- **Visualization**: Diagnosis report image generated with `PIL` (Pillow)
- **Reporting**: 
  - `diagnosis_report.txt`: Textual summary of results
  - `diagnosis_image.png`: Simple AI-generated visual summary
  - Canva-compatible data display for enhanced visualization

---
File Structure

| File                  | Description                                           |
|-----------------------|-------------------------------------------------------|
| `ai_diagnosis.py`     | Main script containing model training and prediction |
| `diagnosis_report.txt`| Auto-generated diagnosis summary report              |
| `diagnosis_image.png` | Visual diagnosis image generated with PIL            |

---

How It Works

1. **Data Preparation**:  
   A small sample dataset of symptoms and associated diagnoses is included for demonstration.

2. **Model Training**:  
   A text classification pipeline is created using `CountVectorizer` and `MultinomialNB`.

3. **User Input**:  
   Users enter symptoms via the command line (comma-separated format).

4. **Prediction**:  
   The trained model outputs the most likely diagnosis along with a confidence score.

5. **Reporting**:
   - A `.txt` file with the results is saved.
   - A PNG image report is generated and displayed.
   - Users are encouraged to use **Canva** to enhance visual presentations.

     GROUP MEMBERS
     Segai Bryton Mampshika
     Vhuvhwano Mawela Masalesa
     Mthunzi Malebadi
     Ondela Citywayo
     Sinesipho Sibulo

