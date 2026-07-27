# AI UVAS Admission Guide

An intelligent, easy-to-use web app that helps students get **instant, accurate answers** about UVAS (University of Veterinary and Animal Sciences) Lahore admissions — without digging through the official website.

**🌐 Live App:** [https://your-vercel-url.vercel.app]([https://your-vercel-url.vercel.app](https://ai-uvas-admission-guide.vercel.app))

---

## 🎯 The Problem It Solves

Every year, thousands of prospective students face the same confusion:
- Which programs am I eligible for?
- What documents are required?
- How do I apply, and what is the deadline?
- Which campus offers a particular degree?

Misinformation spreads quickly, and the official website can be overwhelming.  
This app centralises **verified UVAS admission information** and lets students ask questions in plain English, receiving reliable answers immediately.

**Target users:** Prospective undergraduate and postgraduate UVAS students, and their parents.

---

## ✨ Features

- **💬 AI Admission Chat** – Ask any admission-related question; the AI answers only from official UVAS data.
- **📋 Program Finder** – Search or browse programmes by name, campus, or eligibility.
- **✅ Eligibility Checker** – Quickly see which programmes match your academic background.
- **📄 Document Checklist** – A tickable list of all required admission documents.
- **📅 Admission Timeline** – A visual step‑by‑step guide of the application process.
- **❓ FAQ Page** – Common questions with expandable answers.
- **🔗 Official Links** – Direct access to the UVAS admission portal and important pages.
- **📱 Fully Responsive** – Works beautifully on mobile, tablet, and desktop.

---

## 🤖 AI Feature

The AI assistant is powered by **GPT‑4o** and follows a strict system prompt. It **only** answers using the official UVAS admission data provided in the `uvas_admission_data.txt` file. If the answer is missing, it refuses to guess.

**System Prompt / Instructions:**
> You are an AI assistant for UVAS admissions. Only use the provided UVAS admission information to answer questions. Be clear and concise. If the answer is not in the provided data, say: "I'm sorry, I don't have that information. Please visit the official UVAS website." Never guess or answer unrelated questions.

The AI also politely declines any non‑admission questions (jokes, coding, general knowledge) by redirecting:  
*"I can only help with UVAS admission questions."*

**AI Model:** GPT‑4o  
**Knowledge Source:** Manually curated from official UVAS admission pages into `uvas_admission_data.txt`

---

## 🛠️ Tools & Services Used

- **Frontend:** React + Tailwind CSS
- **AI Model:** GPT‑4o (integrated via Bolt.new)
- **Development Platform:** [Bolt.new](https://bolt.new) – AI‑powered app builder
- **Version Control:** Git & GitHub
- **Deployment:** [Vercel](https://vercel.com)

---

## 📸 Screenshots

*(Take clear screenshots of your app and upload them to your GitHub repository, then link them here. Use relative links if the images are in the repo.)*

1. **Homepage** – Hero section and navigation  
   ![Homepage](./screenshots/homepage.png)

2. **AI Chat** – Asking about eligibility  
   ![Chatbot](./screenshots/chat.png)

3. **Program Finder** – Searching for programmes  
   ![Program Finder](./screenshots/programs.png)

> 💡 Tip: Create a `screenshots` folder in your repo, upload your images there, and use the path as shown.

---

## 🧑‍💻 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/ai-uvas-admission-guide.git
   cd ai-uvas-admission-guide
   
