
# 📄 ResumeMatchAI

**AI-powered Resume vs Job Description Matcher with ATS Insights**

ResumeMatchAI is a Generative AI-powered application that helps job seekers analyze how well their resume matches a specific job description. It calculates a match percentage, identifies missing or weak keywords, and provides suggestions for optimization — all with an ATS (Applicant Tracking System) perspective.

---

## 🚀 Features

- ✅ **Resume vs JD Matching** – Upload a resume and paste a job description to get a match percentage.
- 🧠 **Missing Keywords Detection** – Find important terms in the JD not present in the resume.
- 📊 **ATS-style Scoring** – Simulates how applicant tracking systems assess your resume.
- ✨ **Generative AI Suggestions** – Uses Google's Gemini API to provide personalized tips and improvements.
- 💡 **Streamlit UI** – Simple and interactive web interface.

---

## 📁 Project Structure

```

.
├── sql.py                  # Main Streamlit app
├── resume\_parser.py        # (Optional) PDF parsing and keyword extraction logic
├── requirements.txt        # Python dependencies
├── .env                    # Environment variables (e.g., API keys)
└── README.md

````

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/resume-match-ai.git
cd resume-match-ai
````

### 2. Create a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory and add your [Google Gemini API key](https://ai.google.dev/gemini-api/docs/quickstart):

```env
GOOGLE_API_KEY=your_api_key_here
```

### 5. Run the App

```bash
streamlit run sql.py
```

---

## 🧪 Sample Output

* **Match %**: 78%
* **Missing Keywords**: "TensorFlow", "data pipelines", "A/B testing"
* **AI Suggestion**: "Consider highlighting experience with model deployment and data engineering tools."

---

## 📌 To-Do

* [ ] Add support for multiple JD uploads
* [ ] Generate resume summary paragraph using GenAI
* [ ] Export ATS report as PDF
* [ ] Improve keyword ranking logic

---

## 🤖 Powered By

* [Google Generative AI (Gemini)](https://ai.google.dev/)
* [Streamlit](https://streamlit.io/)
* Python, SQLite

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Contributing

PRs are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

---

## 👤 Author

**Shivam Singla**
[LinkedIn]([https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/shivam-singla-02b726345/)) • 

```

---

Let me know if you'd like me to generate the `requirements.txt` too or add badges (like Streamlit, license, Python version, etc.)!
```
