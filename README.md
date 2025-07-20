<div align="center">
  <br />
    <a href="https://youtu.be/kt0FrkQgw8w" target="_blank">
      <img src="https://github.com/user-attachments/assets/2afc2dc3-f840-4d98-9378-f34acd7df173" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Three_JS-black?style=for-the-badge&logoColor=white&logo=threedotjs&color=000000" alt="three.js" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">A 3D Dev Portfolio</h3>



An interactive 3D developer portfolio built with **React**, **Three.js**, **React Three Fiber**, **Drei**, and **Leva**. This portfolio showcases projects, skills, and contact information in an engaging and animated 3D environment.

## 🚀 Tech Stack

- **React** – Frontend framework
- **Three.js** – 3D graphics engine
- **@react-three/fiber** – React renderer for Three.js
- **@react-three/drei** – Useful helpers for R3F
- **Leva** – GUI panel for debugging & live tweaking
- **React Responsive** – Media queries for responsiveness
- **EmailJS** – For contact form functionality

## 📸 Features

- 🌐 Responsive design
- 🌀 3D interactive models
- 🎮 Smooth camera and lighting animations
- 📬 Contact form with EmailJS
- ⚙️ Real-time tweaking with Leva debug panel
- 🌙 Dark theme & modern UI

## 📁 Project Structure

```bash
3d-portfolio/
├── public/
├── src/
│   ├── assets/              # Models, textures, icons
│   ├── components/          # React components
│   ├── pages/               # Routes/pages
│   ├── App.jsx
│   ├── main.jsx
├── .env                     # EmailJS keys (not pushed to GitHub)
├── README.md
🛠️ Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/SahilAkhtar0812/3d-portfolio.git
cd 3d-portfolio
Install dependencies

bash
Copy
Edit
npm install
Configure environment variables

Create a .env file in the root and add your EmailJS credentials:

env
Copy
Edit
REACT_APP_EMAILJS_USERID=your_user_id
REACT_APP_EMAILJS_TEMPLATEID=your_template_id
REACT_APP_EMAILJS_RECEIVERID=your_service_id
Don't forget to add .env to .gitignore to keep your secrets safe.

Run the app

bash
Copy
Edit
npm run dev
Then visit: http://localhost:5173

📬 Contact
Feel free to connect via the contact form on the portfolio or reach out on LinkedIn.
  
