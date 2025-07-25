# 🧠 YOLO Human Detection UI

A responsive and modern **React** frontend for a human detection system using deep learning. This UI lets users upload images or stream from webcam (optional) to detect the presence of humans using a YOLOv8 or Keras-based model served via a **FastAPI backend**.

---

## 🚀 Features

- 🖼️ **Image Upload Detection** – Upload an image and detect if it contains humans.
- 💡 **Dark/Light Mode Toggle** – Built-in theme switcher using Material UI.
- 📊 **Detection Stats** – Displays confidence score, human count, inference time, etc.
- ⚙️ **Modular Design** – Easily extend or plug in other ML models.
- 🌍 **Deployable** – Ready for GitHub Pages or any static host.

---

## 🖥️ Tech Stack

### Frontend
- ⚛️ React + Vite
- 🎨 Material UI (MUI)
- 🎞️ AOS (Animate On Scroll)
- 📦 React Router DOM

### Backend (separate repo)
- ⚙️ FastAPI
- 🧠 TensorFlow / Keras or YOLOv8 (via Ultralytics)
- 🔁 REST API with CORS enabled

---

## 📂 Project Structure

