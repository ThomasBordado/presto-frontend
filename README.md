# Presto – Presentation Builder

A web application for creating, editing and presenting slide decks in the browser. Inspired by Slides.com, built with React and Vite.

**🌐 Live Demo:** https://presto-frontend-tb.vercel.app

![Presto Dashboard](https://via.placeholder.com/800x400?text=Add+Screenshot+Later)

---

## 🚀 Features

- **Authentication** - Register, login, and logout with session management
- **Dashboard** - View all your presentations with thumbnails and metadata
- **Presentation Editor** - Create and edit slides with drag-and-drop functionality
- **Rich Content** - Add text, images, videos, and code blocks to slides
- **Slide Management** - Reorder, duplicate, and delete slides
- **Presentation Mode** - Full-screen presentation with keyboard navigation
- **Responsive Design** - Works on desktop and tablet devices

---

## 🛠 Tech Stack

- **Frontend Framework:** React 18
- **Build Tool:** Vite
- **Routing:** React Router
- **Styling:** CSS Modules (no UI libraries - custom components)
- **HTTP Client:** Axios
- **Drag & Drop:** @dnd-kit, react-rnd
- **Animations:** Framer Motion
- **Testing:** Vitest, Cypress (E2E)

---

## 📁 Project Structure
```text
.
├── src/
│   ├── pages/          # Main page components (Dashboard, Editor, Preview)
│   ├── components/     # Reusable UI components (modals, cards, etc.)
│   ├── hooks/          # Custom React hooks
│   ├── App.jsx         # Main app component with routing
│   └── main.jsx        # Application entry point
├── public/             # Static assets
├── cypress/            # E2E tests
└── vite.config.js      # Vite configuration
```

---

## 🔧 Getting Started

### Prerequisites

- Node.js (LTS version recommended)
- npm or yarn

### 1. Install dependencies
```bash
npm install
```

### 2. Configure backend URL

Update `backend.config.json` with your backend URL:
```json
{
  "BACKEND_LOCAL": "http://localhost:5005",
  "BACKEND_URL": "https://presto-backend-kappa.vercel.app"
}
```

### 3. Start development server
```bash
npm run dev
```

Open http://localhost:5173 in your browser.

### 4. Build for production
```bash
npm run build
```

### 5. Run tests
```bash
# Unit tests
npm test

# E2E tests
npm run cypress
```

---

## 🧑‍💻 About This Project

This application was developed as a software engineering project at UNSW. I was responsible for the complete frontend implementation.

**Key technical contributions:**
- Built React SPA with client-side routing for authentication, dashboard, and editor
- Implemented drag-and-drop slide editor with real-time content updates
- Created custom modals and UI components without using component libraries
- Integrated REST API for authentication and presentation management
- Applied accessibility best practices (ARIA labels, keyboard navigation, semantic HTML)
- Comprehensive testing with Vitest for components and Cypress for E2E flows

---

## 🌐 Deployment

Deployed on Vercel with automatic deployments from the main branch.

**Live Site:** https://presto-frontend-tb.vercel.app
---

## 📸 Screenshots

*Add screenshots after deployment*

- Dashboard view
- Slide editor
- Presentation mode

---

## 🔗 Related

**Backend Repository:** https://github.com/ThomasBordado/presto-backend