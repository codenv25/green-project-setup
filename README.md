# 🛒 Green: Grocery E-commerce Micro Frontend Application

A beginner-friendly grocery e-commerce application built using **micro frontends (MFEs)** with the powerful [single-spa](https://single-spa.js.org/) framework.

Green is the perfect starting point for developers looking to learn and implement modular frontend architectures with real-world features like routing, state management, authentication, and UI reuse.

---

## ✅ Prerequisites

Before getting started, ensure you're familiar with the following:

- ⚛️ [React](https://reactjs.org/) basics (components, hooks, state)
- 🎨 CSS fundamentals
- 🧩 Micro frontend architecture concepts
- 🔗 [single-spa](https://single-spa.js.org/) micro frontend framework basics

## 📦 Project Structure

```
├── auth-mfe
├── cart-mfe
├── category-mfe
├── home-mfe
├── root-mfe
├── ui-utility
├── store-utility
├── package.json
```

## 🚀 Getting Started

**1. Install Dependencies**

```bash
# From the root directory
npm install

# Then go into each microfrontend and utility package and install separately
cd root-mfe && npm install && cd ..
cd home-mfe && npm install && cd ..
cd category-mfe && npm install && cd ..
cd cart-mfe && npm install && cd ..
cd auth-mfe && npm install && cd ..
cd store-utility && npm install && cd ..
cd ui-utility && npm install && cd ..
```

**2. Run All Microfrontends**

To start all microfrontends at once, run the following command from the root directory:

```bash
npm run start:all
```

**3. View the Application**

Once all micro frontends are running, open your browser and navigate to:
```bash
http://localhost:9000
```
