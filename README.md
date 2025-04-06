# 🔥 Fire Detection API (FastAPI + Gradio + Supabase)

This API receives an image URL (uploaded to Supabase), passes it to a hosted Gradio model, and returns a prediction. If the result is "Fake", Supabase removes the image via the frontend logic.

## 🔧 Endpoint

**POST** `/predict`

**Form Field:**  
- `image_url`: string (URL of the image on Supabase)

**Returns:**  
- JSON with prediction result.

## 🚀 Hosted on: Render / Railway / Replit
