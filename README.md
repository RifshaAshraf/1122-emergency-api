# 1122 Emergency Classification API

> A FastAPI microservice that transcribes Urdu emergency calls, classifies them into Fire/Medical/Accident/Normal using a Random Forest ML model, and generates dispatch-ready response messages.

---

## 🚀 Features

- **/transcribe_and_classify**: Upload an Urdu `.wav` or `.mp3` call and get back:
  - `emergency_type`: Fire / Medical / Accident / Normal  
  - `response_message`: e.g. “Ambulance is on the way”
- **/classify**: Send plain English text (or translated transcript) and receive the same JSON response.
- **Lightweight**: Built with FastAPI + Uvicorn for <100 ms inference.
- **Containerized**: Dockerfile included for cloud deployments (Cloud Run, ECS, Render, etc.).

---



