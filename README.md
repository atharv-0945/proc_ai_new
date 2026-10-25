# ProcureAI — AI-Powered Application Validation, Document Authentication and Regulatory Compliance Verification

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)](https://react.dev/) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/) [![Gemini](https://img.shields.io/badge/Gemini-2.5_Flash-4285F4?logo=google&logoColor=white)](https://ai.google.dev/) [![Groq](https://img.shields.io/badge/Groq-AI_Assistant-F55036)](https://groq.com/) [![Tesseract.js](https://img.shields.io/badge/Tesseract.js-OCR-5A29E4)](https://github.com/naptha/tesseract.js) [![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)](https://www.sqlite.org/) [![React Flow](https://img.shields.io/badge/React_Flow-Graph-FF0072)](https://reactflow.dev/)

> **"From institutional documents to structured, evidence-backed application validation."**

---

## 🖥️ Project preview 

![1st Image](1st_img.png)
![2nd Image](2nd_img.png)
![3rd Image](3rd_img.png)
![4th Image](4th_img.png)

**ProcureAI** is an AI-powered platform designed to help validate institutional applications, review supporting documents, identify inconsistencies, and assist with regulatory compliance checks. It aims to make the preliminary scrutiny of applications more consistent, transparent, and evidence-based

---

## 🎯 Problem Statement

The All India Council for Technical Education (AICTE), under the Ministry of Education, processes applications from technical institutions for Extension of Approval (EoA) and other approval-related changes.

Reviewing these applications involves checking institutional records, supporting documents, expiry dates, and compliance with applicable requirements. Manual verification can be time-consuming, while missing documents, inconsistent information, possible document alterations, and delays in confirming details with issuing authorities can increase administrative effort.

There is a need for a secure, AI-enabled platform that helps identify these issues early, supports document authentication, and assists authorized officials in regulatory review.
---

## 💡 Solution

ProcureAI proposes an AI-powered application validation workflow that combines OCR, document understanding, structured information extraction, rule-based validation, anomaly detection, and evidence-linked reporting.

The platform is designed to identify missing or expired documents, compare information across application records, flag potential document anomalies, and support verification through authorized sources wherever available. It can also assist in checking institutional infrastructure evidence and identifying cases that may need additional documents or physical inspection.

Institutional Application
          ↓
Application Category & Checklist
          ↓
Supporting Document Upload
          ↓
PDF Text Extraction / OCR
          ↓
AI Document Classification
          ↓
Structured Information Extraction
          ↓
Field & Document Validation
          ↓
Cross-Document Consistency Checks
          ↓
Authorized Source Verification
          ↓
Regulatory Compliance Assessment
          ↓
Evidence-Linked Findings & Alerts
          ↓
Application Review Dashboard
          ↓
Authorized Officer Review

The platform serves as a decision-support tool. Potential anomalies require further verification, and final regulatory decisions remain with the competent AICTE authorities.

## 🏗️ System Architecture

![System Architecture](system_archi.png)

## 🛠️ Technology Stack

![Technology Stack](tech_stack.png)

---

## 📁 Project Structure

```text
procure_ai_prototype/
│
├── backend/
│   ├── routers/
│   ├── schemas/
│   ├── services/
│   ├── models/
│   ├── uploads/
│   ├── config.py
│   ├── database.py
│   ├── main.py
│   ├── seed.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.*
│
├── ocr_worker/
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   └── eng.traineddata
│
├── package.json
├── package-lock.json
└── README.md
```
