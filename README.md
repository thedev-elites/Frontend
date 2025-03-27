# CareerWise - Frontend

![CareerWise Logo](public/logo.png)

A modern, responsive web application built with React, TypeScript, and Shadcn UI.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
    - [Method 1: Cloning the Repository](#method-1-cloning-the-repository)
    - [Method 2: Downloading ZIP File](#method-2-downloading-zip-file)
  - [Development](#development)
  - [Building for Production](#building-for-production)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## 🌟 Project Overview

CareerWise is a frontend application designed to help users navigate their career paths. This application provides a user-friendly interface with modern design principles and responsive layouts.

## ✨ Features

- Responsive design for mobile, tablet, and desktop
- Light and dark theme support
- Modern UI with Shadcn UI components
- Type-safe development with TypeScript
- Fast development experience with Vite

## 🔧 Technologies

This project is built using the following technologies:

- **React** - UI library
- **TypeScript** - Static type checking
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn UI** - Component library built with Radix UI and Tailwind
- **React Router** - Routing library
- **React Query** - Data fetching library
- **Zod** - Schema validation
- **React Hook Form** - Form handling

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v18 or newer)
  - To check if you have Node.js installed, run `node -v` in your terminal
  - If not installed, download and install from the official website
- [npm](https://www.npmjs.com/) (v8 or newer) or [Yarn](https://yarnpkg.com/) (v1.22 or newer) or [Bun](https://bun.sh/) (latest version)
  - npm comes with Node.js, to check version run `npm -v`
  - For Yarn: `yarn -v`
  - For Bun: `bun -v`

### Installation

You can set up this project in two ways:

#### Method 1: Cloning the Repository

1. Open your terminal or command prompt
2. Clone the repository:

```bash
git clone https://github.com/yourusername/careerwise.git
```

3. Navigate to the project directory:

```bash
cd careerwise
```

4. Install the dependencies:

Using npm:
```bash
npm install
```

Using yarn:
```bash
yarn install
```

Using bun:
```bash
bun install
```

#### Method 2: Downloading ZIP File

1. Go to the GitHub repository page
2. Click on the "Code" button and select "Download ZIP"
3. Extract the ZIP file to your desired location
4. Open your terminal or command prompt
5. Navigate to the extracted folder:

```bash
cd path/to/careerwise-main
```

6. Install the dependencies:

Using npm:
```bash
npm install
```

Using yarn:
```bash
yarn install
```

Using bun:
```bash
bun install
```

> ⚠️ **Important**: The `npm install` (or yarn/bun install) step is crucial and must be completed before starting the development server. This command downloads and installs all the necessary node modules required by the project.

### Development

To start the development server:

1. Make sure you're in the project directory
2. Run one of the following commands:

Using npm:
```bash
npm run dev
```

Using yarn:
```bash
yarn dev
```

Using bun:
```bash
bun dev
```

3. Open your browser and navigate to `http://localhost:5173`
4. The development server features hot-reloading, so any changes you make to the code will automatically refresh the browser

### Building for Production

To build the application for production:

Using npm:
```bash
npm run build
```

Using yarn:
```bash
yarn build
```

Using bun:
```bash
bun run build
```

This will create a `dist` folder with optimized production files.

To preview the production build locally:

Using npm:
```bash
npm run preview
```

Using yarn:
```bash
yarn preview
```

Using bun:
```bash
bun run preview
```

## 📁 Project Structure

```
careerwise/
├── public/              # Static assets
├── src/                 # Source code
│   ├── components/      # Reusable UI components
│   ├── contexts/        # React contexts for state management
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Utility functions and configurations
│   ├── pages/           # Page components
│   ├── services/        # API service functions
│   ├── App.tsx          # Main application component
│   ├── App.css          # Global CSS
│   ├── index.css        # Tailwind CSS entry point
│   └── main.tsx         # Application entry point
├── .gitignore           # Git ignore file
├── components.json      # Shadcn UI component configuration
├── index.html           # HTML entry point
├── package.json         # Project dependencies and scripts
├── postcss.config.js    # PostCSS configuration
├── tailwind.config.ts   # Tailwind CSS configuration
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite configuration
```

## 🎨 Customization

### Themes

This project uses a theme system which can be customized in the `src/lib/theme.ts` file. To add or modify themes, update the respective theme files.

### Components

All UI components are built using Shadcn UI. You can customize or add new components by following the [Shadcn UI documentation](https://ui.shadcn.com/docs).

### Styling

This project uses Tailwind CSS for styling. You can customize the Tailwind configuration in the `tailwind.config.ts` file.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details. 

