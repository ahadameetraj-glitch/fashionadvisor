# fashionadvisor
# Fashion AI Advisor API

This is a FastAPI backend that provides fashion outfit suggestions using OpenAI.

## 🚀 How to Deploy on Railway

1. Fork or upload this repo to your GitHub.
2. Go to [Railway](https://railway.app), create a new project → Deploy from GitHub.
3. Add Environment Variable:
   - `OPENAI_API_KEY = your_api_key`
4. Deploy → Get your public URL:
   ```
   https://your-app.up.railway.app/fashion-advice
   ```

## 🔗 Endpoint
- **POST** `/fashion-advice`
- Body (JSON):
  ```json
  {
    "occasion": "wedding",
    "mood": "joyful",
    "style": "traditional"
  }
  ```

- Response:
  ```json
  {
    "advice": "Outfit suggestions here..."
  }
  ```

