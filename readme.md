# 🏥 VitalSphere-AI

Offline-first, privacy-first, multi-agent AI health companion (MVP). No API key, no backend, no data upload.

## Run
Open `index.html` in any modern browser, or deploy to GitHub Pages / Vercel (HTTPS recommended for Bluetooth and voice).

## Core Features
- Dashboard: risk score, recovery score (0–100), adherence, trends
- Six agents with live status cards (Vitals, Medication, Lifestyle, Risk, Emergency, Coach)
- Explainable AI factor breakdown and Digital Health Twin
- Daily Health Coach summary, personalised goals
- Symptom checker, report analysis, medication tracking
- Emergency detection (stroke, heart attack, diabetic) with auto crisis banner
- What-if simulator, weekly report (print to PDF)

## 🚀 Advanced AI Features
- **AI Health Chatbot** – asks/answers from your live data
- **Interactive AI Avatar Doctor** – animated "Dr. Fusion" that speaks answers
- **Voice-Based Health Coach** – reads daily summary, voice questions in English/Hindi/Telugu
- **OCR Medical Report Scanner** – photo to extracted lab values with abnormal flags
- **Wearable Integration** – Bluetooth heart-rate band or smartwatch simulator, sync to log
- **GenAI Personalised Care Plans** – 4-week plan by focus area
- **Real-Time Predictive Risk Forecasting** – live 7-day risk curve with alerts

## Architecture
Rule-based agents share one state (localStorage). Risk Agent scores 0–100; Coach, Chatbot, Avatar, Care Plan and Forecast engines all read the same state, so every answer is explainable and consistent. Voice uses Web Speech API; wearables use Web Bluetooth; OCR uses Tesseract.js loaded on demand.

## 🎬 Demo Video Button
Click **🎬 Demo Video** (top right), then **▶ Start**. The app tours every feature automatically with spoken narration, captions, highlights and a progress bar (about 3 minutes). **■ Stop** ends it at any time; **🔊** toggles the voice. Use any screen recorder while it plays to capture your submission video.

## Demo Script = Demo Video (3:00)
The written script (📜 Script) and the narrated video use the **same 15 steps**: Welcome → Daily Coach → Agents & Explainable AI → Goals → Symptoms → Medication → OCR → Chatbot → Avatar & Voice → Wearables → Care Plan → Forecast → Emergency → What-If & Weekly → Closing. Read it as a script with a 3:00 timer, or press **▶ Play as video** to run it automatically.

## Browser Notes
Speech recognition and Bluetooth work best in Chrome/Edge. OCR needs internet once; otherwise paste report text.

## Disclaimer
Not a medical device. Informational only; in emergencies call 108/112 (India).
