# ✨ Interactive Developer Portfolio

Welcome to the source code for my personal portfolio website! This project is a showcase of my skills in modern web development, featuring a sleek design, engaging animations, and a fully interactive user experience. Built with React, Vite, and Tailwind CSS, and brought to life with Framer Motion and Three.js.

---

---
![Portfolio Showcase](https://i.imgur.com/YOUR_GIF_URL.gif)


## 🌟 Key Features

* **🎨 Sleek & Modern UI:** A clean, visually appealing design with a professional aesthetic.
* **🌓 Dark/Light Mode Toggle:** A seamless theme-switching experience that respects user preference and saves their choice.
* **🌌 Interactive 3D Background:** A captivating animated starfield background built with `Three.js` and `React Three Fiber`.
* **🎬 Smooth Animations:** Fluid page transitions and component animations powered by `Framer Motion`.
* **⏳ Dynamic Experience Timeline:** An interactive, scroll-animated timeline that highlights my professional journey. Details expand on hover (desktop) or tap (mobile).
* **🖼️ Project Showcase with Carousel:** A grid of my featured projects, each opening a detailed modal with a swipeable image carousel.
* **📨 Functional Contact Form:** A working contact form integrated with **EmailJS** that sends messages directly to my inbox and provides an auto-reply to the sender.
* **📱 Fully Responsive Design:** Meticulously crafted to look and work perfectly on all devices, from mobile phones to widescreen desktops.

---

## 🛠️ Tech Stack

This portfolio is built with a modern, performance-oriented tech stack:

| Category          | Technology                                                                                                                                                                                                                                                        |
| :---------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)                                                                   |
| **Styling** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)                                                                                                                                                 |
| **Animation** | ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)                                                                                                                                                   |
| **3D & Graphics** | ![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white) ![React Three Fiber](https://img.shields.io/badge/React_Three_Fiber-000000?style=for-the-badge)                                                            |
| **Email Service** | ![EmailJS](https://img.shields.io/badge/EmailJS-1F7F4C?style=for-the-badge)                                                                                                                                                                                          |
| **Deployment** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)                                                                                                                                                                 |

---

## 🚀 Getting Started

To run this project locally, follow these steps:

**1. Clone the repository:**

```bash
git clone 
cd Portfolio
```

**2. Install dependencies:**

```bash
npm install
```

**3. Set up environment variables:**
Create a .env file in the root of your project and add your EmailJS credentials. You can get these from your EmailJS account dashboard.
```Code snippet
VITE_EMAILJS_SERVICE_ID=YOUR_SERVICE_ID
VITE_EMAILJS_TEMPLATE_ID=YOUR_TEMPLATE_ID
VITE_EMAILJS_PUBLIC_KEY=YOUR_PUBLIC_KEY
```
**4. Run the development server:**
```bash
npm run dev
```
Open http://localhost:5173 (or the address shown in your terminal) to view the project in your browser.

---

## 📁 Project Structure

```
my-new-portfolio/
├── public/                 # Static public assets (favicon, manifest, etc.)
├── src/                    # Source files
│   ├── assets/             # Images, icons, and other media
│   ├── components/         # Reusable React components (Navbar, Cards, etc.)
│   ├── context/            # Global state/context (e.g., ThemeContext)
│   ├── data.js             # Centralized data for projects, skills, etc.
│   ├── App.jsx             # Main App component
│   └── main.jsx            # React entry point that renders <App />
├── .gitignore              # Git ignored files and folders
├── package.json            # Project dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
├── vite.config.js          # Vite build configuration
└── README.md               # Project overview and documentation
```

---

## 🌐 Deployment
This project is deployed on Vercel with continuous integration. Every push to the main branch automatically triggers a new build and deployment, ensuring the live site is always up-to-date with the latest changes.

---

## 🔗 Connect with Me

<p align="left">
  <a href="https://github.com/Resham011" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-%2312100E.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/resham011" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---


## 📝 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, share, or contribute with attribution.

---

