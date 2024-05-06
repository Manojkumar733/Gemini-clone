# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

To run a React.js project using Vite, a modern build tool, you can follow these steps:

Initialize a React Project: If you haven't already created a React project, you can do so by using create-react-app or any other method you prefer. For example

npx create-react-app my-react-app
Replace my-react-app with the name you want for your project.
Install Vite: Vite can be installed globally or locally in your project. It's recommended to install it locally in your project to avoid any version conflicts. Run the following command in your project directory:


npm install --save-dev vite
Create a Vite Configuration File (Optional): Vite can work without a configuration file for basic setups. However, if you need custom configurations, you can create a vite.config.js file in your project directory and configure it according to your requirements.
Update package.json Scripts: Update your package.json file to add a script to run Vite. Add the following script:
json

"scripts": {
  "dev": "vite"
}
Start the Development Server: Run the following command in your terminal to start the development server using Vite:

npm run dev
View Your Application: Once the development server has started, it will compile your React code and launch a browser window/tab with your React application running. If it doesn't automatically open, you can access it by navigating to http://localhost:3000 in your web browser.
Make Changes and Save: You can now make changes to your React code. As you save your changes, Vite will automatically update and reflect those changes in the browser without needing a full page reload.
