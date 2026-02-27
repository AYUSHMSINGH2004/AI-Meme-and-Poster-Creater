# 🎨 AI Meme & Poster Creator

An interactive AI-powered web application that allows users to generate memes and posters instantly using AI-generated captions, custom text, and stylish templates.

Built using **Streamlit**, **Python**, and **Pillow**.

---

## 🚀 Live Demo

👉 https://ai-meme-and-poster-creater-vdwoqjmywzfkn49iykywio.streamlit.app/

---

## 📌 Features

- 🎭 AI-generated meme captions based on event name
- ✍ Manual caption writing option
- 🖼 Local template selection
- 🌐 Random internet background generation
- 🔤 Custom font selection (Google Fonts supported)
- 🎚 Adjustable font size
- 🖌 Meme-style white text with black outline
- ⬇ Download generated poster as PNG
- 🌙 Modern Reddit-style dark UI

---

## 🛠 Tech Stack

- Python 3.10+
- Streamlit
- Pandas
- Pillow (PIL)
- Requests

---

## 📂 Project Structure

AI-Meme-and-Poster-Creator/
│
├── app.py
├── caption_generator.py
├── poster_generator.py
├── final_captions.csv
├── requirements.txt
│
├── templates/
│ └── (local poster templates)
│
├── fonts/
│ └── (custom .ttf font files)



---

## ⚙ Installation (Run Locally)

### 1️⃣ Clone Repository

bash
git clone https://github.com/YOUR_USERNAME/AI-Meme-and-Poster-Creator.git
cd AI-Meme-and-Poster-Creator

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run Application

streamlit run app.py

Open browser at: http://localhost:8501

🌐 Deployment (Streamlit Cloud)

Push project to GitHub

Go to https://share.streamlit.io

Select repository

Branch: main

Main file: app.py

Deploy

🧠 How It Works

User enters an event name

App generates AI-based caption suggestions

User selects or writes their own caption

User selects template (local or internet)

Poster is generated using PIL

Final image can be downloaded

🎨 Customization

You can:

Add more templates in /templates

Add more fonts in /fonts

Update final_captions.csv to improve caption variety

Modify styling in app.py CSS section


📈 Future Improvements

Text position selector
Text color picker
Drag-and-drop text placement
Category-based internet backgrounds
Image preview grid layout
User authentication
Meme history storage

👨‍💻 Author

Ayush M. Singh
AI & ML Enthusiast
AIML Batch 2026

📄 License

This project is open-source and available under the MIT License.

