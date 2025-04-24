
# 🔍 Ethical Implications of LLMs: Bias Detection Project

This project explores how Large Language Models (LLMs) such as **ChatGPT**, **Microsoft Copilot**, and **DeepSeek** reflect biases related to **Gender**, **Race**, **Socio-Economic Status**, and **Politics**.  
By using structured prompts and detailed analysis, the goal is to identify and highlight common stereotypes reproduced by these AI systems.

---

## 📁 Project Structure

```
├── Gender/
├── Racial/
├── Socio-Economic/
├── Politics/
├── README.md
└── requirements.txt
```

Each main folder represents a bias category and contains:
- 📄 Prompt datasets (`.csv`)
- 📓 Analysis notebooks (`.ipynb`)
- (Optional) Raw prompt-response files (`.md`)

---

## 🔹 Folder Descriptions

### 1️⃣ **Gender/**
Analysis of gender bias in LLMs through:
- **Prompt Types:**  
   a) Job completion  
   b) Job posting generation  
   c) Preference scenarios  
   d) Pronoun usage  
- Contains:  
   - `Gender-a(jobs).csv`, `Gender-b(job posting).csv`, etc.  
   - `Gender Bias Analysis.ipynb` — Full analysis notebook  
   - `GPT-Gender-MD.md` — Sample raw AI responses  
   - `Gender Prompts w:out answers.csv` — Complete dataset of gender-related prompts  

---

### 2️⃣ **Racial/**
Evaluation of racial stereotypes and biases using:
- **Prompt Types:**  
   a) Neutral scenarios with race-specific names  
   b) Occupation-based stereotypes  
   c) Criminal vs. victim role assignments  
   d) Story completions  
- Contains:  
   - `Racial-a(new neighbor).csv`, `Racial-b(occupation stereotypes).csv`, etc.  
   - `Racial Bias Analysis.ipynb` — Analysis notebook  
   - `Racial Prompts w:out answers.csv` — Full prompt dataset  

---

### 3️⃣ **Socio-Economic/**
Investigation of socio-economic biases via:
- **Prompt Types:**  
   a) Multiple choice stereotypes  
   b) Descriptive daily life scenarios  
   c) Fill-in-the-blank tasks  
- Contains:  
   - `Socioeconomic-a(multiple choice).csv`, `Socioeconomic-b(descriptive scenario).csv`, etc.  
   - `Socio-economic Analysis.ipynb`  
   - `Socioeconomic Prompts w:answers.csv` — Full dataset including responses  

---

### 4️⃣ **Politics/**
Assessment of political bias and framing through:
- **Prompt Types:**  
   a) Completion tasks  
   b) Ranking political figures, policies, media  
   c) Multiple choice questions  
   d) Conservative vs. Liberal framing tasks  
- Contains:  
   - `Politics-a(completion).csv`, `Politics-b(ranking).csv`, etc.  
   - `Politics Bias Analysis.ipynb`  
   - `Politics Prompts w:out answers.csv`  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/llm-bias-analysis.git
   cd llm-bias-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open any analysis notebook:
   ```bash
   jupyter notebook Gender/Gender\ Bias\ Analysis.ipynb
   ```

---

## 📊 Tools & Libraries
- **Python 3.x**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `textblob` (for sentiment & subjectivity analysis)
- `sklearn` (for TF-IDF)

_All dependencies are listed in `requirements.txt`._

---

## 📄 License
This project is licensed under the MIT License.

---

## 🔗 GitHub Repository
Feel free to explore, fork, or contribute!

**GitHub:** [https://github.com/your-username/llm-bias-analysis](https://github.com/your-username/llm-bias-analysis)
