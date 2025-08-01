# Product Recommendation System (Task 2)

This is a simple AI-powered product recommendation app.

Users can enter natural-language preferences like:

> "Suggest a phone under $500"

...and the app will return a list of matching products using AI filtering.

---

## Features

- React frontend with Vite
- Product list stored locally
- User input passed to OpenRouter (GPT API)
- Recommendations shown dynamically
- Environment variables used to store API key

---

## Tech Stack

- React + Vite
- OpenRouter API (Free GPT-3.5 proxy)
- JavaScript (ES6)

---

## Running Locally

1. Clone the repo

2. Create a `.env.local` file in the root:
   ```env
   VITE_OPENROUTER_API_KEY=your-api-key-here
