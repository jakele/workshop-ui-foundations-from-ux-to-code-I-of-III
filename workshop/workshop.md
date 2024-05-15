# Workshop Series: From Design to Development for Designers & UX Practitioners

## Workshop 1: Getting Started with Development

### Introduction to Terminal

**Objective:** Understand what Terminal is and how to use it for basic file system navigation.

1. **Open Terminal**

   - Open the Terminal application on your computer.

2. **What is Terminal?**

   - Terminal is a non-graphical user interface (non-GUI) for navigating your file system.
   - You use a GUI every day when you use Finder. Terminal is like Finder but in a text-based format.
   - Think of Terminal as a text-based video game compared to modern graphical games.
   - Example: Type `open .` in Terminal to open Finder in your current location. Navigate back to Terminal and type `cd Documents`, then type `open .` again. Notice how you're now inside the Documents folder.

   **Teacher's Note:** Walk participants through navigating Finder to do the same. Highlight that we navigated using words in Terminal instead of a trackpad.

3. **Why Use Terminal?**
   - Terminal allows you to run non-GUI applications like Git, which we'll cover later.
   - Terminal, like iOS or Windows, has vast capabilities. We'll simplify our use to three main functions: navigating the file system, running Node apps, and using Git.

### Basic Terminal Commands

**Objective:** Learn and practice essential Terminal commands.

1. **Navigating the File System**

   - `ls`: Lists files and directories in the current directory.
   - `cd <directory>`: Changes the current directory to the specified directory.
   - `.`: Refers to the current directory.
   - `..`: Refers to the parent directory.
   - `open .`: Opens Finder in the current directory.
   - `mkdir <directory>`: Creates a new directory.

   **Hot Tip:** Always use tab to auto-complete directory names. Terminal is case-sensitive and spaces matter.

2. **Running Node Apps**

   - `node <file>`: Runs a Node.js file.

3. **Running Git**
   - Basic Git commands will be covered in a later session.

### Setting Up VS Code

**Objective:** Install and set up VS Code, and understand what a code editor is.

1. **Download and Install VS Code**

   - Download VS Code from [here](https://code.visualstudio.com/).
   - Follow the installation instructions for your operating system.

2. **What is a Code Editor?**

   - A code editor is a tool that helps you write and manage code. It provides features like syntax highlighting, code completion, and debugging.
   - VS Code is a popular code editor with many extensions and integrations.

3. **Setting Up VS Code Command Line**
   - Open VS Code.
   - Press `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Windows) to open the Command Palette.
   - Type `Shell Command: Install 'code' command in PATH` and press Enter.
   - Now you can open VS Code from Terminal by typing `code .`.

### Creating a React Application

**Objective:** Set up a new React application using Create React App.

1. **Install Node.js**

   - Download and install Node.js from [here](https://nodejs.org/).

2. **Create React App**

   - In Terminal, navigate to the directory where you want to create your project.
   - Run `npx create-react-app my-app` to create a new React application.
   - Navigate into the project directory: `cd my-app`.
   - Open the project in VS Code: `code .`.

3. **Update Text in `App.js`**
   - Open `src/App.js` in VS Code.
   - Modify the text inside the `div` to something new.
   - Save the file and observe the changes in the browser.

### Adding Material UI (MUI)

**Objective:** Install and use Material UI components in your React application.

1. **Install Material UI**

   - Run `npm install @mui/material @emotion/react @emotion/styled`.

2. **Add Components**

   - Import and use MUI components in your React application.
   - Example: Add a button component to `App.js`.

   ```jsx
   import Button from "@mui/material/Button";

   function App() {
     return (
       <div className="App">
         <h1>Hello, World!</h1>
         <Button variant="contained" color="primary">
           Click Me
         </Button>
       </div>
     );
   }

   export default App;
   ```

### Exercise: Creating a Repo Directory

**Objective:** Practice navigating the file system and creating directories.

1. **Navigate to Documents**

   - `cd ~/Documents`

2. **Create a Repo Directory**
   - `mkdir repos`
   - `cd repos`

### Summary and Q&A

- Recap the session's topics.
- Answer any questions.
