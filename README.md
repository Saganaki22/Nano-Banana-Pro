# 🍌 Nano Banana Pro (Web Edition)

I created this lightweight web interface for **Nano Banana Pro** so I can generate images on my phone when I am away from my PC. 

It connects directly to the Google Gemini API (`gemini-3-pro-image-preview`) to generate high-quality images without needing a backend server.

## 🚀 Why I Made This
I needed a way to use the Gemini 3 Pro image capabilities on the go. This single-file web app allows me to:
- Generate images from text prompts.
- Use **Image-to-Image** capabilities (uploading photos from my phone).
- Debug API responses if something goes wrong.

## ✨ Features
*   📱 **Mobile Optimized:** Responsive design that works great on smartphones.
*   💾 **Auto-Save Key:** Your API key is saved to your browser's Local Storage, so you don't have to copy-paste it every time you open the app.
*   🔧 **Advanced Controls:** Change aspect ratios (16:9, 9:16, 1:1, 4:3, 3:4) and resolution settings.
*   ⚡ **Client-Side Only:** Runs entirely in your browser. No external servers involved.

## 🛠️ How to Use
1.  Open the hosted page (via GitHub Pages).
2.  Paste your **Google Gemini API Key**.
3.  Type a prompt or upload reference images.
4.  Click **Generate**.

## 🔒 Security Note
**Your API Key is safe.** 
The code runs 100% on your device. The API key is stored in your local browser cache and is sent directly to Google's servers. It is never sent to me or stored on GitHub.
