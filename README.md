# 📸 Party Photos Upload Web App

A lightweight, zero-backend web application built for event guests to easily upload party photos and videos directly from their phone camera or photo gallery to a central cloud repository. 

Designed with a high-contrast, simple interface—ideal for guests of all ages and tech comfort levels.

---

## ✨ Features
* **No Account Required:** Guests do not need to register, sign in, or download an app.
* **Instant Media Previews:** Local thumbnails display immediately upon selection using browser Blob URLs.
* **Real-time Status Overlay:** Shows dynamic upload spinners, success checkmarks, and error badges per photo.
* **Batch Uploading:** Processes files sequentially to avoid request timeouts on weak mobile connection speeds.
* **Direct Cloud Storage:** Uploads media straight to Cloudinary using an unsigned upload preset.

---

## 🛠️ Project Structure
```text
partyphotos/
├── index.html   # Main web interface, styling, and client-side upload logic
└── README.md    # Documentation and setup instructions
