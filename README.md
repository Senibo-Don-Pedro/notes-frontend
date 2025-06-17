# 🧠 Notes App — Frontend

A sleek and intuitive **React** interface that powers a cloud-based note-taking experience. Designed for simplicity and performance, it offers real-time note listing, creation, editing, and deletion with a responsive layout suited for mobile and desktop. The frontend communicates with the Spring Boot backend via RESTful APIs and follows modern development standards for seamless integration.

### ✨ Highlights
- Clean, responsive UI built with React hooks and functional components
- Live CRUD operations powered by Axios
- Extensible architecture with environment-driven API configuration
- Perfect for deploying to Vercel, Netlify, or any static hosting platform

🌐 **[View Live Demo](https://notes-application-frontend-9e75.onrender.com/)**

---

## 🔧 Prerequisites
- [Node.js](https://nodejs.org/) v14 or higher
- Internet access to the backend API

---

## 🛠️ Setup & Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Senibo-Don-Pedro/notes-frontend.git
   cd notes-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment**
   Create a `.env.local` file:
   ```ini
   REACT_APP_API_URL=https://notes-backend-deployment-latest.onrender.com/
   ```

4. **Start the dev server**
   ```bash
   npm start
   ```
   
   Visit http://localhost:3000 to view the app.

---

## 📦 Build & Deploy
To generate a production build:

```bash
npm run build
```

Deploy the `build/` directory to any static hosting provider (e.g., Vercel, Netlify).

---

## 🗂️ Project Structure
```
src/
├── components/   # Reusable UI components (NoteList, NoteForm)
├── pages/        # Application view components
├── services/     # Axios API modules
├── App.js        # Main app component
└── index.js      # Entry point
```

---

## 🚀 Tech Stack
- React
- Axios
- Create React App

---

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests. For major changes, please start a discussion via an issue first.

---

## 👤 Author
**Senibo Don‑Pedro**  
[Connect on LinkedIn](https://linkedin.com/in/senibo-don-pedro)

---

## 📄 License
MIT © 2025 Senibo Don‑Pedro