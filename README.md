<div align="center">

<!-- Animated Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Groq%20Bilingual%20Chatbot&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=AI%20Chatbot%20%7C%20English%20%2B%20Urdu%20%7C%20Custom%20Business%20Data&descAlignY=60&descSize=18" width="100%"/>

<!-- Badges -->
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-FF4B4B?style=for-the-badge&logo=lightning&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bilingual-English%2FUrdu-green?style=for-the-badge" />
</p>

<p>
  <img src="https://img.shields.io/github/stars/habiburrahman849/groq-bilingual-chatbot?style=social" />
  <img src="https://img.shields.io/github/forks/habiburrahman849/groq-bilingual-chatbot?style=social" />
  <img src="https://img.shields.io/github/license/habiburrahman849/groq-bilingual-chatbot?color=blue" />
</p>

<br/>

> 🤖 **An AI-powered bilingual chatbot trained on custom business data.**  
> Built with **Groq's ultra-fast LLaMA3 API**, **React**, and **FastAPI** —  
> speaks fluent **English & Urdu** for Pakistani business audiences.

<br/>

**[🚀 Live Demo](#)** • **[📖 Docs](#installation)** • **[🐛 Report Bug](https://github.com/habiburrahman849/groq-bilingual-chatbot/issues)** • **[✨ Request Feature](https://github.com/habiburrahman849/groq-bilingual-chatbot/issues)**

</div>

---

## Features

-  **Bilingual Support** — Responds in English & Urdu seamlessly
-  **Groq API Powered** — Ultra-fast responses with LLaMA3-8b
-  **Custom Business Training** — Trained on your own business data (FAQ, services, contact)
-  **Real-time Chat UI** — Clean React interface with message bubbles
-  **Secure API Design** — API key never exposed to frontend
-  **Responsive Design** — Works on mobile and desktop
-  **Embeddable** — Can be embedded into any website

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React.js, CSS3 |
| **Backend** | FastAPI (Python) |
| **AI Engine** | Groq API — LLaMA3-8b-8192 |
| **Language** | Python 3.10+, JavaScript (ES6+) |
| **Data** | Custom `.txt` business knowledge base |

---

## 📁 Project Structure

```
groq-bilingual-chatbot/
├── frontend/                  
│   ├── src/
│   │   ├── components/
│   │   │   └── ChatWindow.jsx   ← Chat UI component
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── backend/                   
│   ├── main.py                  ← FastAPI routes
│   ├── chatbot.py               ← Groq logic
│   ├── business_data.txt        ← Custom business knowledge
│   └── requirements.txt
│
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/habiburrahman849/groq-bilingual-chatbot.git
cd groq-bilingual-chatbot
```

### 2. Backend Setup

```bash
cd backend
pip install -r requirements.txt
```

Create a `.env` file in `/backend`:
```env
GROQ_API_KEY=your_groq_api_key_here
```

Run the backend:
```bash
uvicorn main:app --reload
```

### 3. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

> 🌐 App runs at: `http://localhost:5173`

---

## 🔑 Get Your Groq API Key

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up for free
3. Click **API Keys** → **Create API Key**
4. Paste it in `backend/.env`

> ✅ Groq is **free to use** with generous rate limits!

---

## 🧠 How Business Training Works

Edit `backend/business_data.txt` with your business info:

```
Business Name: My Business
Services: [List your services]
Contact: [Phone / Email]
Location: [City, Pakistan]
FAQs:
- Q: What are your prices? A: ...
- Q: Do you deliver? A: Yes, we deliver across Pakistan.
```

The chatbot reads this file as **system context** on every request — no retraining needed. Just update the `.txt` file!

---


---

## 🚀 Call to Action

<div align="center">

### 💼 Want this chatbot for your business?

> This chatbot can be customized for **any Pakistani business** —  
> e-commerce stores, service providers, restaurants, clinics & more.

**[📩 Contact Me on LinkedIn](https://linkedin.com/in/habiburrahman-ai-ecommerce/)** | **[🐦 Follow on X](https://x.com/HabibUr11142637)**

<br/>

### ⭐ If this project helped you — please star the repo!

[![Star on GitHub](https://img.shields.io/github/stars/habiburrahman849/groq-bilingual-chatbot?style=for-the-badge&logo=github&color=yellow)](https://github.com/habiburrahman849/groq-bilingual-chatbot/stargazers)

</div>

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork the repo
- Create a feature branch (`git checkout -b feature/AmazingFeature`)
- Commit your changes (`git commit -m 'Add AmazingFeature'`)
- Push to the branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👨‍💻 Author

<div align="center">

**Habib Ur Rahman**  
AI & E-Commerce Developer | Pakistan 🇵🇰

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/habiburrahman-ai-ecommerce/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/habiburrahman849)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@futurewala1)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/HabibUr11142637)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
