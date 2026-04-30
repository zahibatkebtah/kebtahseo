# Kebtah SEO

A React + Vite project for building fast, modern web applications.

## Installation

### Prerequisites
- Node.js (v16 or higher)
- npm (v7 or higher)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd kebtahseo
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

   > **Note:** This project uses Vite 4.x due to native binding compatibility on Windows. If you experience any issues, try a clean reinstall:
   > ```bash
   > rm -r node_modules package-lock.json
   > npm install
   > ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   
   The application will be available at `http://localhost:5173/`

## Available Scripts

- `npm run dev` - Start the development server with hot module reloading (HMR)
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## Project Overview

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
