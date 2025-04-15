# ⚛️ React TypeScript Webpack Starter

A modern, lightweight boilerplate for building high-performance **React** applications using **TypeScript** and **Webpack 5**. Designed for scalability, speed, and developer experience — this template gives you the essentials, no bloat.

---

## 📦 What's Included

- ✅ React 19 with JSX transform
- ✅ TypeScript support
- ✅ Babel 7
- ✅ Webpack 5 bundler
- ✅ Webpack Dev Server (v5) with HMR
- ✅ React Fast Refresh
- ✅ Sass/SCSS support
- ✅ Environment-based configs (development & production)
- ✅ Code splitting & content hashing for optimized builds
- ✅ Clean output with `clean-webpack-plugin`
- ✅ HTML template with `html-webpack-plugin`
- ✅ Source maps for both dev and prod
- ✅ Automatic browser launch on dev server

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/guillemleon/react-ts-template.git
cd react-ts-template
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start development server

```bash
npm run start
```

### 4. Build for production

```bash
npm run build
```

## Folder Structure

/react-ts-template/
│
├── /config/                  # Webpack configuration files
│   ├── webpack.common.js     # Common Webpack configuration
│   ├── webpack.dev.js        # Development Webpack configuration
│   └── webpack.prod.js       # Production Webpack configuration
│
├── /node_modules/            # Installed npm dependencies
│
├── /public/                  # Public assets
│   └── index.html            # HTML template
│
├── /src/                     # Source code for the app
│   ├── index.tsx             # Entry point for React
│   ├── App.tsx               # Main React component
│   └── /assets/              # Images and other assets
│
├── /dist/                    # Build output directory (generated after building)
│
├── .babelrc                  # Babel configuration
├── .gitignore                # Git ignore file
├── LICENSE                   # License file (your custom license)
├── README.md                 # Project documentation
├── package.json              # Project metadata and npm scripts
└── tsconfig.json             # TypeScript configuration



## Scripts

Command | Description
npm start | Start dev server (with React Fast Refresh)
npm run build | Build production bundle
npm test | Placeholder for test setup

## Tips

Use .tsx for components and .ts for utilities and logic.

The dist/ folder is automatically cleaned before each production build.

React Fast Refresh only works in development mode.

Customize Webpack config by modifying the files in the config/ directory.