# 🏦 Smart Choice - AI-Powered FinTech & Loan Origination System

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Website-blue?style=for-the-badge)]([https://smartchoice-lj5e.onrender.com/])
[![Python](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python&logoColor=white)]()
[![Flask](https://img.shields.io/badge/Flask-3.0.3-black?style=for-the-badge&logo=flask&logoColor=white)]()

## 🚀 Overview
**Smart Choice** is a comprehensive, full-stack web application designed to simulate a real-world Core Banking and Loan Origination System (LOS). It digitizes the end-to-end home loan application process, featuring a highly interactive Glassmorphism UI, a secure Maker-Checker admin portal, and a proprietary Mock AI Underwriting Engine.

## ✨ Key Features

* **🤖 Auto-Approval AI Engine:** Evaluates applicant risk dynamically by calculating FOIR (Fixed Obligation to Income Ratio) and mock CIBIL scores to simulate instant loan sanctioning.
* **👨‍💼 Maker-Checker Admin Portal:** A dedicated workspace for DSA/Partners to visually review uploaded KYC documents and manually approve or reject applications.
* **🔒 Smart KYC Vault:** Secure file upload system that renames, stores, and tracks the verification status of highly sensitive user documents (Aadhaar, PAN, Bank Statements).
* **📊 Interactive Credit Score Checker:** A visually rich lead-generation tool using GSAP-animated linear gauge meters to fetch and display mock bureau reports.
* **🛡️ Persistent Authentication:** Role-Based Access Control (RBAC) for 'Partners' and 'Customers' utilizing Werkzeug password hashing and secure server-side session management.
* **💎 Enterprise UI/UX:** Built with modern CSS variables, Bento grid layouts, custom cursors, and Glassmorphism design principles.

## 🛠️ Tech Stack

**Frontend**
* HTML5 & CSS3 (Glassmorphism & Bento Grids)
* Vanilla JavaScript (DOM Manipulation & Fetch API)
* GSAP (High-performance UI animations)

**Backend & Database**
* Python 3
* Flask (WSGI Framework & REST APIs)
* SQLite (Database) & Flask-SQLAlchemy (ORM)
* Werkzeug (Security & File Sanitization)

**Deployment**
* Gunicorn
* Render Platform

## 💻 Running the Project Locally

## 📦 Installation

Follow these steps to set up the project locally:

1️⃣ **Clone the repository**

```bash
git clone [https://github.com/yourusername/smart-choice-fintech.git](https://github.com/yourusername/Home-Loan-Page.git)
cd Home-Loan-Page

2️⃣ Create a Virtual Environment (Optional but recommended)

Bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3️⃣ Install dependencies

Bash
pip install -r requirements.txt

4️⃣ Start the development server

Bash
python app.py
5️⃣ Open the project in your browser at:
http://127.0.0.1:5001/

📜 License
This project is for educational purposes and aims to demonstrate a real-world FinTech & Core Banking System using modern web technologies and AI logic.

Made with ❤️ by Nirmal Babu V M
