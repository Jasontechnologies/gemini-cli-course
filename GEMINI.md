# Project Overview

This is a Nuxt.js v3 web application called "FoodSmash". It is built with Vue.js v3 and TypeScript. The purpose of this application is to allow users to find, share, and rate unique food combinations. It serves as a starter project for demonstrating the capabilities of the Gemini CLI.

The project uses `vitest` for testing and `lucide-vue-next` for icons.

## Building and Running

### Prerequisites

Node.js and npm are required to build and run this project.

### Installation

To install the project dependencies, run the following command in the root directory:

```bash
npm install
```

### Development Server

To run the application in development mode with hot-reloading, use:

```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

### Building for Production

To build the application for production, run:

```bash
npm run build
```

This will create a `.output` directory with the production-ready assets.

### Running Tests

To run the test suite, use the following command:

```bash
npm test
```

Tests are powered by `vitest` and `@nuxt/test-utils`.

## Development Conventions

### Project Structure

The application follows the standard Nuxt.js directory structure:

-   `app/`: Contains the main application files.
    -   `pages/`: Vue components that are mapped to routes.
    -   `assets/`: Un-compiled assets like CSS or fonts.
    -   `layouts/`: Layout components for different parts of the application.
-   `test/`: Contains all the tests.
-   `public/`: Static assets that are publicly accessible.
-   `nuxt.config.ts`: The main Nuxt.js configuration file.

### Coding Style

-   **Vue:** The project uses the Vue 3 Composition API with the `<script setup>` syntax.
-   **TypeScript:** The codebase is written in TypeScript.
-   **Testing:** Tests are located in the `test/` directory and are written using `vitest`. Component tests utilize `@nuxt/test-utils` and the `mountSuspended` utility.

### Key Commands Summary

-   **`npm run dev`**: Start the development server.
-   **`npm run build`**: Create a production build.
-   **`npm run generate`**: Generate a static site.
-   **`npm run preview`**: Preview the production build.
-   **`npm test`**: Run the test suite.
