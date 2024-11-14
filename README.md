# React JS

## What is React JS?
React JS is a popular JavaScript library used for building user interfaces, particularly single-page applications. It allows developers to create reusable UI components, making code easier to manage, debug, and scale. React uses a virtual DOM to update only the parts of the UI that have changed, which improves performance and efficiency.

## How to Setup React JS
Setting up React JS involves installing Node.js, npm (Node Package Manager), and using the `create-react-app` tool to quickly scaffold a new project.

### Key Features
- **Component-Based Architecture**: Build encapsulated components that manage their own state.
- **Virtual DOM**: React updates only the parts of the DOM that have changed, making applications faster.
- **Declarative**: Design simple views for each state in your application, and React will efficiently update the UI to match.
- **Unidirectional Data Flow**: Data flows in one direction, making code more predictable and easier to debug.
- **Rich Ecosystem**: React has a large ecosystem of libraries and tools that can extend its functionality, like React Router for navigation and Redux for state management.

### Prerequisites
- **Node.js**: A JavaScript runtime for building fast and scalable applications.
- **npm (Node Package Manager)**: Helps manage libraries and dependencies.
- **Code Editor**: VS Code or any editor of your choice.

### Step-by-Step Installation
1. **Install Node.js and npm**
   - Download and install Node.js from [https://nodejs.org](https://nodejs.org).
   - Confirm installation by running:
     ```bash
     node -v
     npm -v
     ```

2. **Create a React App**
   - Run the following command to create a new React project:
     ```bash
     npx create-react-app my-app
     ```
   - Replace `my-app` with your project name.

3. **Navigate to Project Directory**
   ```bash
   cd my-app