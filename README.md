# 🎨 K72.ca Website Clone  

This project is **Front-end clone** of the official [K72.ca](https://k72.ca/) website, built for learning purposes.  
It replicates the **modern design, animations, and smooth interactions** of the original site using **React** and **GSAP**.  

⚠️ **Disclaimer:** This project is created **only for educational purposes** and is **not affiliated** with K72 in any way.  

---

## 📸 Demo Preview  

### 🏠 Home Page
<video autoplay muted loop src="Readme of K72\20250910-1651-27.5439102.mp4" title="home"></video>

### ⚒️ Projects Page
<video autoplay muted loop src="Readme of K72\20250910-1647-14.1266165.mp4" title="projets"></video>

### 🏢 Agence Page
<video autoplay muted loop src="Readme of K72\20250910-1642-34.1905830.mp4" title="agence"></video>

### 📰 Blog Page
<video autoplay muted loop src="Readme of K72\Recording 2025-09-11 205316.mp4" title="blogue"></video>


### 📧 Contact Page
<video autoplay muted loop src="Readme of K72\20250910-1654-59.3900190.mp4" title="contact"></video>

---

## 🛠️ Tech Stacks  

- **React.js** → Component-based UI  
- **Tailwind CSS** → Styling & responsive design  
- **GSAP + ScrollTrigger** → Animations & scroll effects  
- **Lenis** → Smooth scrolling  
- **Vite** → Development & bundling  

---

## 🚀 Features  

- Responsive layout (desktop, tablet, mobile)  
- Smooth scroll effects  
- Engaging GSAP animations  
- Pixel-perfect UI inspired by K72.ca  
- Clean and reusable React components  

---

## 📂 Project Structure  

```
K72.CA WEBSITE
│── src
│ ├── assets
│ │     ├──Fonts
│ │     └──Media
│ ├── Components
│ │     ├──blogue
│ │     │     └──Blgcont.jsx       
│ │     ├──Common
│ │     │     └──Stairs.jsx       
│ │     ├──contact
│ │     │     ├──ContactBottom.jsx       
│ │     │     └──ContactTop.jsx       
│ │     ├──home
│ │     │     ├──Homebottom.jsx       
│ │     │     ├──Hometop.jsx       
│ │     │     └──Video.jsx       
│ │     └──projets
│ │           └──ProjetCard.jsx       
│ ├── Context
│ │     └──NavContext.jsx
│ ├── Navigation
│ │     ├──FullScreenNav.jsx
│ │     └──Navbar.jsx
│ ├── Page
│ │     ├──Agence.jsx
│ │     ├──Blogue.jsx
│ │     ├──Contact.jsx
│ │     ├──Home.jsx
│ │     └──Projets.jsx
│ ├── App.jsx
│ ├── index.css
│ └── main.jsx
│── .gitignore
│── index.html
│── package-lock.json
│── package.json
│── tailwind.config.js
└── vite.config.js
```