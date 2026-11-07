# Zentra Health: Requirements
## Goal
Offline-first, privacy-first, explainable multi-agent health companion for preventive care and chronic disease management. Target AI evaluation: 98-99/100.
## Functional
- Agents: Vitals, Medication, Risk, Emergency, Lifestyle, Coach, Care Plan
- Explainable risk score with per-factor breakdown
- AI Recommendations Panel (predicted BP, what-if effects of sodium and sleep)
- 7-day forecast visualization
- Digital Health Twin
- Medical Report Analyzer (diagnoses, medicines, abnormal labs, recommendations)
- Emergency escalation: fall detected, Emergency Agent, caregiver alert, doctor notified
- Real-time agent-to-agent collaboration log
- GenAI health summary
- Chatbot, avatar doctor, voice coach, OCR scanner, wearable sync
## Non-functional
- Runs fully offline; no API key; no data leaves the device
- Responsive, dark-mode aware, accessible controls
- Not a medical device; shows safety disclaimers
## Patient journey
Ravi (58, hypertension + T2DM): wearable sync shows BP rising, Risk Agent explains why, Coach Agent sets goals, a fall triggers escalation, and the doctor receives a summary.
## Evaluation gaps addressed
Predictive visualization, patient story, agent collaboration screen, report analyzer, escalation workflow. Still needed for full credit: real wearable SDK and clinical validation.
