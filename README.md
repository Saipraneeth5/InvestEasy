# 💰 InvestEasy

### AI-Powered Investment Learning & Portfolio Recommendation Platform

InvestEasy is a full-stack MERN + AI application designed to help beginners understand investing, evaluate their risk profile, receive portfolio recommendations, and learn financial concepts through an AI-powered tutor.

The platform focuses on financial education and decision support rather than investment execution.

---

## 🚀 Problem Statement

Many beginners want to start investing but struggle with questions such as:

* How much risk should I take?
* What type of investor am I?
* How should I allocate my investments?
* What do financial terms actually mean?

InvestEasy simplifies this journey through guided assessments, portfolio recommendations, and AI-driven explanations.

---

## ✨ Key Features

### 🔐 Authentication

* User Registration
* Secure Login
* JWT Authentication
* Protected Routes
* Persistent Sessions

---

### 📊 Risk Assessment Engine

Users complete a structured questionnaire covering:

* Investment Horizon
* Market Crash Behavior
* Loss Tolerance
* Financial Knowledge
* Portfolio Preferences
* Risk vs Return Expectations

The platform calculates:

* Risk Score
* Investor Classification

Investor Categories:

* Conservative
* Moderate
* Aggressive

---

### 📈 Portfolio Recommendation Engine

Based on assessment results, InvestEasy generates a portfolio allocation strategy.

Example:

#### Conservative

* Stocks: 20%
* Mutual Funds: 30%
* Bonds: 40%
* Cash: 10%

#### Moderate

* Stocks: 40%
* Mutual Funds: 40%
* Bonds: 15%
* Cash: 5%

#### Aggressive

* Stocks: 70%
* Mutual Funds: 20%
* Bonds: 5%
* Cash: 5%

---

### 🤖 AI-Powered Explanations

Google Gemini generates beginner-friendly explanations for each recommendation.

The AI:

* Explains portfolio decisions
* Uses simple language
* Provides real-world analogies
* Highlights risks and rewards
* Avoids financial guarantees

---

### 🎓 AI Investment Tutor

Users can ask investing-related questions such as:

* What is a mutual fund?
* What is diversification?
* Why are bonds considered safer?

The AI Tutor responds with simple educational explanations designed for beginners.

---

### 📜 History Tracking

Users can review:

* Previous Assessments
* Previous Recommendations
* Risk Score Evolution
* Historical Portfolio Suggestions

---

## 🏗️ Architecture

User

↓

React + Tailwind CSS Frontend

↓

Express.js REST API

↓

Business Logic Layer

* Risk Scoring Engine
* Recommendation Engine
* AI Integration Layer

↓

MongoDB Atlas

↓

Google Gemini AI

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

### AI

* Google Gemini 2.5 Flash
* @google/genai

---

## 📸 Screenshots

Add screenshots of:

* Login Page
* Dashboard
* Risk Assessment
* Recommendation Page
* AI Tutor
* History Pages

---

## 🔗 Project Repositories

### Frontend

[InvestEasy Frontend Repository]

### Backend

[InvestEasy Backend Repository]

---

## ⚠️ Disclaimer

InvestEasy is an educational platform.

It:

* Does not predict stock prices
* Does not execute trades
* Does not connect to brokers
* Does not provide personalized financial advice
* Does not guarantee investment returns

All recommendations are generated for educational and learning purposes only.

---

## 👨‍💻 Author

Sai

Built as a full-stack MERN + AI project to help beginners learn investing through risk assessment, portfolio recommendations, and AI-powered financial education.
