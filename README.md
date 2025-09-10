# Mohammed Mohsin — Developer Portfolio

A personal portfolio website built with **Next.js (Pages Router)**, showcasing projects, skills, and experience. Powered by **Hygraph (GraphQL)** CMS.

---

## 📌 Overview

This repository contains a modern, GraphQL-powered portfolio built on a Next.js foundation. It is structured to be easily extensible, rich with visuals, and connected to an external CMS for dynamic content delivery.

---

## 🚀 Key Features

| Feature                  | Description |
|--------------------------|-------------|
|  **Next.js Framework**     | Built using the Pages Router with SSR, SSG, and API route support |
|  **GraphQL CMS Integration** | Uses Hygraph (GraphCMS) for content management |
|  **Dynamic Content**         | Projects and profile data are fetched via GraphQL |
|  **TypeScript**             | Fully typed for reliability and developer ergonomics |
|  **Tailwind CSS**           | For rapid, utility-first styling |
|  **API Routes**             | Custom endpoints via Next.js `pages/api` |
|  **Optimized for SEO**      | Semantic markup and metadata predefined |

---

## 🗂️ Project Structure

```
.
├── components/          # Reusable React components
├── graphqlOperations/   # GraphQL queries/mutations
├── hooks/               # Custom hooks for React data/state
├── pages/               # Next.js Pages Router entries
│   ├── api/             # Backend-like API endpoints
│   └── index.tsx        # Home page entry point
├── public/              # Static assets (images, favicon)
├── styles/              # Global/styled CSS utility files
├── apollo-client.ts     # Apollo setup for GraphQL
├── data.ts              # Local static data fallback
├── .env.example         # Sample environment variables
├── README.md            # This documentation
├── next.config.js       # Next.js configuration
├── package.json         # Dependencies and scripts
├── postcss.config.js    # PostCSS setup for Tailwind
├── tailwind.config.js   # Tailwind configuration
├── tsconfig.json        # TypeScript config
└── types.d.ts           # Custom type declarations
```

---

## ⚡ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/MohammedMohsin404/Mohammed-Mohsin.git
cd Mohammed-Mohsin
```

### 2. Set up environment
```bash
cp .env.example .env.local
# Fill in Hygraph URL and Auth Token
```

### 3. Install dependencies
```bash
yarn install
# or
npm install
```

### 4. Run in development mode
```bash
yarn dev
# or
npm run dev
```
Visit **http://localhost:3000** to view the site.

### 5. Build for production
```bash
yarn build
yarn start
```

---

## 🌐 Deploying

Deploy easily on **[Vercel](https://vercel.com/)**:

- Sign in with GitHub.
- Import your repository (`MohammedMohsin404/Mohammed-Mohsin`).
- Set your environment variables (Hygraph URL and Auth Token).
- Deploy—your portfolio will be live within minutes.

---

## 📬 Contact

- **LinkedIn**: [Your LinkedIn URL]  
- **Email**: [mohammedmohsin0725@gmail.com]  
- **GitHub**: [@MohammedMohsin404](https://github.com/MohammedMohsin404)

---

## 📜 License

This portfolio is open-source and shared under the **MIT License**. Feel free to adapt and customize it for your own uses.
