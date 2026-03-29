<div align="center">

```
███████╗████████╗██╗   ██╗██╗     ███████╗██╗   ██╗ █████╗ ██╗   ██╗██╗  ████████╗
██╔════╝╚══██╔══╝╚██╗ ██╔╝██║     ██╔════╝██║   ██║██╔══██╗██║   ██║██║  ╚══██╔══╝
███████╗   ██║    ╚████╔╝ ██║     █████╗  ██║   ██║███████║██║   ██║██║     ██║   
╚════██║   ██║     ╚██╔╝  ██║     ██╔══╝  ╚██╗ ██╔╝██╔══██║██║   ██║██║     ██║   
███████║   ██║      ██║   ███████╗███████╗ ╚████╔╝ ██║  ██║╚██████╔╝███████╗██║   
╚══════╝   ╚═╝      ╚═╝   ╚══════╝╚══════╝  ╚═══╝  ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝   
```

### *Your wardrobe. Curated. Digitized. Elevated.*

<br/>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square)

<br/>

[🚀 Live Demo](#) · [🐛 Report Bug](https://github.com/your-username/stylevault/issues) · [✨ Request Feature](https://github.com/your-username/stylevault/issues)

</div>

---

<br/>

## 🌟 What is StyleVault?

> Ever stood in front of your wardrobe thinking *"I have nothing to wear"* — with a closet full of clothes?

**StyleVault** solves that. It's a full-stack wardrobe management app that lets you digitize every clothing item you own, create outfit combinations, and finally take control of your personal style.

<br/>

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📷 Upload    →    👗 Organize    →    ✨ Style            │
│                                                             │
│   Snap your       Tag by type,        Mix & match          │
│   clothes         color & season      saved outfits         │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

<br/>

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 📷 **Photo Upload** | Upload images of every clothing item in your wardrobe |
| 🗂️ **Smart Organization** | Categorize by type, color, season, and occasion |
| 👗 **Outfit Builder** | Mix and match items to create and save complete outfits |
| 🔐 **Secure Auth** | JWT-powered authentication via Supabase |
| ☁️ **Cloud Storage** | All images and data stored securely in the cloud |
| 📱 **Responsive Design** | Looks stunning on desktop, tablet, and mobile |
| ⚡ **Blazing Fast** | Built with Vite for lightning-quick load times |

<br/>

---

## 🛠️ Tech Stack

<div align="center">

```
╔══════════════════╦═══════════════════════════════════════╗
║    LAYER         ║    TECHNOLOGY                         ║
╠══════════════════╬═══════════════════════════════════════╣
║  🎨 Frontend     ║  React 18 + Vite                      ║
║  ⚙️  Backend      ║  Node.js + Express                    ║
║  🗄️  Database     ║  Supabase (PostgreSQL)                ║
║  🔐 Auth         ║  Supabase Auth + JWT Middleware        ║
║  🖼️  File Upload  ║  Multer + Supabase Storage            ║
║  🧹 Linting      ║  ESLint                               ║
╚══════════════════╩═══════════════════════════════════════╝
```

</div>

<br/>

---

## 📁 Project Structure

```
👗 stylevault/
│
├── 🖥️  backend/
│   └── src/
│       ├── 🔒 middleware/
│       │   └── auth.js           ← JWT token verification
│       ├── 🛣️  routes/
│       │   ├── auth.js           ← Register, login, session
│       │   ├── outfits.js        ← Create & manage outfits
│       │   ├── upload.js         ← Image upload handler
│       │   └── wardrobe.js       ← Clothing item CRUD
│       ├── index.js              ← Express entry point
│       └── supabase.js           ← Supabase client setup
│   ├── .env.example              ← Environment variable template
│   ├── schema.sql                ← Full database schema
│   └── package.json
│
├── 🎨 frontend/
│   ├── src/                      ← React components & pages
│   ├── public/
│   │   ├── favicon.svg
│   │   └── icons.svg
│   ├── index.html
│   ├── vite.config.js
│   └── package.json
│
├── 📄 DEPLOY.md                  ← Deployment guide
├── 📄 README.md                  ← You are here!
└── 🔧 eslint.config.js
```

<br/>

---

## 🚀 Quick Start

### Prerequisites

Before you begin, make sure you have:

- ![Node](https://img.shields.io/badge/Node.js-v18+-339933?style=flat-square&logo=nodedotjs&logoColor=white) installed
- A [Supabase](https://supabase.com) account (free tier works great!)
- ![npm](https://img.shields.io/badge/npm-v9+-CB3837?style=flat-square&logo=npm) or Yarn

<br/>

### Step 1 — Clone the repo

```bash
git clone https://github.com/your-username/stylevault.git
cd stylevault
```

### Step 2 — Set up the database

1. Open your [Supabase Dashboard](https://app.supabase.com)
2. Go to **SQL Editor**
3. Paste and run the contents of `backend/schema.sql`

> 💡 This creates all required tables: `wardrobe_items`, `outfits`, and more.

### Step 3 — Configure environment variables

```bash
cd backend
cp .env.example .env
```

Fill in your `.env`:

```env
# Server
PORT=5000

# Supabase
SUPABASE_URL=https://your-project.supabase.co
SUPABASE_ANON_KEY=your-anon-key-here
SUPABASE_SERVICE_ROLE_KEY=your-service-role-key-here

# Auth
JWT_SECRET=your-super-secret-jwt-key
```

> ⚠️ **Never** push your `.env` to GitHub. It's already in `.gitignore`.

### Step 4 — Start the backend

```bash
cd backend
npm install
npm run dev
# 🟢 Running on http://localhost:5000
```

### Step 5 — Start the frontend

```bash
cd frontend
npm install
npm run dev
# 🎨 Running on http://localhost:5173
```

**That's it! Open `http://localhost:5173` and start styling. 🎉**

<br/>

---

## 🔌 API Reference

### 🔐 Authentication `/api/auth`

```
POST   /api/auth/register    →  Create a new account
POST   /api/auth/login       →  Login & get JWT token
GET    /api/auth/me          →  Get current user profile
```

### 👕 Wardrobe `/api/wardrobe`

```
GET    /api/wardrobe         →  Fetch all clothing items
POST   /api/wardrobe         →  Add a new item
PUT    /api/wardrobe/:id     →  Update an item
DELETE /api/wardrobe/:id     →  Remove an item
```

### 👗 Outfits `/api/outfits`

```
GET    /api/outfits          →  Fetch all saved outfits
POST   /api/outfits          →  Create a new outfit
PUT    /api/outfits/:id      →  Update an outfit
DELETE /api/outfits/:id      →  Delete an outfit
```

### 📷 Upload `/api/upload`

```
POST   /api/upload           →  Upload a clothing image
```

> 🔑 All routes except `/auth/register` and `/auth/login` require:
> ```
> Authorization: Bearer <your_jwt_token>
> ```

<br/>

---

## 📜 Available Scripts

### Backend
```bash
npm run dev      # 🔄 Start with hot-reload (nodemon)
npm start        # 🚀 Start in production mode
```

### Frontend
```bash
npm run dev      # ⚡ Start Vite dev server
npm run build    # 📦 Build for production
npm run preview  # 👀 Preview production build
npm run lint     # 🧹 Run ESLint checks
```

<br/>

---

## 🌐 Deployment

Full deployment instructions are in **[`DEPLOY.md`](./DEPLOY.md)**, including:

- 🚂 **Backend** → Railway / Render / Fly.io
- ▲ **Frontend** → Vercel / Netlify
- 🔧 **Environment** → Production env variables setup
- 🪣 **Storage** → Supabase Storage bucket configuration

<br/>

---

## 🤝 Contributing

Contributions are what make the open source community amazing. Any contributions you make are **greatly appreciated**!

```
1. 🍴  Fork the project
2. 🌿  Create your branch   →  git checkout -b feature/AmazingFeature
3. 💾  Commit your changes  →  git commit -m 'Add: some AmazingFeature'
4. 📤  Push to the branch   →  git push origin feature/AmazingFeature
5. 🔁  Open a Pull Request
```

<br/>

---

## 📄 License

Distributed under the **MIT License**.
See [`LICENSE`](./LICENSE) for more information.

<br/>

---

<div align="center">

**Built with passion for fashion & clean code** 👗⚡

*If you found this useful, please consider giving it a* ⭐

<br/>

[![GitHub stars](https://img.shields.io/github/stars/your-username/stylevault?style=social)](https://github.com/your-username/stylevault)
[![GitHub forks](https://img.shields.io/github/forks/your-username/stylevault?style=social)](https://github.com/your-username/stylevault)

</div>
