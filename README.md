# Installation and Setup Guide 🚀

Welcome to this project! Follow these steps to set up and run the application effortlessly. 🌟

---

## 📂 Project Structure
The repository is divided into two main directories:
- **`ui`**: Contains the frontend code (Angular)
- **`server`**: Contains the backend code (NodeJS and ExpressJS)

To run the application, you'll need to install dependencies and start the code separately for both directories.

---

## 🛠️ Prerequisites
1. **Download and Install NodeJS and MongoDB**
   - Detailed installation instructions are available in the `docs` directory.
2. **Clone the Repository**
   ```bash
   git clone <repo-link>
   ```

---

## 🌐 Backend Setup (`server`)
1. **Rename Configuration File**
   - Navigate to the `server` directory and rename `.env_example` to `.env`.

2. **Install Dependencies and Start Server**
   Open a terminal and run the following commands:
   ```bash
   cd server
   npm install
   npm start
   ```

3. **Add Sample User Data**
   - Navigate to the `server/scripts` directory to run the script that populates user data:
     ```bash
     cd server/scripts
     node createUsers.js
     ```

---

## 🎨 Frontend Setup (`ui`)
1. Open another terminal and navigate to the `ui` directory.
2. Run these commands to install dependencies and start the UI:
   ```bash
   cd ui
   npm install
   npm start
   ```

---

## ⚙️ Customization
### Changing the Server Port
1. Update the `SERVER_PORT` value in the `server/.env` file.
2. Update the corresponding `baseUrl` in the `ui/src/assets/environment.json` file to match the server port.

**Example:**
If your `SERVER_PORT` is **4000**, set the `baseUrl` as:
```json
{
  "baseUrl": "http://localhost:4000"
}
```

---

## 🚀 Visual Overview
To make your experience even better, enjoy a dynamic animation that guides you through the setup process!

![Setup Animation](https://media.giphy.com/media/QHE5gWI0QjqF2/giphy.gif)

---

### You're All Set! 🎉
Your application should now be running smoothly. Explore and enjoy coding! 💻✨

