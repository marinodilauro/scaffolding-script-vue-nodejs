# 🚀 Node.js and Vue.js Scaffolding Script

This Bash script automates the setup of a **Node.js backend** and a **Vue.js frontend** for a new project. It simplifies the process of creating a boilerplate application structure, complete with essential files and configurations.

## 🎉 Features
- **Directory Structure**: Creates a well-organized directory structure for both backend and frontend applications.
- **Node.js Initialization**: Initializes a Node.js project and installs necessary dependencies.
- **Express Server**: Sets up a basic Express server with static file serving for the frontend.
- **Fast Development**: Uses Vite for rapid development of Vue.js applications.
- **Dynamic Components**: Generates dynamic components in Vue.js, including a Header and Footer.
- **Bootstrap Integration**: Installs Bootstrap as a CSS framework.
- **User Experience**: Includes a loading bar during the project creation process for a better user experience.

## 📦 Node.js Dependencies
The script installs the following Node.js dependencies in the backend:
- **express**: A web application framework for Node.js, designed for building APIs and web applications.
- **dotenv**: A module that loads environment variables from a `.env` file into `process.env`.
- **nodemon**: A utility that automatically restarts the Node.js application when file changes are detected.

## 🎨 Vue.js Dependencies
- **vue-router**: The official router for Vue.js, enabling navigation between different views in a Vue application.

## 🌱 Environment Variables
The script generates a `.env` file in the `backend` directory containing the following environment variables:
- **VITE_APP_NAME**: The name of the application (provided by the user).
- **APP_ENV**: Environment type (default: development).
- **APP_DEBUG**: Debug mode (default: true).
- **APP_URL**: The base URL of the application.
- **PORT**: The port on which the server runs (default: 8080).
- **DB_CONNECTION**: Database connection type (default: mysql).
- **DB_HOST**: Database host (default: 127.0.0.1).
- **DB_PORT**: Database port (default: 3306).
- **DB_DATABASE**: Name of the database (default: `${APP_NAME}_db`).
- **DB_USERNAME**: Database username (default: root).
- **DB_PASSWORD**: Database password (default: root).

## 🗂️ Directory Structure
The script creates the following directory structure:
```
project-name/
├── backend/
│   ├── node_modules/
│   ├── package-lock.json
│   ├── package.json
│   └── server.js
└── frontend/
    ├── .vscode/
    ├── node_modules/
    ├── public/
    ├── src/
    │   ├── assets/
    │   │   ├── nodejs.svg
    │   │   └── vue.svg
    │   ├── components/
    │   │   ├── Card.vue
    │   │   ├── Footer.vue
    │   │   └── Header.vue
    │   ├── router/
    │   │   └── router.js
    │   ├── views/
    │   │   ├── About.vue
    │   │   └── Homepage.vue
    │   ├── App.vue
    │   ├── main.js
    │   └── style.css
    ├── .env
    ├── .gitignore
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── README.md
    └── vite.config.js
```

## ⚙️ Usage
To use this script, follow these steps in a bash terminal:

1. Make the script executable:
   ```bash
   chmod +x create-nodejs-vue.sh
   ```
2. Run the script with your desired project name:
    ```bash
    ./create-nodejs-vue.sh [project-name]
    ```
3. You will be prompted to enter an application name. Press Enter to use the default project name or provide a new one.

## 🤝 Contributing
Feel free to contribute to this project by submitting issues or pull requests.

## 📄 License
This project is open source and available under the MIT License.

