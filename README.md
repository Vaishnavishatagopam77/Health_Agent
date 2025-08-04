# Health_Agent

# 🧠 Agentic AI Health Symptom Checker

An AI-powered assistant that helps users understand potential health conditions based on symptom inputs. It offers preliminary insights, urgency levels, home remedies, and when to consult a doctor — powered by NLP and deployed on IBM Cloud using IBM Granite.

---

## 🚀 Problem Statement (No. 28)

Millions face delays in accessing accurate medical information. This project aims to bridge that gap with an agentic AI health assistant that:
- Accepts natural language symptoms like “I have a sore throat and fever.”
- Returns possible conditions, urgency levels, and remedies.
- Uses verified health data from WHO, government portals, and medical journals.
- Supports multilingual interaction.
- Avoids self-diagnosis by offering referral-based guidance.

---

## 🧩 Features

- ✅ Natural language symptom input
- ✅ AI-based condition prediction
- ✅ Triage: Self-care / Doctor visit / Emergency
- ✅ Preventive health suggestions
- ✅ Multilingual support
- ✅ Web-based responsive UI

---

## 🛠️ Technology Stack

| Component     | Tech Used                          |
|--------------|-------------------------------------|
| Backend       | Python, Flask                      |
| NLP Engine    | IBM Watson NLU, spaCy              |
| ML Models     | Logistic Regression, BERT          |
| Frontend      | HTML, CSS, React                   |
| Deployment    | IBM Cloud Lite,                    |
| Database      |  IBM Cloudant                      |

---

## 🔁 Architecture Overview

1. **Input Layer**: User inputs symptoms via web UI.
2. **NLP Layer**: IBM Watson or spaCy parses input.
3. **Prediction Layer**: ML models predict possible conditions.
4. **Triage Engine**: Classifies into urgency levels.
5. **Response Layer**: Sends preventive advice and next steps.

---

## 📸 Screenshots

> _(Add UI screenshots here in the `/screenshots/` folder if available)_

---

## 🧪 Setup Instructions

```bash
# Clone this repository
git clone https://github.com/yourusername/agentic-ai-health-symptom-checker.git
cd agentic-ai-health-symptom-checker
```
# Create a virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py

Screen shots...

<img width="1915" height="1053" alt="Screenshot 2025-08-04 105724" src="https://github.com/user-attachments/assets/3ad7b3a2-4766-49d5-97b5-6b3fe2960866" />

<img width="816" height="433" alt="Screenshot 2025-08-04 093248" src="https://github.com/user-attachments/assets/604571f5-c7af-43f3-8d0f-abf16db304a4" />

<img width="785" height="474" alt="Screenshot 2025-08-04 093215" src="https://github.com/user-attachments/assets/8301b744-387e-477d-83ec-5d90ccd0ab8f" />

<img width="923" height="558" alt="Screenshot 2025-08-04 093116" src="https://github.com/user-attachments/assets/b1f0fe7b-4236-41ac-8468-f09fcf401c23" />
