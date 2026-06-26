---
title: TalentRadar API
emoji: 🚀
colorFrom: blue
colorTo: green
sdk: docker
pinned: false
---
<div align="center">
  <img src="talentradar-frontend/public/icon.svg" alt="TalentRadar Logo" width="100" />
  <h1>🚀 TalentRadar AI</h1>
  <p><strong>Discover Talent Beyond Keywords</strong></p>
  
  <p>
    An Explainable Talent Discovery Engine that intelligently ranks candidates, discovers hidden talent, evaluates risk, and explains every hiring decision.
  </p>

</div>

---

## 💡 The Problem
Current Applicant Tracking Systems (ATS) rely heavily on exact keyword matching. This leads to massive inefficiencies in modern hiring:
- ❌ **Hidden talent is missed** because candidates use different terminology for the same skills.
- ❌ **Keyword stuffing** fools the system.
- ❌ **Black Box AI**: There is no explanation behind candidate rankings.
- ❌ **Recruiters lack context**: They don't understand *why* a candidate was selected.

## ✨ Our Solution
**TalentRadar AI** completely revolutionizes the talent discovery pipeline. Instead of looking for words, our AI looks for *meaning*. 

By leveraging advanced semantic matching, automated risk evaluation, and Explainable AI (XAI), TalentRadar helps recruiters find the perfect candidate—even if their resume doesn't perfectly match the exact wording of the job description.

---

## 🌟 Key Features

### 🧠 Semantic Matching
Our engine understands candidate profiles beyond exact keywords. If you ask for a "Machine Learning Engineer," the system understands that a candidate with "Deep Learning" and "Neural Networks" is a strong match, even if they don't explicitly say "Machine Learning."

### 🕵️ Hidden Talent Discovery (Our USP!)
Finds candidates with highly transferable skills. TalentRadar identifies candidates who might not fit traditional keyword filters but possess the exact foundational skills needed to excel in the role (e.g., matching a Backend Engineer to an AI role based on their robust Search Systems experience).

### 🤖 Explainable AI
No more black boxes. For every candidate ranked, TalentRadar generates a human-readable explanation detailing *exactly* why they were recommended, highlighting their strengths and skill alignments.

### 🛡️ Risk Analysis
Automatically detects risky hiring patterns. Our risk engine analyzes career momentum, tenure, and profile completeness to assign a Low, Medium, or High risk score to every applicant.

### 📊 Comprehensive Analytics Dashboard
A visually stunning dashboard that provides recruiters with bird's-eye insights into their talent pool, including score distributions, risk factors, and overall hiring funnel metrics.

---

## 🏗️ Architecture & Tech Stack

TalentRadar is a full-stack application built for performance and scale.

**Frontend:**
- ⚛️ **Next.js 14** (React) - App Router
- 🎨 **Tailwind CSS** - For sleek, modern, glassmorphism UI
- 📈 **Recharts** - Dynamic data visualization
- 🪟 **Lucide Icons** - Beautiful, consistent iconography

**Backend:**
- 🐍 **FastAPI** - High-performance Python backend
- 🧠 **AI Ranking Pipeline** - Custom Python modules for Semantic Matching, Risk Assessment, and Explainability

---

## 🚀 Quick Start (Local Development)

### 1. Start the Backend (FastAPI)
```bash
# Navigate to project root
pip install -r backend/requirements.txt
python -m backend.main
# Runs on http://localhost:8000
```

### 2. Start the Frontend (Next.js)
```bash
cd talentradar-frontend
npm install
npm run dev
# Runs on http://localhost:3000
```

---

## 📸 Application Flow

1. **Landing Page**: Visually stunning introduction to TalentRadar's capabilities.
2. **Dashboard**: High-level KPIs, Risk/Score distribution charts, and Recent Top Candidates.
3. **Candidate Ranking**: Input a Job Description, run the AI pipeline, and filter/sort candidates dynamically.
4. **Candidate Detail**: A deep-dive into a specific candidate, featuring a generated AI Recommendation, Skill Match matrix (✓/✗), Strengths/Weaknesses, and a visual Career Timeline.
5. **Hidden Talent**: Dedicated interface for discovering non-traditional candidates with high transferable skills.

---
<div align="center">
  <i>Built with ❤️ for the Hackathon</i>
</div>
