![image](https://github.com/user-attachments/assets/1a32a0e8-958e-4267-b89c-a9f4ee874888)



# Electron React Application

This is a template for an Electron application with React, Vite, Tailwind CSS, and SQLite integration.

## Features

- Electron for cross-platform desktop application development
- React for building user interfaces
- Vite for fast development and building
- Tailwind CSS for utility-first styling
- SQLite for local database storage

## Prerequisites

- Node.js (version 18.0.0 or later)
- npm (usually comes with Node.js)

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/Maximekgn/ElectronJS-React-sqlite_Template.git

   cd your-repo-name
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Run the application in development mode:
   ```
   npm run dev
   ```

4. Build the application for production:
   ```
   npm run build
   ```

5. Package the application for different platforms:
   - Windows: `npm run build:win`
   - macOS: `npm run build:mac`
   - Linux: `npm run build:linux`

## Project Structure

- `src/main`: Electron main process code
- `src/preload`: Preload scripts for Electron
- `src/renderer`: React application code
- `resources`: Application resources (e.g., database file)

## Configuration

- Electron builder configuration is in `electron-builder.yml`
- Vite configuration is in `electron.vite.config.mjs`

## Scripts

- `npm start`: Preview the built app
- `npm run dev`: Run the app in development mode
- `npm run build`: Build the app for production
- `npm run lint`: Lint the code
- `npm run format`: Format the code with Prettier

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


