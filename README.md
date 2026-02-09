# 🌱 KlimaTwin

**KlimaTwin** is an AI-driven, low-power **Campus Climate Twin** that monitors **energy, water, air quality, and e-waste** at campus scale and converts real-time insights into **personalized behavioral nudges** and **data-backed micro-policies**.

**Goal:**  
Reduce campus resource waste **measurably within weeks** using edge AI, short-term forecasting, and behavioral science.

---

## 📌 Problem Statement

University campuses waste significant energy, water, and materials due to:

- Lack of real-time, fine-grained visibility  
- Siloed sustainability initiatives  
- Low student engagement with static awareness campaigns  

Most existing solutions **only observe consumption**.  
**KlimaTwin actively drives behavior change and verifies impact.**

---

## 💡 Solution Overview

KlimaTwin operates as a **closed-loop system**:

**Sense → Predict → Nudge → Verify → Learn**

It functions as a **lightweight operational digital twin** of a campus, enabling **short-term, actionable sustainability decisions** instead of delayed reporting.

---

## 🧠 Key Features

- 📊 Real-time monitoring (energy, water, air quality, e-waste)  
- ⚡ Low-power edge AI with event-based filtering  
- 🔮 Short-term consumption & air-quality forecasting  
- 🧠 AI ranking of highest-impact actions  
- 💬 LLM-generated personalized nudges  
- 🏆 Hostel-level comparison and gamification  
- ✅ Impact verification (before vs after analysis)  
- ♻️ QR-based e-waste logging and classification  

---

## 🏗️ System Architecture

### 1. Edge Layer
- ESP32-class devices  
- Lightweight ML / TinyML concepts  
- Event-triggered data transmission  

### 2. Ingestion Layer
- MQTT / REST APIs  
- Centralized data gateway  

### 3. Processing Layer
- Time-series database  
- Anomaly detection and trend analysis models  

### 4. AI Layer
- Short-term forecasting models  
- LLM-based nudge generation engine  

### 5. Application Layer
- Web dashboards for students and administrators  
- Notification services (App / WhatsApp / Displays)  

---

## 🔄 Process Flow

1. Sensors or simulated meters collect data  
2. Edge AI filters events to reduce noise and power usage  
3. Backend ingests time-series data  
4. Digital twin forecasts short-term usage  
5. AI ranks highest-impact actions  
6. LLM generates personalized nudges  
7. Students and admins take action  
8. System verifies impact and improves models  

---

## 🧪 Demo & Prototype Scope

For hackathon feasibility, KlimaTwin:

- Uses **simulated + limited real sensor data**  
- Demonstrates **one complete closed loop**  
- Focuses on **weekly measurable outcomes**, not long-term projections  

---

## 🛠️ Tech Stack

- **Languages:** Python, JavaScript  
- **Backend:** FastAPI / Node.js  
- **Frontend:** React  
- **AI/ML:** PyTorch, Scikit-learn  
- **Edge AI:** TinyML concepts  
- **Data:** Time-series databases  
- **Deployment:** Containerized (Docker-ready)  

---

## ⚙️ AMD Relevance

- Optimized for high-performance AI inference on AMD CPUs  
- Parallel processing for forecasting and simulations  
- Energy-efficient compute aligned with sustainability workloads  

---

## 📈 Impact Potential

- Reduced peak energy consumption in hostels  
- Lower water usage through behavior-driven interventions  
- Improved air-quality awareness at campus hotspots  
- Increased e-waste collection and circular practices  

---

## 🚀 Scalability

- Config-driven deployment for new campuses  
- Modular architecture (domains can be added or removed easily)  
- Extendable to institutional campuses or city blocks  

---

## 📂 Repository Structure (Suggested)

```text
├── edge/
│   └── edge_ml_simulation/
├── backend/
│   ├── ingestion/
│   ├── forecasting/
│   └── nudge_engine/
├── frontend/
│   └── dashboard/
├── data/
│   └── simulated_streams/
├── docs/
│   └── diagrams/
└── README.md

📽️ Demo
Demo Video: https://youtu.be/mbN-pg-v1AU
Live Prototype: https://greenwave-campus-pulse.lovable.app/

👥 Team
Team Name: KlimaTwin
Team Lead: yessasvini

📜 License
This project is developed for hackathon and research purposes.

🏁 Final Note
KlimaTwin is designed as a pilot-ready sustainability system, not just a demo.
It prioritizes measurable impact, feasibility, and behavioral change over abstract climate metrics.
