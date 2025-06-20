# 🌟 AI Career Coach

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Gradio](https://img.shields.io/badge/Gradio-5.12.0-orange.svg)
![IBM watsonx.ai](https://img.shields.io/badge/IBM-watsonx.ai-blue)

---

<p align="center">
  <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=800&q=80" width="60%" alt="AI Career Coach Banner"/>
</p>

---

## 👋 Welcome!

Hi, I'm Garbii, and this is my personal project: **AI Career Coach**. It's a suite of AI-powered tools designed to help you polish your resume, generate personalized cover letters, and get strategic career advice—all powered by IBM's watsonx.ai Large Language Models.

> "I built this project to help job seekers (like myself!) stand out in today's competitive job market."

---

## 🚀 Project Overview

**AI Career Coach** is your all-in-one assistant for job applications. It features:

- **AI-driven Resume Enhancer:** Analyze and improve your resume for specific job descriptions.
- **Personalized Cover Letter Generator:** Draft custom cover letters that make your application shine.
- **Strategic Job Hunting Advisor:** Get tailored career advice by comparing your resume to target job roles.

This project is both a learning journey and a practical toolkit for anyone looking to bridge the gap between talent and opportunity using AI.

---

## 🎯 Learning Objectives

By building and using this project, you will:

- ✅ Learn to use Gradio for interactive AI web apps
- ✅ Integrate IBM watsonx.ai's language models
- ✅ Develop a resume enhancement tool
- ✅ Create a personalized cover letter generator
- ✅ Build a career advice application
- ✅ Apply AI to solve real-world career development problems

---

## 🛠️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Garbii1/AI-Career-Coach.git
   cd AI-Career-Coach
   ```

2. **Create a Virtual Environment**
   ```bash
   pip install virtualenv
   virtualenv my_env
   # On Windows:
   .\my_env\Scripts\activate
   # On macOS/Linux:
   source my_env/bin/activate
   ```

3. **Install Dependencies**
   ```bash
   pip install gradio==5.12.0 ibm_watsonx_ai==1.1.20 email-validator==2.1.1 numpy==1.26.4 pandas==2.1.4
   ```

---

## 🚦 Quick Start

Try out the demo apps:

### 1. Gradio Sum Calculator
A simple web app that adds two numbers (see `gradio_demo.py`).
```bash
python gradio_demo.py
```

### 2. Watsonx.ai Q&A Bot
A chatbot using watsonx.ai's Llama-3 model (see `llm_chat.py`).
```bash
python llm_chat.py
```

---

## 🤖 Core Applications

Each tool runs as a standalone Gradio web app:

### 1. Resume Polisher (`resume_polisher.py`)
Polish your resume for a specific job.
```bash
python resume_polisher.py
```

### 2. Cover Letter Generator (`cover_letter.py`)
Generate a tailored cover letter.
```bash
python cover_letter.py
```

### 3. Career Advisor (`career_advisor.py`)
Get strategic advice to improve your resume and skills.
```bash
python career_advisor.py
```

---

## 💡 Customization & Tips

- **Longer Responses:** Increase `max_tokens` in `TextChatParameters` for more detailed output.
- **Control Randomness:** Adjust `temperature` for more creative or deterministic responses.
- **Modify Prompts:** Tweak the prompts in the Python files to personalize the AI's advice.
- **Change Gradio Inputs:** Try new input types for a better user experience.

---

## 🙏 Acknowledgements

- [IBM watsonx.ai](https://www.ibm.com/products/watsonx-ai)
- [Gradio](https://gradio.app/)
- [Unsplash](https://unsplash.com/) for banner images

---

<p align="center">
  <b>Made with ❤️ by Garbii</b>
</p>