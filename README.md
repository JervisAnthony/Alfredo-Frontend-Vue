# Alfredo Frontend Vue

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Build for Production](#build-for-production)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Introduction

**Alfredo Frontend Vue** is the collaborative editor interface of the Alfredo app, developed using **Vue.js**. It provides a rich-text editing experience with real-time collaboration powered by **Socket.IO**. The application manages state with **Vuex** and communicates with the backend API using **Axios**.

---

## Features

- **Real-Time Collaboration**
  - Simultaneous editing with live updates.
  - Changes are synchronized across all connected clients.
- **Rich Text Editing**
  - Text formatting, images, and attachments.
  - Built using **Quill Editor**.
- **User Authentication**
  - Secure login and registration.
  - JWT token management.
- **State Management**
  - Centralized state using **Vuex**.
- **Responsive Design**
  - Mobile-friendly and responsive UI.
- **Routing**
  - SPA navigation with **Vue Router**.

---

## Screenshots

*(Include screenshots or GIFs of your application here to showcase the UI and features.)*

---

## Technologies Used

- **Vue.js 3**: Progressive JavaScript framework.
- **Vuex**: State management pattern + library.
- **Vue Router**: Routing for SPA navigation.
- **Axios**: Promise-based HTTP client.
- **Socket.IO Client**: Enables real-time communication with the backend.
- **Quill Editor**: Rich text editor component.
- **ESLint** and **Prettier**: For code linting and formatting.

---

## Project Structure

```
alfredo-frontend-vue/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── router/
│   ├── store/
│   ├── views/
│   ├── App.vue
│   ├── main.js
│   └── socket.js
├── .env
├── package.json
└── README.md
```

---

## Prerequisites

- **Node.js** (v14 or higher)
- **npm** (v6 or higher)

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/JervisAnthony/alfredo-frontend-vue.git
   cd alfredo-frontend-vue
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

---

## Configuration

1. **Create a `.env` file** in the root directory.

   ```bash
   touch .env
   ```

2. **Add the following environment variables to `.env`**

   ```env
   VUE_APP_BACKEND_URL=http://localhost:5000
   ```

   - Replace the URL with your backend server address if different.

---

## Running the Application

### Development Mode

Start the development server with hot reloading.

```bash
npm run serve
```

The app will be available at `http://localhost:8080` by default.

---

## Build for Production

Compile and minify the app for production deployment.

```bash
npm run build
```

The compiled files will be located in the `dist/` directory.

---

## Testing

### Unit Tests

Run unit tests using **Jest**.

```bash
npm run test:unit
```

### End-to-End Tests

Run end-to-end tests using **Cypress**.

```bash
npm run test:e2e
```

---

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix.
3. **Commit your changes** with descriptive messages.
4. **Push to your fork** and submit a **pull request**.

Please ensure all pull requests are accompanied by appropriate tests.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Contact

- **Author**: Jervis Anthony
- **GitHub**: [JervisAnthony](https://github.com/JervisAnthony)
- **Email**: [jervisaldanha.collabs@gmail.com](mailto:jervisaldanha.collabs@gmail.com)

---
