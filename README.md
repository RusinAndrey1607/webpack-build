## React + TypeScript Webpack Configuration with ESLint, Jest, and Storybook

This guide provides a comprehensive setup for building a React application with TypeScript, utilizing Webpack for bundling and incorporating essential tools like ESLint for code quality, Jest for testing, and Storybook for component development and documentation.

### Project Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RusinAndrey1607/webpack-build.git my-react-app
   cd my-react-app
   ```

2. **Install dependencies:**
   ```bash
   npm install 
   ```

### Running the Development Server

1. **Start the development server:**
   ```bash
   npm start
   ```

This command starts the development server, which automatically opens your application in the browser.

### Project Structure

```
my-react-app
└── src
    │── index.tsx
    ├── app
    │   ├── App.tsx
    │       
    ├── pages
    │   └── Home
    │       
    ├── widgets
    │   └── MyWidget
    │        
    ├── features
    │   └── User
    │       
    ├── entities
    │   └── User
    │      
    └── shared
