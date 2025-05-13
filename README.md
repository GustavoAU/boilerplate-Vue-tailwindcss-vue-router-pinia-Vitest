# <h1>✨ Vue Boilerplate ✨</h1>

<div align="center">
<a href="https://vuejs.org/" target="blank" style="margin: 0 1rem;"><img src="https://router.vuejs.org/logo.svg" width="80" alt="Vue Logo" /></a>
<a href="https://www.typescriptlang.org/" target="blank" style="margin: 0 1rem;"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/1024px-Typescript_logo_2020.svg.png?20210506173343" width="80" alt="Typescript Logo" /></a>
<a href="https://vitejs.dev/" target="blank" style="margin: 0 1rem;"><img src="https://vitejs.dev/logo.svg" width="80" alt="Vite Logo" /></a>
<a href="https://pinia.vuejs.org/" target="blank" style="margin: 0 1rem;"><img src="https://pinia.vuejs.org/logo.svg" width="50" alt="Pinia Logo" /></a>
<a href="https://tailwindcss.com/" target="blank" style="margin: 0 1rem;"><img src="https://tailwindcss.com/_next/static/media/tailwindcss-mark.d52e9897.svg" width="90" alt="Tailwind CSS Logo" /></a>

<br><br>


</div>

The boilerplate of Vue v3, Typescript, Vite, Vue Router, Pinia, Tailwind CSS, and Playwright for building efficient, maintainable, and scalable enterprise applications.

### 📚 Table of Contents

- [❓ What's Included?](#-whats-included)
- [🖇️ Core Dependencies](#️-core-dependencies)
- [🗂️ Project Structure](#️-project-structure)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [💡 Scripts](#-scripts)
- [📝 License](#-license)

## ❓ What's Included?

- [x] TypeScript support for better development experience.
- [x] Pinia for state management.
- [x] Tailwind CSS for styling.
- [x] Playwright for end-to-end testing.
- [x] ESLint and Prettier for code formatting and linting.
- [x] Vite for fast development and build tooling.

## 🖇️ Core Dependencies

[&#8593; Back to top](#-table-of-contents)

| Library      | Version                                                         | Description                       |
| ------------ | --------------------------------------------------------------- | --------------------------------- |
| Vue          | ![Vue](https://img.shields.io/badge/%5E3.5.13-blue.svg)         | Progressive JavaScript framework. |
| Vite         | ![Vite](https://img.shields.io/badge/%5E6.2.4-blue.svg)         | Fast frontend build tooling.      |
| Typescript   | ![Typescript](https://img.shields.io/badge/%5E5.8.0-blue.svg)   | Static typing for JavaScript.     |
| Vue Router   | ![Vue Router](https://img.shields.io/badge/%5E4.5.0-blue.svg)   | Official router for Vue.js.       |
| Pinia        | ![Pinia](https://img.shields.io/badge/%5E3.0.1-blue.svg)        | State management for Vue.js.      |
| Tailwind CSS | ![Tailwind CSS](https://img.shields.io/badge/%5E4.1.6-blue.svg) | Utility-first CSS framework.      |
| Playwright   | ![Playwright](https://img.shields.io/badge/%5E1.51.1-blue.svg)  | End-to-end testing framework.     |

## 🚀 Getting Started

### Prerequisites

[&#8593; Back to top](#-table-of-contents)

1. [Node.js](https://nodejs.org/en/) version `v20+`.
2. [Visual Studio Code](https://code.visualstudio.com/download).

   **Recommended Plugins for VSCode**

   - [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
   - [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
   - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
   - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

### Installation

[&#8593; Back to top](#-table-of-contents)

1. Clone this repository:

   ```sh
   git clone https://github.com/GustavoAU/boilerplate-Vue-tailwindcss-vue-router-pinia-Vitest.git
   ```

2. Install dependencies:

   ```sh
   pnpm install
   ```

3. Start development server:

   ```sh
   pnpm dev
   ```

4. Build for production:

   ```sh
   pnpm build
   ```

## 💡 Scripts

[&#8593; Back to top](#-table-of-contents)

| Script           | Action                                                    |
| ---------------- | --------------------------------------------------------- |
| `pnpm install`   | Installs dependencies.                                    |
| `pnpm dev`       | Runs the development server.                              |
| `pnpm build`     | Builds the production-ready bundle.                       |
| `pnpm preview`   | Starts the preview server using Vite.                     |
| `pnpm lint`      | Runs ESLint to lint the project files and fix any issues. |
| `pnpm format`    | Formats the source code using Prettier.                   |
| `pnpm test:unit` | Runs unit tests using Vitest.                             |
| `pnpm test:e2e`  | Runs end-to-end tests using Playwright.                   |
