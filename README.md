# 🎥 ViText – Multimodal Video Answer Evaluation System

ViText is an AI-powered system that evaluates **student video answers** by analyzing speech and comparing it with a reference answer.
The goal is to automate the evaluation process and provide objective feedback.

---

## 📌 Problem Statement

In online learning and interviews, students often submit **video answers**.
Manually evaluating these videos is:

* Time-consuming
* Subjective
* Difficult to scale

---

## 💡 Solution

ViText solves this problem by using AI models to:

1. Extract speech from the uploaded video
2. Convert speech to text
3. Compare the student's answer with an expert reference answer
4. Calculate semantic similarity
5. Check for important keywords
6. Generate evaluation results

---

## ⚙️ Project Pipeline

Video Upload
⬇
Audio Extraction
⬇
Speech-to-Text Transcription
⬇
Semantic Similarity Analysis
⬇
Keyword Matching
⬇
Evaluation Output

---

## 🧠 Technologies & Libraries Used

* Python
* Gradio (Web Interface)
* Whisper (Speech Recognition)
* Sentence Transformers (Semantic Similarity)
* MoviePy (Video Processing)
* PyTorch (Deep Learning Framework)

---

## 📂 Project Structure

```
vitext-project
│
├── app.py              # Gradio UI
├── pipeline.py         # Main evaluation logic
├── utils.py            # Helper functions
├── style.css           # UI styling
├── requirements.txt    # Project dependencies
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/vitext-project.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the application

```
python app.py
```

4. Open the local Gradio interface and upload a video answer.

---

## 📊 Output

The system provides:

* Video transcription
* Semantic similarity score
* Keyword coverage
* Missing important keyword

---

## 🔮 Future Improvements

* Real-time evaluation
* Visual gesture analysis
* Emotion and confidence detection
* Integration with online learning platforms

---

## 📚 Use Cases

* Online learning platforms
* AI-based interview evaluation
* Student assessment systems
* Educational technology tools

---

## 👩‍💻 Author

Developed as an AI-based academic project for hackthon.

---
