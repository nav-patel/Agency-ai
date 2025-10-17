# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# Modern Agency Landing Page

## 🧭 Overview

This project is a **modern digital agency landing page** built using **React.js** and **Tailwind CSS**.  
It is designed to showcase a professional web presence for creative agencies or freelancers.  
The website includes essential sections such as **Home, Services, Portfolio, Team, and Contact**, all integrated with smooth animations, responsive design, and a dark/light mode toggle.  

The **Contact form** is fully functional and uses **Web3Forms API** to handle form submissions without a backend.  
All components are modular and reusable, making the codebase scalable and easy to maintain.

---

## 🛠️ Technologies Used

| Category | Technology |
|-----------|-------------|
| Frontend | React.js (Vite) |
| Styling | Tailwind CSS |
| Animations | Framer Motion |
| Notifications | React Hot Toast |
| Form Handling | Web3Forms API |
| Theme Management | Local Storage + Custom Hook |

---

## 📁 Folder Structure

```

src/
│
├── assets/              # Images, icons, and static assets
│
├── components/          # Reusable UI components
│   ├── Navbar.jsx
│   ├── Hero.jsx
│   ├── TrustedBy.jsx
│   ├── Services.jsx
│   ├── ServiceCard.jsx
│   ├── OurWork.jsx
│   ├── Teams.jsx
│   ├── ContactUs.jsx
│   ├── Footer.jsx
│   ├── Title.jsx
│   └── ThemeToggleBtn.jsx
│
├── App.jsx              # Main app entry file
└── main.jsx             # Renders App and mounts to DOM

````

---

## ⚙️ Installation and Setup

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/nav-patel/modern-agency-landing-page.git
````

### 2. Navigate to the Project Directory

```bash
cd modern-agency-landing-page
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Run the Development Server

```bash
npm run dev
```

The project will start locally (usually at):

```
http://localhost:5173
```

---

## 🔑 Configuration (Optional)

The **Contact Form** uses [Web3Forms](https://web3forms.com/) for submission.
Replace the default access key in `ContactUs.jsx` with your own key:

```js
formData.append("access_key", "your-web3forms-access-key");
```

You can get a free access key by signing up on Web3Forms.

---

## 📦 Build for Production

To create an optimized build for deployment:

```bash
npm run build
```

Then deploy the `dist` folder to **Vercel**, **Netlify**, or **GitHub Pages**.

---

## 🧱 Features

* Responsive and modern landing page layout
* Dark and Light theme with toggle button
* Framer Motion animations for smooth transitions
* Functional contact form (Web3Forms integration)
* Modular and reusable React components
* Toast notifications for user feedback
* Clean and minimal Tailwind CSS design

---

## 👨‍💻 Author

**Navdeep Patel**
Frontend Developer | MERN Stack Enthusiast



