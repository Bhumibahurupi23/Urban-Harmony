# 🏙️ SmartCityGen – An Explainable AI-Based Smart City Planning Simulator

## HackNexus 2.0 | Team Project Repository

---

## 📌 Project Information

- **Team Name:** CodeCrafters  
- **Project Title:** SmartCityGen – An Explainable AI-Based Smart City Planning Simulator  
- **Track / Theme:** Smart Cities & Infrastructure Optimization  

---

## 🧠 Project Overview

**SmartCityGen** is a web-based smart city planning simulator designed to help users **visualize, experiment with, and understand urban layouts** through interactive 3D simulations.

The platform enables planners, students, and stakeholders to:
- Visualize city infrastructure in a 3D environment
- Explore “what-if” planning scenarios
- Understand the impact of zoning, green spaces, and infrastructure design
- Bridge the gap between human decision-making and AI-assisted insights

The current version is a **frontend-focused prototype**, architected for seamless integration with AI services and backend systems in future iterations.

---

## ✨ Key Features

- 🏙️ Modular 3D city visualization (buildings, roads, water bodies, green spaces)
- 🎛️ Interactive control panel for city configuration
- 🧠 AI Explanation Panel (UI-ready for explainable AI integration)
- 🎨 Modern, responsive dashboard UI
- ⚡ Fast performance using Vite
- 🧪 Test-ready structure with Vitest

---

## 🛠️ Technical Stack

### Frontend
- **React 18** – Component-based UI development  
- **TypeScript** – Static type safety  
- **Vite** – Fast development server and bundler  
- **Tailwind CSS** – Utility-first styling  
- **shadcn/ui (Radix UI)** – Accessible, customizable UI components  
- **Three.js (React-based integration)** – 3D city rendering and simulation  

backend:
- Node.js / Express or FastAPI  
- AI-powered explainability services  

database:
- Supabase (PostgreSQL)

### Tools & Libraries
- ESLint – Code quality and linting  
- Vitest – Unit testing  
- PostCSS – Styling pipeline  

---

## 🧱 Project Structure
src/
├── components/
│ ├── city/ # 3D city and infrastructure components
│ ├── ui/ # Reusable UI components (shadcn/ui)
│ ├── ControlPanel.tsx
│ └── AIExplanationPanel.tsx
├── pages/ # Application pages
├── hooks/ # Custom React hooks
├── utils/ # City generation logic
├── types/ # TypeScript type definitions
├── App.tsx # Root component
└── main.tsx # Application entry point
