# VitalSphere-AI – Requirements

## Goal
An offline, privacy-first, multi-agent health companion that turns daily vitals into explainable risk, coaching and emergency guidance.

## Functional Requirements
| ID | Feature | Description |
|----|---------|-------------|
| FR1 | Health Dashboard | Risk score, recovery score, adherence, trend charts |
| FR2 | Multi-Agent Architecture | Vitals, Medication, Lifestyle, Risk, Emergency, Coach agents with live status cards |
| FR3 | Explainable AI | Per-factor point breakdown of the risk score |
| FR4 | Digital Health Twin | Snapshot of BMI, BP, glucose, weight, sleep, biological load |
| FR5 | Risk Scoring Engine | Rule-based 0–100 score (BP, glucose, BMI, activity, sleep, adherence, age) |
| FR6 | Daily Health Coach Summary | Week-over-week BP %, adherence change, activity and sleep tips |
| FR7 | Personalised Goals | Weight, BP and activity targets with progress bars |
| FR8 | Recovery Score | 0–100 improvement score from risk and adherence |
| FR9 | Symptom Checker | Rule-based possible causes with urgent flag |
| FR10 | Report Analysis | Hemoglobin, cholesterol, HbA1c, creatinine classification |
| FR11 | Medication Tracking | Add medicines, one-tap taken, adherence % |
| FR12 | Emergency Detection | Stroke, heart attack, diabetic warnings plus automatic crisis banner |
| FR13 | What-If Simulator | Projected risk for weight, steps, sleep, adherence changes |
| FR14 | Weekly Report | Averages and trends, printable to PDF |
| FR15 | 3-Minute Demo Script | Button opens timed script with countdown highlighting |

## Advanced AI Requirements
| ID | Feature | Description |
|----|---------|-------------|
| FR16 | AI Health Chatbot | On-device intent engine answering from live health data, with quick-question chips |
| FR17 | Voice-Based Health Coach | Web Speech API: reads daily summary, answers voice questions (English, Hindi, Telugu) |
| FR18 | OCR Medical Report Scanner | Image upload, Tesseract.js OCR, value extraction (Hb, cholesterol, HbA1c, creatinine, glucose), abnormal flags, paste-text fallback |
| FR19 | Wearable Integration | Web Bluetooth heart-rate band plus smartwatch simulator (HR, SpO2, steps, sleep); sync to daily log |
| FR20 | GenAI Care Plans | Personalised plan (nutrition, activity, sleep, medication, monitoring, 4-week milestones) with focus selector |
| FR21 | Real-Time Predictive Risk Forecasting | 7-day risk forecast from linear trends, live refresh, wearable heart-rate factor, high-risk alert |
| FR22 | Interactive AI Avatar Doctor | Animated SVG doctor that speaks answers with lip-sync and accepts text or voice |
| FR23 | Auto-Playing Demo Video | Header button opens a player that narrates and walks through every feature automatically, with Start, Stop, voice mute, progress bar, captions and spotlight highlighting |

## Non-Functional Requirements
- Offline-first: no API key and no backend; data stays in localStorage. Only the optional OCR engine downloads once on first scan (paste-text fallback works offline)
- Privacy-first: nothing leaves the device
- Responsive/mobile friendly, light and dark theme
- Single-file deployment (index.html)
- Accessible controls with clear labels

## Safety
Informational only; not a medical diagnosis. Emergency guidance directs users to 108/112.

## Out of Scope
Cloud sync, wearable integration, clinical validation, multi-user accounts.
