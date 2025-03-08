# vue-simple-demo

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

# Vue Simple Demo

A simple Vue.js demonstration project with multiple components and page routing.

## Features

- Vue 3 with Vue Router
- Home, About, and Experts pages with different background colors
- Simple responsive design
- Navigation bar for easy page switching

## Project Setup

### Prerequisites

- Node.js (v14.0 or later recommended)
- npm or yarn
- Visual Studio Code (recommended)

### Installation Steps

1. Clone or download this repository to your local machine
2. Open the project folder in Visual Studio Code
3. Open a terminal in VSCode (Terminal > New Terminal)
4. Install dependencies:

```bash
npm install
```

5. Start the development server:

```bash
npm run serve
```

6. Open your browser and navigate to: `http://localhost:8080`

## Production Build

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` folder, which can be deployed to any static file server.

## Project Structure

- `src/App.vue` - Main application component with navigation
- `src/router/index.js` - Route definitions
- `src/views/` - Page components:
  - HomePage.vue - Yellow background
  - AboutPage.vue - Blue background
  - ExpertsPage.vue - Green background

## Client Demonstration

This project demonstrates:

1. Component-based architecture
2. Page routing without page reloads
3. Responsive design
4. Code organization
5. Easy maintenance and scalability

Vue.js allows for much more complex applications with state management, API integration, animations, and more sophisticated UI components.
