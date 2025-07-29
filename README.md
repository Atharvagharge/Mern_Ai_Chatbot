# MERN AI Chatbot 🤖

An AI-powered SaaS chatbot built with the **MERN stack (MongoDB, Express.js, React, Node.js)**, providing intelligent conversational support for businesses. Integrates NLP models for seamless user interaction and automation.

---

## 🚀 Features

- 💬 **AI-Powered Chat Interface** – Real-time intelligent conversation using NLP.
- 🗄️ **MongoDB Database** – Stores chat history, user sessions, and analytics.
- 🌐 **REST API** – Robust backend with Express and Node.js.
- ⚛️ **React Frontend** – Responsive and interactive chat UI.
- 🔒 **Secure API Key Handling** – Environment variable support for OpenAI and other services.
- 📊 **Analytics Ready** – Track conversation patterns and engagement.

---

## 🧑‍💻 Tech Stack

| Frontend     | Backend        | AI/NLP      | Database   |
|--------------|----------------|-------------|------------|
| React.js     | Node.js        | OpenAI API  | MongoDB    |
| TypeScript   | Express.js     | LangChain*  | Mongoose   |
| Tailwind CSS | FastAPI* (optional) |         |            |

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Atharvagharge/Mern_Ai_Chatbot.git
cd Mern_Ai_Chatbot
```

### 2. Setup Backend
```bash
cd backend
npm install
# Create a .env file
touch .env
# Add your OpenAI API key
OPENAI_API_KEY=your_api_key_here
npm start
```

### 3. Setup Frontend
```bash
cd ../frontend
npm install
npm run dev
```

---

## 📸 Screenshots

| Chat UI                             | Backend API Test                  |
|------------------------------------|-----------------------------------|
| ![Chat UI](screenshots/chat_ui.png) | ![API](screenshots/backend_api.png) |

*(Replace with actual images in a `/screenshots` folder)*

---

## 📦 Folder Structure
```
Mern_Ai_Chatbot/
├── backend/         # Node.js + Express API
├── frontend/        # React UI
├── .gitignore
├── README.md
```

---

## 📄 License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📬 Contact
**Atharva Gharge**  
📧 atharva.g2022@vitstudent.ac.in  
🌐 [GitHub Profile](https://github.com/Atharvagharge)