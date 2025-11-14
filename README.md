# Medi-Bridge AI Platform 
> Bringing intelligent healthcare to users with a clean, modern, and responsive UI.

---

## 🚀 Overview  
The **Medi-Bridge AI Platform (Frontend)** is a fast, modern, and intuitive web interface built to deliver seamless access to AI-enhanced healthcare tools. Designed with performance, accessibility, and usability in mind, it ensures effortless interaction for patients, doctors, and admins.

---

## 🌟 Features  
- ⚡ **React + TypeScript + Vite** for high-performance development  
- 📱 **Fully responsive** design — mobile, tablet & desktop  
- 🔐 **Secure authentication & session handling**  
- 🤝 **Smooth backend integration** with APIs  
- 🎨 **Tailwind CSS** for modern visual design  
- 🚀 **Optimized UI** with reusable components  
- ⚙️ **Scalable architecture** ready for production & CI/CD  

---

## 🧱 Tech Stack  
| Category | Technology |
|---------|------------|
| Framework | React.js |
| Language | TypeScript |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| State / Context | React Context API / Custom hooks |
| Deployment | Vercel / Azure Static Web App |
| Code Quality | ESLint + Prettier |

---

## 📂 Project Structure  
frontend/
├─ public/ # Static assets
├─ src/
│ ├─ assets/ # Images, icons, fonts
│ ├─ components/ # Reusable UI components
│ ├─ pages/ # Page-level screens
│ ├─ hooks/ # Custom hooks
│ ├─ context/ # Global state management
│ ├─ services/ # API integration & utilities
│ ├─ styles/ # Global styles & config
│ └─ App.tsx # Main app entry
├─ package.json
├─ vite.config.ts
├─ tailwind.config.js
└─ tsconfig.json

## 🔧 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Arka056/Medi-Bridge-AI-Platform.git
cd Medi-Bridge-AI-Platform/frontend
```
### 2️⃣ Install Dependencies  
```bash
npm install
```
### 3️⃣ Environment Variables
Create .env file: 
```bash
VITE_API_BASE_URL=http://localhost:5000/api
VITE_AUTH_ENDPOINT=/auth
```
