# Lazy Cat React Demo

A lightweight and efficient starter project built with **Vite**, **TypeScript**, **SWC (Speedy Web Compiler)**, and **React.js**. This demo serves as a foundation for fast and modern web application development.

---

## Features

- **Vite**: Blazing-fast development and build tool.
- **TypeScript**: Type-safe development for robust applications.
- **SWC**: High-performance JavaScript/TypeScript compiler.
- **React.js**: Component-based UI library for building interactive interfaces.

---

## Getting Started

### Development

1. Launch the development shell:
   ```bash
   lzc-cli project devshell -f
   ```

2. Open another shell, install dependencies and start the development server:
   ```bash
   npm install
   npm run dev
   ```

The app will be available locally. Modify source files to see real-time updates with hot module replacement (HMR).

---

### Building for Production

1. Build the project using Lazy Cat CLI:
   ```bash
   lzc-cli project build -o release.lpk
   ```

2. Install the release package:
   ```bash
   lzc-cli app install release.lpk
   ```

Your application is now ready for deployment.

---

## Prerequisites

- Node.js (v16 or higher recommended)
- Lazy Cat CLI (`lzc-cli`)
- NPM (or Yarn as an alternative)

---

## Contribution

Feel free to submit issues or contribute via pull requests to improve this starter template.

---

## License

[MIT](LICENSE)