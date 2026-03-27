**DALL-E Image Generator 🎨**
A Generative AI web application that transforms text prompts into stunning AI-generated images using  DALL-E model, built with Python and Flask.

Features
🖼️ Text-to-Image Generation — Enter any text prompt and generate a high-quality image in seconds
📐 Multiple Image Sizes — Choose from Square (1024×1024), Portrait (1024×1536), Landscape (1536×1024), or Auto
🗂️ Image Gallery — All generated images appear in a live gallery on the same page
⬇️ Download Images — Save any generated image directly to your device with one click
🔁 Reuse Prompts — Instantly reload a previous prompt back into the input field
⚡ Dark Mode UI — Clean, modern dark-themed interface

**Tech Stack**
Backend: Python, Flask
AI Model: OpenAI gpt-image-1 DALLE
Frontend: HTML5, CSS3, Vanilla JavaScript (Jinja2 templating)
Hosting: Replit

**How It Works**
Enter a descriptive text prompt in the input box
Select your preferred image size
Click Generate and wait 10–20 seconds
Your AI-generated image appears in the gallery below
Download or reuse the prompt as needed

**Setup**
pip install flask openai
python app.py
**Set the following environment variables:**

AI_INTEGRATIONS_OPENAI_BASE_URL=<your_openai_base_url>
AI_INTEGRATIONS_OPENAI_API_KEY=<your_openai_api_key>
