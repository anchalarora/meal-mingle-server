# 🍽️ Meal Mingle Server

## Overview

The **Meal Mingle Server** is a Node.js server built to call the Swiggy API and handle Cross-Origin Resource Sharing (CORS) issues 🌐. It acts as the backend for the [Meal Mingle Frontend](https://github.com/anchalarora/namaste-react-meal-mingle-app), Live at : [Meal Mingle App](https://mealmingle-app.netlify.app/) ensuring smooth API communication between the client and external services like Swiggy 🚀.

This server is part of the **Meal Mingle** project [Meal Mingle Frontend](https://github.com/anchalarora/namaste-react-meal-mingle-app), which allows users to browse meals, place orders, and interact with a modern, user-friendly meal ordering system. 🥡🥗

## Features

- **Proxy Server**: 🛠️ Makes API calls to Swiggy to fetch restaurant and meal data.
- **CORS Handling**: 🚧 Resolves CORS issues, allowing secure communication between the frontend and Swiggy API.
- **Seamless Integration**: ⚡ Works perfectly with the Meal Mingle frontend app to provide a smooth user experience.
- **Efficient Performance**: 💨 Built with Node.js for fast API handling and performance optimization.

## Endpoints
1. /api/restaurants: 📍 Returns a list of restaurants by interacting with the Swiggy API.

2. /api/menu: 📜 Returns a list of menu items from a selected restaurant by calling Swiggy’s menu API.

3. /: 🎉 A simple root route to test server availability and link to the Meal Mingle live web app.

## Getting Started

### Prerequisites

Make sure you have the following installed before starting:

- [Node.js](https://nodejs.org) (v12 or higher) 🟢
- [npm](https://npmjs.com) (Node Package Manager) 📦

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/anchalarora/meal-mingle-server.git
   ```

2. **Navigate to the project directory**:
    ```bash
    cd meal-mingle-server
    ```

3. **Install dependencies**:
    ```bash
    npm install
    ```

4. **Usage**
    Start the server:
    ```bash
    npm start
    ```

By default, the server will run on http://localhost:3000 🚀.

5. **Server Endpoints**:

/api/swiggy: Proxy endpoint to call Swiggy API and return data 📡.
This server is designed to work with the Meal Mingle frontend app. Make sure the frontend points to this server's API 🌉.

6. **Environment Variables**:

Create a .env file in the root of the project to store your environment variables:

PORT=3000

🛡️ **CORS Handling**

The server handles CORS issues, allowing API calls from the frontend to Swiggy without any restrictions 🚫🔒.

🌐 **Integration with Meal Mingle Frontend**

The Meal Mingle server is designed to work alongside the Meal Mingle Frontend App. You can find the frontend app and try it out live here:

Frontend GitHub Repository: [Meal Mingle Frontend](https://github.com/anchalarora/namaste-react-meal-mingle-app)
Live App: [Meal Mingle App](https://mealmingle-app.netlify.app/)

🛠️**Contributing**
We welcome contributions! If you'd like to improve this project, feel free to fork the repository and submit a pull request 🤝. Any feedback or suggestions are highly appreciated!

🏆**License**
This project is licensed under the MIT License. See the LICENSE file for details.


