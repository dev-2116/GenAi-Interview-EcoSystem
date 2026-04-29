# 🚀 GenAi-Interview-EcoSystem

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-blue)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-lightgrey)

**GenAi-Interview-EcoSystem** is an intelligent, AI-powered interview preparation platform. It analyzes a candidate's resume against a target job description to generate highly tailored interview strategies, technical/behavioral questions, match scores, and a day-by-day preparation roadmap.

---

## ✨ Features

- 🧠 **AI-Powered Analysis**: Generates comprehensive interview plans using Generative AI based on your specific resume and target job description.
- 🎯 **Match Scoring & Skill Gaps**: Instantly calculates how well your resume matches the job description and highlights critical skill gaps.
- 💻 **Technical & Behavioral Questions**: Provides custom interview questions categorized by technical skills and behavioral traits, complete with intentions and model answers.
- 🗺️ **Preparation Roadmap**: Generates a structured, day-by-day preparation roadmap to help you close skill gaps before the interview.
- 📄 **Resume Integration**: Seamlessly upload and process your resume.
- 📊 **Beautiful Dashboard**: A responsive, modern React UI to track all your recent interview plans and scores.

---

## 🛠️ Tech Stack

### **Frontend**
- **React.js** (via Vite)
- **React Router** for navigation
- **SCSS** for modern, responsive styling
- Custom hooks (`useInterview`) for state management

### **Backend**
- **Node.js & Express** 
- **MongoDB Atlas** with Mongoose for data persistence
- **Generative AI Integration** (Processing resumes & generating personalized feedback)

---

## ⚙️ Prerequisites

Before you begin, ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/en/) (v16 or higher recommended)
- [Git](https://git-scm.com/)
- A MongoDB Atlas account and Cluster URI
- API keys for the Generative AI service used in the backend

---

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/dev-2116/GenAi-Interview-EcoSystem.git
   cd GenAi-Interview-EcoSystem
   ```

2. **Backend Setup**
   ```bash
   cd Backend
   npm install
   ```
   - Create a `.env` file in the `Backend` directory and add your environment variables:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_atlas_connection_string
     AI_API_KEY=your_gen_ai_api_key
     ```
   - Start the backend server:
     ```bash
     npm run dev
     ```

3. **Frontend Setup**
   ```bash
   cd ../Frontend
   npm install
   ```
   - Start the React development server:
     ```bash
     npm run dev
     ```

---

## 💡 Usage

1. Open your browser and navigate to `http://localhost:5173` (or the port Vite provides).
2. Enter the **Job Description** and your **Self Description**.
3. Upload your **Resume** (PDF).
4. Click **"Generate My Interview Strategy"**.
5. The AI will analyze your inputs and redirect you to a personalized interview preparation dashboard!

---

## 📁 Folder Structure

```text
GenAi-Interview-EcoSystem/
├── Backend/                 # Express.js server, AI logic, MongoDB schemas
│   ├── src/
│   ├── .env
│   └── package.json
├── Frontend/                # React Vite Application
│   ├── src/
│   │   ├── features/        # Feature-based architecture (e.g., interview pages)
│   │   ├── hooks/           # Custom React hooks (useInterview.js)
│   │   ├── style/           # SCSS stylesheets
│   │   └── App.jsx
│   └── package.json
└── README.md                # Project documentation
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check the [issues page](https://github.com/dev-2116/GenAi-Interview-EcoSystem/issues) if you want to contribute.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
