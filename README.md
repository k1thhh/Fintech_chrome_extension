# FinSight: AI-Powered Bill Scanner and Expense Categorizer

## Overview

FinSight is an intelligent browser extension designed to revolutionize personal finance management. Developed during an **Academic Internship at the National University of Singapore**, it automates the tedious process of expense tracking by extracting data from scanned bills and categorizing spending using advanced AI and Natural Language Processing (NLP). This full-stack solution provides users with real-time financial insights, personalized savings tips, and predictive analytics, including seamless integration with Google APIs for calendar access and event creation, all through an intuitive web dashboard.

## Key Features

* **Automated Bill Data Extraction:** Utilizes **OCR** (Optical Character Recognition) to accurately extract relevant financial data from scanned bills.
* **Intelligent Expense Categorization:** Employs **NLP** (Natural Language Processing) to automatically categorize expenses, simplifying budgeting and financial analysis.
* **Real-time Financial Insights:** Delivers immediate insights into spending patterns, offering personalized savings tips and predictive analytics through an integrated chatbot interface.
* **Google API Integration:** Enables creation of calendar events for bill payment reminders or financial milestones, ensuring users stay organized and on track with their budgets.
* **User Engagement:** Chatbot integration significantly boosts user engagement based on usage metrics.
* **Full-Stack Implementation:** Engineered with a robust **Python (Flask)** backend and a dynamic **HTML/CSS/React** frontend.
* **Browser Extension & Web Dashboard:** Deployed as a convenient browser extension with a responsive web dashboard for comprehensive financial tracking and visualization.

## Technologies Used

* **Backend:** Python (Flask), Google API
* **Frontend:** React, HTML/CSS
* **AI/ML:** Optical Character Recognition (OCR), Natural Language Processing (NLP), TensorFlow, PyTorch
* **Deployment:** Browser Extension framework
* **OCR DATASET:** https://www.kaggle.com/datasets/trainingdatapro/ocr-receipts-text-detection

## Impact & Results

FinSight transforms manual expense tracking into an automated, insightful process, significantly enhancing financial literacy and planning for users.

* Accurately parses and categorizes expenses from **1,350+ scanned bills** with **91% classification accuracy**.
* Delivers financial insights approximately **35% faster** compared to manual tracking.

## How It Works / Architecture

<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/c6d10e73-5abb-4fcc-80d5-ad35feeca622" />
<img width="475" height="463" alt="image" src="https://github.com/user-attachments/assets/2a8709a3-86ed-4a13-8f8f-4eae86d04d32" />


The system begins with bill submission via the browser extension. OCR processes the bill image to extract text data, which is then fed to NLP models for intelligent expense categorization. This categorized data is stored in the backend, powered by Flask. The React frontend interacts with the backend to display insights on a user-friendly dashboard. Deep Learning models, trained with TensorFlow and PyTorch, contribute to predictive analytics and financial trend insights delivered via the chatbot. **Google APIs are utilized to enable seamless integration with user calendars for automated reminders and event management.**

## Visuals
receipts used to train:
<img width="1117" height="373" alt="image" src="https://github.com/user-attachments/assets/86ed178c-4288-4345-b1f0-906b86350190" />
bill data extracted from ocr:
<img width="461" height="470" alt="image" src="https://github.com/user-attachments/assets/ac436b30-6c53-46ef-8878-d9d0001fd7ad" />
chatbot backend:
<img width="361" height="430" alt="image" src="https://github.com/user-attachments/assets/e366e0ac-5a1a-45cd-805b-6e663399e071" />
frontend setup: 
<img width="1898" height="973" alt="image" src="https://github.com/user-attachments/assets/5032acb2-74d5-43d4-8927-b496cf4d0021" />

## Future Work

* Integration with banking APIs for direct transaction import.
* Implementation of advanced machine learning models for more nuanced financial forecasting.
* Support for multiple currencies and international bill formats.
