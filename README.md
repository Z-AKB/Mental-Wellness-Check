# Mental Wellness Check

## Objective
Assess stress, anxiety, and depression

## Possible Computational Techniques
1. Scoring system
2. Threshold classification

## Flask UI Component
1. Radio button inputs
2. wellness score output

## Types of Dataset
1. Psychological assessment scales
2. mental health indicators

## Possible Sources for Dataset
1. Psychology research papers
2. mental health organizations

## Dataset URLs
1. https://openpsychologydata.metajnl.com/
2. https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey

## Setup Instructions
13. Mental Wellness Check
1. Create Flask app with radio buttons for assessment questions
2. Implement scoring systems from clinical scales
3. Design threshold classification
4. Build question and scoring database
5. Implement privacy and data handling
6. Generate wellness scores and interpretations
7. Suggest self-care routines
8. Visualise wellness across dimensions
9. Test with clinical cases






**##Group 13**

Ugochukwu Adaugo Queeneth VUG/SEN/23/10415
Akanbi Oluwafifunmi Zion VUG/SEN/22/7238
Marshall Aaron VUG/SEN/22/8506

# 🧠 Mental Wellness Check

A Flask-based expert system that assesses mental wellness using inputs like stress levels, sleep patterns, and mood. The system provides personalized recommendations using rule-based logic inspired by psychological assessment scales (PHQ-9, GAD-7, etc.).

---

## 🚀 Features
- Web-based mental wellness questionnaire
- Expert rules for stress, mood, and sleep analysis
- Dynamic feedback and self-care suggestions
- Clean Bootstrap-based UI (no custom CSS)

---

## 📁 Project Structure
```
mental_wellness_app/
├── app/
│   ├── __init__.py        # App factory
│   ├── routes.py          # Flask routes
│   ├── logic.py           # Expert system logic
│   ├── templates/
│   │   ├── base.html      # Base layout
│   │   └── index.html     # Wellness form + results
│   └── static/            # Static assets (currently empty)
├── config.py              # Environment configs
├── main.py                # App runner
├── requirements.txt       # Dependencies
├── .env                   # Secret keys (not tracked)
└── README.md              # Project documentation
```

---

## 🛠️ Setup Instructions

1. **Clone the repo**
```bash
git clone https://github.com/yourusername/mental-wellness-app.git
cd mental-wellness-app
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Add `.env` file**
```env
SECRET_KEY=your-secret-key
```

5. **Run the app**
```bash
python main.py
```

6. **Open in browser**
```
http://localhost:5000
```

---

## 🧠 Example Questions
- Stress Level (0-10)
- Sleep Hours (per night)
- Mood Score (0-10)

---

## 📝 Future Enhancements
- Add PHQ-9 / GAD-7 complete scales
- Track user scores over time
- Visualize mental wellness trends
- Add authentication for secure logins
- Export reports or send email summaries

---

## 📚 Data Sources & References
- [PHQ-9](https://www.phqscreeners.com/)
- [GAD-7](https://adaa.org/)
- [Open Psychology Data](https://openpsychologydata.metajnl.com/)
- [OSMI Mental Health Dataset](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)

---

## 📄 License
MIT License
```
