# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

for creating a vite project

`npm create vite@latest`
`cd project name`
`npm i`

run project
`npm run dev`

Install Tailwind CSS

`npm install -D tailwindcss postcss autoprefixer`
`npx tailwindcss init -p`

Configure your template paths in tailwind.config.js

  `content: [`
    `"./index.html",`
    `"./src/**/*.{js,ts,jsx,tsx}",`
  `]`

  Add the Tailwind directives to your CSS in index.css

`@tailwind base;`
`@tailwind components;`
`@tailwind utilities;`