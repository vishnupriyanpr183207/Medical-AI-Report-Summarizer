# 🧠 Medical AI Report Summarizer

**Medical AI Report Summarizer** is a smart web application that allows users to upload medical reports (PDF, JPG, PNG), automatically extract text, highlight medical terms, and generate an AI-based summary. Users can also export the final summary as a clean PDF. This project is designed to assist patients and doctors in quickly understanding lengthy medical documents.

---

## 🚀 Features

- 📂 **Upload Reports** – Accepts PDF, JPG, PNG files
- 🔍 **Text Extraction** – Uses OCR (`pytesseract`) and `pdfplumber` for accurate text retrieval
- 🩺 **Medical Term Highlighting** – Detects and highlights important medical terms in sky blue
- 🤖 **AI Summary Generation** – Uses HuggingFace’s `facebook/bart-large-cnn` for natural language summarization
- 📤 **Export to PDF** – Summaries can be downloaded in a clean, structured PDF format
- 🌐 **Interactive UI** – Stylish, responsive frontend with drag-and-drop support

---

## 🧪 Tech Stack

| Layer      | Tools Used |
|------------|------------|
| 💻 Frontend | HTML, CSS, JavaScript |
| 🧠 AI / NLP | spaCy, sciSpacy |
| 🖼️ OCR / Parsing | `pytesseract`, `pdfplumber`, `Pillow` |
| 🐍 Backend | Python (Flask) |
| 📄 PDF Generation | `reportlab` |

---

## 🛠️ Setup Instructions

### 📦 Requirements

- Python 3.8+
- `pip install -r requirements.txt`

### ▶️ To Run Locally

```bash
git clone https://github.com/your-username/ai-report-summarizer.git
cd ai-report-summarizer
pip install -r requirements.txt
python app.py
```

Then open your browser and go to:  
👉 `http://localhost:5000`

---

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/8868f0ca-7276-4341-8e1f-9afcdb96308b" alt="Screenshot 1" width="600"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c39844f7-8d34-4243-b6cc-fc92418f7e50" alt="Screenshot 2" width="600"/>
</p>
---

## 🧑‍🤝‍🧑 Team Members & Contributions

- 👨‍💻 **Vivek K K**
  - Project Lead, Full-Stack Integration, OCR & PDF Parser Logic  
  - Implemented UI logic, patient ID management, CSV preview, export to PDF  
  - Ensured overall workflow between image uploads, AI summarization, and UI behavior

- 🤖 **Vishnupriyan**  
  - Built the core **AI-based ECG and Report Summary Generator**  
  - Trained and integrated HuggingFace summarization models  
  - Tuned and optimized model outputs for better clinical relevance

- 🎨 **Akshaya**  
  - UI/UX Designer  
  - Designed modern, user-friendly frontend layout using Figma  
  - Styled summary output pages, buttons, and cloud upload animations

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 💬 Feedback

Have suggestions or facing issues?  
Feel free to open an issue or connect with us!

