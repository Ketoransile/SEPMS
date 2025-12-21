Smart Entrepreneurial Pitching & Matching System (SEPMS)
Final Year Project – Documentation & Planned Implementation
📌 Project Overview

The Smart Entrepreneurial Pitching & Matching System (SEPMS) is an AI-assisted digital platform designed to facilitate structured pitch submission, intelligent evaluation, and effective matching between entrepreneurs and potential investors. The system aims to reduce inefficiencies in traditional pitching processes by introducing automated guidance, semantic analysis, and data-driven recommendations.

The platform supports three primary user roles: Entrepreneurs, Investors, and Administrators, each interacting with the system through role-specific workflows. Artificial intelligence components are incorporated to assess idea completeness, generate semantic embeddings, and recommend relevant investment opportunities.


🎯 Project Objectives

To provide entrepreneurs with structured, AI-guided pitch submission templates

To enable investors to discover high-potential projects using semantic matching

To reduce manual screening through automated idea validation

To support multilingual and voice-based interactions

To ensure scalability and cost-efficiency using open-source technologies

🧩 System Roles
1. Entrepreneur

Register and verify account

Submit business ideas and supporting documents

Receive AI feedback on pitch completeness

Request meetings with interested investors

2. Investor

Register and define investment preferences

Receive AI-generated project recommendations

Interact via text or voice queries

Engage in milestone-based investment simulation

3. Administrator

Approve and manage user accounts

Monitor submissions and AI decisions

View system analytics and audit actions

🏗️ Proposed System Architecture

The system follows a modular, service-oriented architecture composed of:

Client Layer: Web (Next.js) and Mobile (Flutter)

Backend API: Node.js with Express

Authentication: Firebase Authentication

Database: MongoDB Atlas

Vector Database: Qdrant

AI/ML Services: Python-based services (scikit-learn, Sentence Transformers)

Cloud Storage: Cloudinary

All components are designed to be loosely coupled to support future scalability and maintenance.

🤖 AI & Machine Learning Components

The AI pipeline includes:

Template Completeness Checker

Idea Quality Classification using scikit-learn models

Semantic Embedding Generation using all-MiniLM-L6-v2

Similarity Matching via cosine similarity in Qdrant

Text Summarization using T5-small

Voice Interaction

Speech-to-text: Whisper.cpp

Text-to-speech: Coqui TTS

These components are selected to ensure free, open-source, and offline-capable operation.

🛠️ Planned Technology Stack
Frontend

Next.js

Tailwind CSS

shadcn/ui

Redux Toolkit

Backend

Node.js

Express.js

RESTful APIs

Database & Storage

MongoDB Atlas

Qdrant

Cloudinary

AI / ML

Python

scikit-learn

Sentence Transformers (all-MiniLM-L6-v2)

T5-small

Whisper.cpp

Coqui TTS

Development Tools

Git & GitHub

VS Code

Draw.io / PlantUML

Postman (planned)

📄 Project Documentation Structure

This repository aligns with the university-approved documentation structure:

Chapter 1: Introduction

Chapter 2: Existing System & Literature Review

Chapter 3: Proposed System

Chapter 4: System Design

Chapter 5: Implementation (Documentation Phase)

Diagrams and artifacts include:

Use Case Diagrams

Class Diagrams

System Architecture Diagrams

AI Workflow Diagrams

Low-fidelity UI Wireframes

📅 Project Status & Timeline
Phase	Status
Requirements & Analysis	Completed
System Design	Completed
Documentation	In Progress
Implementation	Planned (Next Semester)
Testing & Deployment	Planned
📂 Repository Structure (Planned)
SEPMS/
├── docs/
│   ├── chapter1-2/
│   ├── chapter3/
│   ├── chapter4/
│   └── chapter5/
├── diagrams/
│   ├── usecase/
│   ├── class/
│   ├── architecture/
│   └── workflows/
├── wireframes/
├── backend/        # (Next semester)
├── frontend/       # (Next semester)
└── README.md

⚖️ Academic Notice

This repository is maintained as part of a final year academic project. All implementation claims are forward-looking and reflect planned development activities. The system is not currently deployed or operational.

👥 Contributors

Project Team: Final Year Software Engineering Students

Institution: [Your University Name]

Academic Year: 2025–2026

📜 License

This project is intended for academic use only. Commercial use is not permitted without prior authorization.



Align it exactly with your Chapter 5 wording

Just say the word.
