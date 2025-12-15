````md
# 🛒 E-Commerce Gen-AI

An **AI-powered e-commerce platform** that uses **Generative AI** to enhance product discovery, recommendations, and user experience using **OpenAI**, **Qdrant**, and **React**.

---

## 🚀 Features
- AI-based product recommendations
- Semantic product search
- Smart chatbot for shopping assistance
- React-based responsive UI
- Vector search with Qdrant

---

## 🛠️ Tech Stack
- **Frontend:** React
- **Backend:** Node.js (Express)
- **AI:** OpenAI API
- **Vector DB:** Qdrant

---

## ⚙️ Setup

### Backend
```bash
cd server
npm install
npm start
````

`.env`

```env
OPENAI_API_KEY=your_key
QDRANT_URL=http://localhost:6333
```

### Qdrant

```bash
docker run -p 6333:6333 qdrant/qdrant
```

### Frontend

```bash
cd client
npm install
npm start
```

