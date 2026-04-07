# 🚀 React + Vite Starter Template

This project is a minimal and fast setup for building React applications using **Vite** with **Hot Module Replacement (HMR)** and basic **ESLint** configuration.

## ⚡ Features

* ⚛️ React (with modern hooks support)
* ⚡ Vite for lightning-fast builds and dev server
* 🔥 Hot Module Replacement (HMR)
* 🧹 ESLint for code quality
* 📦 Optimized production build

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone <your-repo-url>
cd <project-folder>
npm install
```

## 🧑‍💻 Development

Start the development server:

```bash
npm run dev
```

Then open:

```
http://localhost:5173
```

## 🏗️ Build for Production

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

## 🔌 Available Plugins

You can choose between two official React plugins for Vite:

### 1️⃣ Babel-based Plugin

* Package: `@vitejs/plugin-react`
* Uses **Babel**
* Recommended for compatibility and ecosystem support

### 2️⃣ SWC-based Plugin

* Package: `@vitejs/plugin-react-swc`
* Uses **SWC (Rust-based)**
* Faster builds and refresh times

👉 To switch plugins, update your `vite.config.js`:

```js
// Babel version
import react from '@vitejs/plugin-react'

// SWC version
import react from '@vitejs/plugin-react-swc'
```
## 📁 Project Structure

```
├── public/
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── main.jsx
├── index.html
├── package.json
├── vite.config.js
```

## 🧹 ESLint Setup

To maintain clean and consistent code:

```bash
npm run lint
```

You can customize rules in:

```
.eslintrc.cjs / .eslintrc.js
```

## 🚀 Best Practices

* Use **functional components + hooks**
* Keep components small and reusable
* Use **environment variables** via `.env`
* Enable **strict mode** in development

---

## 📚 Learn More

* [Vite Documentation](https://vitejs.dev/)
* [React Documentation](https://react.dev/)

---

## 🤝 Contributing

Pull requests are welcome! Feel free to fork and improve.

---

## 📄 License

This project is open-source and available under the **MIT License**.
