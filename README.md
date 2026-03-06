# PhishGuard AI  
### AI-Powered Phishing URL Detection System

PhishGuard AI is a web application designed to detect and analyze potentially malicious URLs using AI-driven techniques and multi-layer security checks. The system evaluates structural and behavioral characteristics of a URL to determine whether it is likely to be a phishing attempt.

This project demonstrates the practical application of heuristic analysis, database validation, and ensemble scoring to enhance cybersecurity awareness.

---

## Features

- Real-time URL analysis  
- AI-based phishing detection  
- Confidence score with risk assessment  
- Integration with phishing and trusted domain databases  
- 20+ heuristic security checks  
- Detailed security reports with recommendations  
- Responsive and user-friendly interface  
- Serverless deployment using Vercel  

---

## How It Works

### 1. Database Validation
- PhishTank database lookup  
- Trusted domain whitelist  
- Known phishing pattern detection  

### 2. Heuristic Analysis
The URL is evaluated based on several indicators, including:
- Suspicious keywords  
- URL length and structure  
- Number of subdomains  
- Top-level domain risk  
- HTTPS and SSL usage  
- Presence of IP addresses  
- Special characters and obfuscation  
- Shortened URLs  
- Custom ports  
- Domain reputation  

### 3. Ensemble Scoring Model
All checks are combined using a weighted scoring approach to generate:
- Phishing prediction (Safe / Suspicious)  
- Confidence percentage  
- Risk breakdown  
- Security recommendations  

---

## Technology Stack

### Frontend
- HTML5  
- CSS3  
- JavaScript (ES6)  

### Backend
- Node.js (Serverless Functions)  
- Vercel deployment platform  

---

## Installation and Setup

### Clone the Repository

```bash
git clone <repository-url>
cd phishguard-ai
