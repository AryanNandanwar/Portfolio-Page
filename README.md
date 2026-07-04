# Aryan Nandanwar — Portfolio

A single-page developer portfolio showcasing selected projects:

## Featured

- **EchoAide** (doctorscribe-prod) — Production AI platform for outpatient clinics that generates clinical notes from doctor-patient conversations ([demo](https://www.loom.com/share/d81c882c16ef4079be582e4d605a4ce6))
  - Real-time transcription via Socket.IO and Soniox Streaming STT (90% latency reduction vs batch processing)
  - Claude Sonnet on AWS Bedrock with few-shot prompting for structured clinical notes
  - Patient intake queues, historical note retrieval, and role-based access control
  - Deployed with Docker, Nginx, and OCI-hosted Ubuntu VM for zero-downtime releases

## Other projects
- **Agent Inference Platform** — LLM chatbot with inference logging ([GitHub](https://github.com/AryanNandanwar/Ollive-AI))
- **[NephroSense AI](https://github.com/AryanNandanwar/NephroSense-AI)** — CKD risk prediction
- **[Subscart](https://github.com/AryanNandanwar/Subscart-)** — Meal subscription slot management
- **[Travel CRM](https://github.com/AryanNandanwar/Travel-CRM)** — Travel agency CRM

## Run locally

Open `index.html` in a browser, or serve with any static server:

```bash
npx serve .
# or
python -m http.server 8080
```

Then visit `http://localhost:8080` (or the port shown).

## Customize

- Update the email in `index.html` (`#contact` section)
- Adjust project descriptions or add live demo links as needed

## Deploy

This is static HTML/CSS/JS — deploy to GitHub Pages, Netlify, Vercel, or any static host by pointing at this directory.
