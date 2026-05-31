# Student Collaboration Hub - Frontend

A modern React-based frontend application for student collaboration, built with Vite and styled with Tailwind CSS.

## 📋 Overview

This is the frontend component of the Student Collaboration Hub, a platform designed to facilitate communication and collaboration among students. The application provides a responsive, user-friendly interface with real-time state management and routing capabilities.

## 🛠️ Tech Stack

- **React** (^18.2.0) - UI library
- **Vite** (^4.0.0) - Build tool and dev server with HMR
- **Tailwind CSS** (^3.0.0) - Utility-first CSS framework
- **Redux Toolkit** (^1.9.5) - State management
- **React Router** (^6.22.3) - Client-side routing
- **Axios** (^1.6.7) - HTTP client
- **React Icons** (^5.5.0) - Icon library

## 📦 Language Composition

- JavaScript: 91.8%
- CSS: 7.1%
- HTML: 1.1%

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18.0.0
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/neeru-meda/sch-frontend.git
cd sch-frontend
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your API endpoints and configuration (see `.env.example` if available)

### Development

Start the development server with hot module replacement:

```bash
npm run dev
# or
npm start
```

The application will be available at `http://localhost:5173` (or the next available port).

### Build

Build the application for production:

```bash
npm run build
```

The optimized build will be output to the `dist` directory.

### Preview

Preview the production build locally:

```bash
npm run preview
```

## 📁 Project Structure

```
sch-frontend/
├── src/                   # Source files
├── public/                # Static assets
├── index.html            # Entry HTML file
├── vite.config.js        # Vite configuration
├── tailwind.config.cjs   # Tailwind CSS configuration
├── postcss.config.cjs    # PostCSS configuration
├── eslint.config.js      # ESLint configuration
└── package.json          # Project metadata and dependencies
```

## 🎨 Features

- **Responsive Design** - Mobile-first approach with Tailwind CSS
- **State Management** - Redux Toolkit for predictable state management
- **Client-Side Routing** - React Router for seamless navigation
- **API Integration** - Axios for HTTP requests
- **Code Quality** - ESLint configuration for consistent code style
- **Fast Development** - Vite's HMR for instant feedback

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with HMR |
| `npm start` | Alias for dev server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |

## 🔧 Configuration Files

- **vite.config.js** - Vite build configuration
- **tailwind.config.cjs** - Tailwind CSS customization
- **postcss.config.cjs** - PostCSS plugins configuration
- **eslint.config.js** - Linting rules
- **.env** - Environment variables (not included in repo)
- **.gitignore** - Files excluded from version control

## 📚 Learning Resources

- [React Documentation](https://react.dev)
- [Vite Guide](https://vitejs.dev)
- [Tailwind CSS Documentation](https://tailwindcss.com)
- [Redux Toolkit Documentation](https://redux-toolkit.js.org)
- [React Router Documentation](https://reactrouter.com)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👤 Author

[neeru-meda](https://github.com/neeru-meda)

## 📧 Support

For issues, questions, or suggestions, please open an [issue](https://github.com/neeru-meda/sch-frontend/issues) on GitHub.

---

**Last Updated:** May 2026
