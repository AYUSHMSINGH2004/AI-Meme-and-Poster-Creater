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

1. Push project to GitHub
2. Go to https://share.streamlit.io
3. Select repository
4. Branch: main
5. Main file: app.py
6. Deploy


🧠 How It Works

1. User enters an event name
2. App generates AI-based caption suggestions
3. User selects or writes their own caption
4. User selects template (local or internet)
5. Poster is generated using PIL
6. Final image can be downloaded


🎨 Customization

You can:

a. Add more templates in /templates
b. Add more fonts in /fonts
c. Update final_captions.csv to improve caption variety
d. Modify styling in app.py CSS section


📈 Future Improvements

a. Text position selector
b. Text color picker
c. Drag-and-drop text placement
d. Category-based internet backgrounds
e. Image preview grid layout
f. User authentication
g. Meme history storage

👨‍💻 Author

Ayush M. Singh
AI & ML Enthusiast
AIML Batch 2026

📄 License

This project is open-source and available under the MIT License.

