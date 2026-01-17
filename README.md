# Tic Tac Toe

A simple React-based Tic Tac Toe game.

if ypour react app version 18 change into version 19 
```bash
npm install --save-exact react@^19.0.0 react-dom@^19.0.0
```

fastest way to delelete node modules 
```bash
PowerShell.exe -Command {Remove-Item -Recurse -Force -ErrorAction SilentlyContinue .\node_modules}
```
<!--(i like use ai it helps boring work faster i use ai here only for post here writing you can see)-->

#🧩 Simple React Tic-Tac-Toe (Multiplayer)

📌 Features

✔ Two players (X and O) take turns <br>
✔ Simple UI with grid <br>
✔ Shows current player  <br>
✔ Detects wins & ties  <br>
✔ Easy to read for new learners  <br>

📁 Project Structure
```bash
tic-tac-toe/
├── public/              # Static files
│   ├── index.html      # Main HTML file
│   ├── manifest.json   # App metadata
│   └── robots.txt      # SEO robots file
├── src/                # Source code
│   ├── App.js          # Main App component
│   ├── App.css         # App styles
│   ├── index.js        # Entry point
│   ├── index.css       # Global styles
│   └── reportWebVitals.js  # Performance metrics
├── package.json        # Project dependencies
├── package-lock.json   # Locked dependency versions
└── node_modules/       # Installed packages (auto-generated)
```

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- **Node.js** (version 14 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) - Package manager for JavaScript

To verify your installation, run:
```bash
node --version
npm --version
```

## Installation

### Step 1: Navigate to the Project Directory
```bash
cd tic-tac-toe
```

### Step 2: Install Node Module Dependencies
Install all required npm packages listed in `package.json`:
```bash
npm install
```

This command will:
- Read the `package.json` file
- Download and install all dependencies (React, React DOM, React Scripts, Web Vitals, etc.)
- Create a `node_modules` folder containing all the libraries
- Update the `package-lock.json` file to lock dependency versions

**Note:** If you encounter peer dependency warnings, you can use:
```bash
npm install --legacy-peer-deps
```

### Step 3: Verify Installation
To verify that all packages were installed correctly, run:
```bash
npm ls
```

## Running the Project

### Start the Development Server
Once dependencies are installed, start the React development server:
```bash
npm start
```

This command will:
- Start a local development server (typically on `http://localhost:3000`)
- Open the project in your default browser
- Enable hot-reloading (changes will automatically refresh in the browser)

The app should open automatically. If not, visit `http://localhost:3000` in your browser.

## Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm build`
Builds the app for production to the `build` folder.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm eject`
**Note:** This is a one-way operation. Once you eject, you can't go back!

## Project Structure

```
tic-tac-toe/
├── public/              # Static files
│   ├── index.html      # Main HTML file
│   ├── manifest.json   # App metadata
│   └── robots.txt      # SEO robots file
├── src/                # Source code
│   ├── App.js          # Main App component
│   ├── App.css         # App styles
│   ├── index.js        # Entry point
│   ├── index.css       # Global styles
│   └── reportWebVitals.js  # Performance metrics
├── package.json        # Project dependencies
├── package-lock.json   # Locked dependency versions
└── node_modules/       # Installed packages (auto-generated)
```

## Dependencies

The project uses the following main dependencies:
- **React** (^18.0.0) - JavaScript library for building user interfaces
- **React DOM** (^18.0.0) - React package for DOM manipulation
- **React Scripts** (^5.0.0) - Build scripts and configuration for React apps
- **Web Vitals** (^2.1.4) - Library for measuring web performance metrics

## Troubleshooting

### "Module not found" Errors
If you encounter module not found errors:
```bash
# Clear node_modules and reinstall
rm -r node_modules package-lock.json
npm install
```

### Port 3000 Already in Use
If port 3000 is already in use, you can specify a different port:
```bash
PORT=3001 npm start
```

### npm install Takes Too Long
For faster installation, use:
```bash
npm ci
```

This uses `package-lock.json` for exact dependency versions.

## License

This project is private and for educational purposes.





