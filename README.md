# React Webpack From Scratch

A minimal React application built from scratch using Webpack, demonstrating how to set up a React project without Create React App.

## Features

- React 19
- Webpack 5
- Babel 7
- Hot Module Replacement
- CSS Support
- Development & Production builds

## Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/kubaparol/react-webpack-from-scratch.git
cd react-webpack-from-scratch
```

2. Install dependencies:

```bash
npm install
```

3. Start development server:

```bash
npm start
```

The application will open automatically at `http://localhost:3000`.

## Available Scripts

- `npm start` - Starts development server
- `npm run build` - Creates production build in `dist` folder

## Project Structure

```
react-webpack-from-scratch/
├── public/
│   └── index.html
├── src/
│   ├── styles/
│   │   └── globals.css
│   ├── App.js
│   └── index.js
├── .babelrc
├── .gitignore
├── index.html
├── package.json
└── webpack.config.js
```

## Configuration

The project includes basic configuration for:

- Webpack
- Babel
- Development server
- CSS loading
- Production optimization
