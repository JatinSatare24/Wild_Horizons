# 🗺️ Wild Horizons - Destination Explorer

A full-stack travel discovery application that allows users to browse global destinations and view detailed information. This project demonstrates the transition from a static frontend to a dynamic, Node.js-powered backend environment.

## ✨ Core Features
* **Dynamic Routing:** A custom backend "Librarian" that handles requests for specific destinations and assets.
* **OS-Agnostic Architecture:** Built to run on any operating system (Windows, Mac, or Linux) using professional pathing techniques.
* **JSON API Logic:** Handles data requests by reading local JSON files and serving them with appropriate MIME types.

## 🛠️ Tech Stack
* **Runtime:** Node.js (ES Modules enabled via `"type": "module"`)
* **Native Modules:** * `http`: For server creation and request handling.

## 🏗️ Backend Logic Checklist
The server follows a strict 4-step "Reading and Serving" workflow:
1. **Identify:** Check `req.url` to see if the user wants an HTML page, CSS style, or JSON data.

## 🚀 Getting Started
1. Clone the repository.
2. Ensure you have Node.js installed (v20.11.0 or higher recommended for `import.meta.dirname` support).
3. Initialize the project:
   ```bash
   npm init -y
