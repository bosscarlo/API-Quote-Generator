# Gemini Quote Generator API

A simple REST API built with **Node.js + Express** that generates motivational, funny, and inspirational quotes using **Google Gemini AI**.  
Perfect for demos, school projects, or just for fun 🚀.

---

## Features
- **GET /api/quote** → generate a quote using query parameters.
- Supports parameters:
  - `topic` → subject of the quote (e.g., success, love, dreams)
  - `mood` → tone of the quote (e.g., motivational, funny, hopeful)
  - `lang` → language (default: `en`)
  - `max_words` → max words in the quote (default: `20`, min: `6`, max: `30`)
- Returns a structured **JSON response**.

---

## Endpoints

### Health Check
