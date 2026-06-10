# 💰 InvestEasy

## AI-Powered Investment Learning & Portfolio Recommendation Platform

InvestEasy is a full-stack MERN + AI application that helps beginners understand investing, assess their risk profile, receive portfolio recommendations, and learn financial concepts through an AI-powered tutor.

The platform is designed to bridge the gap between financial curiosity and financial confidence by combining risk assessment, portfolio guidance, and AI-driven education in a single user-friendly experience.

---

## 🌐 Live Demo

**Frontend:** https://invest-easy-frontend.vercel.app/

**Backend API:** https://investeasy-backend-smb3.onrender.com/

---

## 📖 Overview

Many first-time investors are interested in building wealth but struggle with questions such as:

* What type of investor am I?
* How much risk should I take?
* How should I allocate my investments?
* What do financial terms like diversification, SIPs, and mutual funds actually mean?

InvestEasy simplifies the learning process through guided assessments, intelligent recommendations, and AI-powered explanations designed specifically for beginners.

---

## ✨ Features

### 🔐 Authentication & Security

* User Registration
* Secure Login
* JWT Authentication
* Protected Routes
* Persistent Sessions
* Password Hashing with bcryptjs

---

### 📊 Risk Assessment Engine

Users complete a structured assessment covering:

* Investment Horizon
* Market Crash Behavior
* Loss Tolerance
* Investment Knowledge
* Portfolio Preferences
* Risk vs Return Expectations

The platform calculates:

* Risk Score
* Investor Classification

#### Investor Categories

🟢 Conservative

🟡 Moderate

🔴 Aggressive

---

### 📈 Portfolio Recommendation Engine

Based on assessment results, InvestEasy generates personalized portfolio allocation suggestions.

#### Conservative Portfolio

| Asset        | Allocation |
| ------------ | ---------- |
| Stocks       | 20%        |
| Mutual Funds | 30%        |
| Bonds        | 40%        |
| Cash         | 10%        |

#### Moderate Portfolio

| Asset        | Allocation |
| ------------ | ---------- |
| Stocks       | 40%        |
| Mutual Funds | 40%        |
| Bonds        | 15%        |
| Cash         | 5%         |

#### Aggressive Portfolio

| Asset        | Allocation |
| ------------ | ---------- |
| Stocks       | 70%        |
| Mutual Funds | 20%        |
| Bonds        | 5%         |
| Cash         | 5%         |

---

### 🤖 AI-Powered Explanations

Google Gemini generates beginner-friendly explanations for every recommendation.

The AI:

* Explains portfolio decisions
* Uses simple language
* Provides real-world examples
* Highlights risks and trade-offs
* Avoids financial guarantees

---

### 🎓 AI Investment Tutor

Users can ask investing-related questions such as:

* What is a mutual fund?
* What is diversification?
* How do SIPs work?
* Why are bonds considered safer than stocks?

The AI Tutor responds with concise, beginner-friendly educational explanations.

---

### 📜 Assessment & Recommendation History

Users can track their investment journey through:

* Assessment History
* Recommendation History
* Risk Score Evolution
* Previous Portfolio Allocations

---

### 🌙 Modern User Experience

* Fully Responsive Design
* Dark Mode Support
* Clean Dashboard Interface
* Mobile-Friendly Layout
* Consistent Design System

---

## 🏗️ System Architecture

```text
User
 │
 ▼
React + Tailwind Frontend
 │
 ▼
Express.js REST API
 │
 ├── Authentication Layer
 ├── Risk Assessment Engine
 ├── Recommendation Engine
 └── AI Integration Layer
 │
 ▼
MongoDB Atlas
 │
 ▼
Google Gemini AI
```

---

## 🛠️ Tech Stack

### Frontend

* React
* React Router DOM
* Axios
* Tailwind CSS
* Vite

### Backend

* Node.js
* Express.js
* JWT Authentication
* bcryptjs

### Database

* MongoDB Atlas
* Mongoose

### Artificial Intelligence

* Google Gemini 2.5 Flash
* @google/genai

### Deployment

* Vercel (Frontend)
* Render (Backend)

---

## 📸 Screenshots

### Login Page

<img width="1919" height="911" alt="image" src="https://github.com/user-attachments/assets/cd966bce-81ac-46bf-a088-c488761c06d2" />


### Dashboard

<img width="1897" height="909" alt="image" src="https://github.com/user-attachments/assets/88602187-9012-47f8-81d4-226b3b0d67e0" />


### Risk Assessment

<img width="741" height="906" alt="image" src="https://github.com/user-attachments/assets/1b38c0ec-7558-49ad-a9ee-4a6e201de22d" />


### Portfolio Recommendation

<img width="1058" height="899" alt="image" src="https://github.com/user-attachments/assets/1fba6da7-6b17-41ec-9af7-37bb1ff60779" />


### AI Investment Tutor

<img width="981" height="905" alt="image" src="https://github.com/user-attachments/assets/9e1fce9d-c7c1-454d-88b0-a8d863249642" />


### Assessment History

<img width="1369" height="897" alt="image" src="https://github.com/user-attachments/assets/40e9bc04-deb0-4543-a51e-3209e78a24c0" />


### Recommendation History

<img width="1255" height="894" alt="image" src="https://github.com/user-attachments/assets/90338936-8d06-40fa-966d-e344ebd40ebb" />



---

## 🚀 Getting Started

### Clone Repositories

Frontend:

```bash
git clone https://github.com/Saipraneeth5/InvestEasy-frontend.git
```

Backend:

```bash
git clone https://github.com/Saipraneeth5/InvestEasy-backend.git
```

### Backend Setup

```bash
npm install
npm run dev
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

### Frontend Setup

```bash
npm install
npm run dev
```

Create a `.env` file:

```env
VITE_API_URL=http://localhost:5000/api
```

---

## 📂 Repositories

### Frontend Repository

https://github.com/Saipraneeth5/InvestEasy-frontend

### Backend Repository

https://github.com/Saipraneeth5/InvestEasy-backend

---

## ⚠️ Disclaimer

InvestEasy is an educational platform created for learning and portfolio purposes.

It:

* Does not execute trades
* Does not connect to brokers
* Does not provide personalized financial advice
* Does not guarantee investment returns
* Does not predict market movements

All recommendations are generated solely for educational and learning purposes.

---

## 👨‍💻 Author

**Sai Praneeth**

Built to help beginners understand investing through risk assessment, portfolio recommendations, and AI-powered financial education.

---

⭐ If you found this project interesting, consider giving the repositories a star.
