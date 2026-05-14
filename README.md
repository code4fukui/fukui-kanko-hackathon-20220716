# fukui-kanko-hackathon-20220716

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A front-end template created for the Fukui Tourism Hackathon on July 16, 2022. This project, featuring the "福クル" (Fuku-Kuru) logo, is built with Alpine.js and TypeScript, offering a fast development environment powered by Vite and Yarn v3.

## ✨ Features

-   **Modern Stack**: Alpine.js for lightweight reactivity, fully typed with TypeScript.
-   **Fast Development**: Vite for near-instant server start and Hot Module Replacement (HMR).
-   **Type-Safe Styling**: [vanilla-extract](https://vanilla-extract.style/) for writing CSS in TypeScript with zero runtime overhead.
-   **Efficient Package Management**: Yarn v3 for fast and reliable dependency management.
-   **Built-in Routing**: A simple hash-based router (`#home`, `#navi`, `#review`) implemented in `src/router.ts`.
-   **Testing & Linting**: Pre-configured with Vitest for testing and ESLint for code quality.

## 🛠️ Getting Started

### Prerequisites

-   Node.js v14+
-   Yarn v3.2.1+

### Installation & Usage

1.  **Install dependencies:**
    ```shell
    yarn
    ```

2.  **Run the development server:**
    ```shell
    yarn dev
    ```

## 📜 Available Scripts

-   `yarn dev`: Starts the Vite development server.
-   `yarn build`: Compiles TypeScript and builds the application for production.
-   `yarn preview`: Serves the production build locally for previewing.
-   `yarn test`: Runs tests using Vitest.

## 🔎 References

-   [Getting started with Alpine.js and TypeScript](https://dev.to/wtho/get-started-with-alpinejs-and-typescript-4dgf)
-   [Create your first Vite project](https://vitejs.dev/guide/#scaffolding-your-first-vite-project)
-   [The rise and fall of yarn and npm](https://blog.ikeryo1182.com/yarn-and-npm) (about yarn v3)
-   [Vitest - a surprisingly fast testing framework](https://sapper-blog-app.vercel.app/blog/testingframework-vitest)
-   [vanilla-extract](https://vanilla-extract.style/documentation/)

## License

MIT License — see [LICENSE](LICENSE).