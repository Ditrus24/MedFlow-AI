# 🏥 MedFlow AI

MedFlow AI is a smart clinical workflow platform that helps doctors document, analyze, and review patient data faster and more accurately using AI-assisted insights.

It reduces manual effort for senior doctors while helping junior residents learn through structured clinical remarks.

---

## 🚨 Problem Statement

In hospitals, doctors often face:
- Slow and messy manual documentation
- Loss of important clinical observations
- Poor coordination between senior doctors and junior residents
- Time pressure during diagnosis and follow-ups

These issues affect patient care and learning outcomes.

---

## 💡 Solution

MedFlow AI provides:
- A **structured bedside panel** for vitals and observations
- **Smart Remarks** powered by Gemini AI
- A **Remark & Learn** layer for junior residents
- Fast, clean, and role-based clinical workflow

---

## ✨ Key Features

- 📋 Bedside patient vitals dashboard  
- 🤖 AI-powered smart clinical remarks  
- 👨‍⚕️ Role-based views (Resident / Senior Doctor)  
- ⚡ Fast UI built with Vite + React  
- 🔐 Secure API handling via backend  
- 🚦 Rate-limited AI requests to prevent abuse  

---

## 🧠 How It Works

1. Doctor enters patient vitals and observations
2. Frontend sends request to secure backend API
3. Backend calls Gemini AI
4. AI returns structured clinical insights
5. Results are displayed instantly in the dashboard

---

## 🛡 Security & API Safety

- Gemini API key is **never exposed** on frontend
- All AI calls go through a backend API
- IP-based rate limiting is implemented
- Prevents excessive API usage and abuse

---

## 🧰 Tech Stack

- **Frontend:** React + TypeScript + Vite  
- **Backend:** Vercel Serverless Functions  
- **AI:** Google Gemini API  
- **Deployment:** Vercel  

---

## ⚙️ Environment Variables

Create a `.env.local` file (for local development):

```env
GEMINI_API_KEY=your_api_key_here
