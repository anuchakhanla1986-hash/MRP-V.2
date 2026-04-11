# Setup Documentation

## Installation Guide

### Prerequisites
- Ensure you have [Node.js](https://nodejs.org/) installed.
- Install [Git](https://git-scm.com/) for version control.

### Steps for Cloning
1. Open your terminal.
2. Clone the repository using:
   ```bash
   git clone https://github.com/anuchakhanla1986-hash/MRP-V.2.git
   ```

### Installing Dependencies
1. Navigate to the project directory:
   ```bash
   cd MRP-V.2
   ```
2. Install the necessary dependencies using:
   ```bash
   npm install
   ```

### Configuring Environment
- Create a `.env` file in the root directory and populate it with the necessary environment variables.

### Starting Development Server
- To start the development server, run:
  ```bash
  npm start
  ```
- The default development server will be accessible at `http://localhost:3000`.

### Accessing Application
- Open your browser and navigate to `http://localhost:3000` to access the application.

### Building for Production
1. To build the application for production, run:
   ```bash
   npm run build
   ```
2. This will create a `dist/` directory with the production build.

### Running Tests
- To run the tests, use:
  ```bash
  npm test
  ```
- Ensure you have written tests appropriately to verify all parts of your application.