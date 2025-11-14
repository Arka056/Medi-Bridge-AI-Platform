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
```bash
frontend/
├─ public/
├─ src/
│ ├─ assets/ 
│ ├─ components/ 
│ ├─ pages/ 
│ ├─ hooks/ 
│ ├─ context/ 
│ ├─ services/ 
│ ├─ styles/ 
│ └─ App.tsx 
├─ package.json
├─ vite.config.ts
├─ tailwind.config.js
└─ tsconfig.json
```
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
### 4️⃣ Start Development Server
```bash
npm run dev
```
### 5️⃣ Build for Production
```bash
npm run build
```
### 6️⃣ Preview Production Build
```bash
npm run preview
```
### 🧪 Code Quality
```bash
npm run lint       # Check linting issues
npm run format     # Auto-format code with Prettier
```

### 📈 Deployment

This frontend is ready for cloud deployment:

Vercel
* Auto-deploy on commit to main
* Add environment variables in the Vercel dashboard

Azure Static Web App
* Build command: npm run build
* Output folder: ```dist```

### 🎨 UI & UX Principles
✔ Clean layout with intuitive navigation

✔ Accessible color contrast & typography

✔ Mobile-first design approach

✔ Smooth transitions & meaningful loading states

✔ Modular components for easy expansion

### 🤝 Contributing

1. Fork the repository
2. Create a new branch  ```git checkout -b feature/my-feature```
3. Commit your changes
4. Push the branch
5. Create a Pull Request
   
We appreciate contributions that enhance performance, improve accessibility, or enhance the user experience!

### 📜 License

This project is licensed under the MIT License.

### 💬 Feedback
If you have suggestions or ideas to improve this UI, feel free to open an issue or share your thoughts.

### ⭐ Support
If you like this project, please ⭐ star the repository on GitHub — it motivates development!

Thank you for exploring the **Medi-Bridge AI Platform**!

Crafted with ❤️ for a **Smarter Healthcare** future.
