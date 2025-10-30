Une application de présentation liturgique tout-en-un pour les églises
Créez et présentez vos cultes professionnellement avec une seule application

=> Présentations Liturgiques
Lectures bibliques avec intégration API Bible
Chants et louanges avec paroles
Annonces et informations
Prières et ordres du culte
Templates catholique et protestant

# Cloner le projet
https://github.com/manambina9/ProjetMasina.git
cd ProjetMasina

# Installation des dépendances
npm install
composer install

# Développement
npm run dev          # Frontend Next.js
symfony server:start # Backend Symfony

# Build production
npm run build:all

ChurchPresenter/
├── 📁 servers/               # Serveurs intégrés
│   ├── 📁 php/              # PHP portable Windows
│   ├── 📁 node/             # Node.js portable
│   ├── 📁 symfony/          # API Backend
│   └── 📁 nextjs/           # Frontend React/Next.js
├── 📁 database/             # SQLite intégrée
├── 🚀 ChurchPresenter.exe   # Lanceur principal
└── 📖 README.md


This is a Next.js project bootstrapped with create-next-app.

Getting Started
First, run the development server:

npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
Open http://localhost:3000 with your browser to see the result.

You can start editing the page by modifying app/page.tsx. The page auto-updates as you edit the file.

This project uses next/font to automatically optimize and load Geist, a new font family for Vercel.

Learn More
To learn more about Next.js, take a look at the following resources:

Next.js Documentation - learn about Next.js features and API.
Learn Next.js - an interactive Next.js tutorial.
You can check out the Next.js GitHub repository - your feedback and contributions are welcome!

Deploy on Vercel
The easiest way to deploy your Next.js app is to use the Vercel Platform from the creators of Next.js.

Check out our Next.js deployment documentation for more details.
