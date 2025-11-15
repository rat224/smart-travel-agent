
# Smart Travel Agent – AI Capstone Project

## Overview
Smart Travel Agent is an intelligent itinerary-generation agent powered by both OpenAI (primary) and Gemini (fallback). It provides:
- Dynamic travel planning
- Weather forecasting
- Mock flights/hotels
- JSON-structured itineraries
- Dual LLM fallback

## Features
- FastAPI backend
- OpenAI + Gemini hybrid agent
- Geocoding + weather integration
- Clean JSON outputs
- Flexible preferences

## How to Run
```bash
cd backend
pip install -r requirements.txt
$env:OPENAI_API_KEY="sk-xxxx"
$env:GEMINI_API_KEY="AIzaSyxxxx"
uvicorn app.main:app --reload --port 8000
```

## API
Open browser:
`http://127.0.0.1:8000/docs`

## Project Structure
```
backend/
  app/
    main.py
    agent.py
    llm_openai.py
    llm_gemini.py
    tools/
    prompts.py
```

## Submission
Include:
- GitHub link
- Demo video
- PPTX Slides
- PDF summary
