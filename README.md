# Tic Tac Toe Game

A fun and interactive Tic Tac Toe game built to help you learn GitHub Actions for Continuous Integration (CI).

## 📖 About

This project is an educational tool designed to teach developers about GitHub Actions through a practical, hands-on approach. By building and deploying a simple Tic Tac Toe game, you'll learn how to set up CI/CD pipelines, run automated tests, and implement best practices for modern software development workflows.

## ✨ Features

- **Interactive Gameplay**: Play Tic Tac Toe in your browser
- **GitHub Actions Integration**: Learn CI/CD workflows through practical examples
- **Automated Testing**: Includes test suite with Jest
- **Code Quality**: Uses StandardJS for linting
- **Modern Build Pipeline**: Webpack-based build system
- **Development Mode**: Hot-reload for easy development

## 🚀 Getting Started

### Prerequisites

- Node.js (v12 or higher recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dhanachavan/github-actions-for-ci.git
   cd github-actions-for-ci
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## 💻 Usage

### Development Mode

Start the development server with hot-reload:

```bash
npm run dev
```

This will watch for file changes and automatically rebuild the project.

### Production Build

Build the project for production:

```bash
npm run build
```

The compiled files will be generated in the `public/` directory.

### Running Tests

Run the test suite and linting:

```bash
npm test
```

This command will:
- Run StandardJS linting to check code quality
- Execute Jest tests

### Opening the Game

After building, open `index.html` in your web browser to play the game.

## 🛠️ Technology Stack

- **JavaScript (ES6+)**: Core programming language
- **Webpack**: Module bundler and build tool
- **Babel**: JavaScript transpiler for browser compatibility
- **Jest**: Testing framework
- **StandardJS**: Code linting and style guide
- **HTML/CSS**: Frontend markup and styling

## 📁 Project Structure

```
github-actions-for-ci/
├── src/                    # Source files
│   ├── game.js            # Game logic
│   ├── index.js           # Entry point
│   └── webpack.config.js  # Webpack configuration
├── public/                # Static assets and build output
│   └── index.css          # Stylesheets
├── index.html             # Main HTML file
├── package.json           # Project dependencies and scripts
├── babel.config.js        # Babel configuration
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## 🤝 Contributing

Contributions are welcome! This project is designed for learning, so feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

Please ensure your code follows the StandardJS style guide and includes appropriate tests.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Originally created by [The GitHub Training Team](https://github.com/githubtraining)
- Part of the GitHub Actions learning curriculum

## 📚 Learning Resources

To learn more about GitHub Actions:

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Skills](https://skills.github.com/)
- [GitHub Learning Lab](https://lab.github.com/)

---

**Happy Learning! 🎮**
