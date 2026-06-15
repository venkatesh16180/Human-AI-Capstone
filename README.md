# Process Analytics of Human-AI Collaboration
**Capstone Project | University of Arizona | MS Information Sciences**
Mentored by [Xiao Hu, Associate Professor](https://infosci.arizona.edu/person/xiao-hu), University of Arizona

---

## 📌 Overview
An exploratory research project applying advanced **process mining techniques** to an anonymized dataset of 47 students' essay-writing interactions with AI. The goal was to uncover and compare human-AI interaction patterns in an educational setting — an area with limited empirical research — and translate findings into actionable recommendations for organizations building AI tools for education.

This project was presented as a research poster at **IShowcase 2025**, University of Arizona, to an audience of 300+ graduate, PhD, and industry attendees.

---

## 🔍 Research Questions
- What types of AI assistance do students rely on during essay writing?
- What are the most common action sequences students take when collaborating with AI?
- What behavioral patterns and anomalies emerge from the interaction data?

---

## 📊 Dataset
- **Source:** Anonymized trace data from a foreign educational institution
- **Size:** 20,000+ interaction events across 47 student participants
- **Contents:** Two datasets — Essay logs and Trace logs with 23 features including user actions, timestamps, AI prompts, and response types

> ⚠️ The dataset is anonymized and not included in this repository to protect participant privacy. Sample files are provided for reference.

---

## 🔑 Key Findings
- **80%** of all AI assistance occurred via the `Ask_GPT` function — students overwhelmingly relied on conversational AI over dictionary-style tools
- Most common student action sequence identified:
  `START_TASK → RELEVANT READING → OPEN_ESSAY → OPEN_GPT → READ_FEEDBACK_GPT → WRITE_ESSAY → SAVE_ESSAY`
- Top 3 most frequent actions: `RELEVANT READING`, `WRITE_ESSAY`, `READ_FEEDBACK_GPT`
- Only **1 out of 47 students** (2%) expressed gratitude to ChatGPT — highlighting a unique dimension of human-AI social dynamics
- ChatGPT was used for translation, grammar checking, brainstorming, and inspiration — not just direct answers

---

## 💡 Recommendations for AI Tool Developers
Based on findings, organizations building AI tools for educational settings should prioritize:
1. **Grammar checking** features integrated into the writing workflow
2. **Brainstorming assistance** tools that guide without completing tasks
3. **Synonym and dictionary** tools for multilingual learners
4. **Feedback loop** mechanisms to improve student-AI engagement

---

## 🛠️ Tools & Technologies
| Category | Tools |
|---|---|
| Language | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, NetworkX |
| Process Mining | Transition graphs, directed network graphs, transition matrices |
| Environment | Jupyter Notebook, Google Colab |
| Version Control | GitHub |

---

## 📁 Repository Structure
```
Human-AI-Capstone/
│
├── Capstone.ipynb              # Main analysis notebook
├── Capstone_Report.docx        # Full written research report
├── Poster_refined_v2.pptx      # IShowcase research poster
└── README.md
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/venkatesh16180/Human-AI-Capstone.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn networkx openpyxl
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Capstone.ipynb
   ```
> Note: The full dataset is not included. Sample files (`essayLog (sample).xlsx` and `trace_data (sample).xlsx`) are provided to demonstrate the data structure.

---

## 📄 Research Poster
Presented at **IShowcase 2025**, University of Arizona — an event featuring 300+ graduate students, PhD candidates, and industry professionals from technical and non-technical backgrounds.

---

## 👤 Author
**Venkateshwara Chowdary Tallapaneni**
MS Information Sciences (Machine Learning) | University of Arizona
[LinkedIn](https://www.linkedin.com/in/your-linkedin) | [GitHub](https://github.com/venkatesh16180)
