<div align="center">
  
  # Just Another Text Editor (J.A.T.E)
  > Module 19 Challenge

![JavaScript Badge](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
[![Node.js Badge](https://img.shields.io/badge/Node.js-393%3F?style=for-the-badge&logo=node.js&logoColor=green)](https://nodejs.org/en/)
[![Express Badge](https://img.shields.io/badge/Express-4.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Webpack Badge](https://img.shields.io/badge/Webpack-5.x-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)](https://webpack.js.org/)
[![PWA Badge](https://img.shields.io/badge/PWA-Progressive%20Web%20App-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)

</div>

## Description

This repository contains the code for the **Just Another Text Editor (J.A.T.E)** project. J.A.T.E is a Progressive Web App (PWA) text editor that works both online and offline, utilizing service workers and IndexedDB for persistent data storage. The app allows users to create, update, and store text content, making it accessible even when offline.

### Website

The live application can be accessed [here](https://jate-text-editor-pcpj.onrender.com).

### Key Features:

-   **PWA**: Installable as a web app, with offline capabilities.
-   **Service Worker**: Enables the app to work offline.
-   **IndexedDB**: Stores content locally for offline access.
-   **Data Persistence**: Text is saved and available even after closing the browser.

## Installation

To run this application, follow these steps:

1. **Ensure Node.js is Installed:**

    You will need Node.js installed on your computer. Check if you have Node.js by typing `node -v` in your command line. You should see a version number. If Node.js is not installed, visit the [Node.js website](https://nodejs.org/en) to install it.

2. **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/jate-text-editor.git
    cd jate-text-editor
    ```

3. **Install Dependencies:**

    ```bash
    npm install
    ```

4. **Start the Application:**

    ```
    npm run start:dev
    ```

    This will start the Webpack development server and open the app in your browser.

5. **Access the Application:**

    To build the production version of the application, run:

    ```
    npm run build
    ```

    This will bundle the code using Webpack and generate the necessary files in the dist directory.

    To start the production server, run:

    ```
    npm start
    ```

    This will start the Express server and serve the production version of the app.

## Features

### Service Workers

This application uses Workbox to generate a service worker that caches key assets and ensures that the app can work offline.

### IndexedDB

J.A.T.E uses IndexedDB to store content so that users can continue writing and editing text even without an internet connection. The data is saved locally and reloaded the next time the app is opened.

## Usage

1. **Writing Text**: Users can write text in the editor. The content is automatically saved in IndexedDB for offline persistence.

2. **Offline Support**: When offline, the app will load the last saved content from IndexedDB.

3. **PWA Installation**: Users can install the app to their desktop or mobile device by clicking the 'Install' button.

4. **Service Worker**: The service worker caches key assets to ensure that the app works offline.

## License

[MIT License](https://opensource.org/licenses/MIT)

## Contact

-   GitHub: [leontran44](https://github.com/leontran44)
-   Email: [Leon Tran](mailto:leontran44@gmail.com)
-   LinkedIn: [Leon Tran](https://www.linkedin.com/in/hoangqtran/)
