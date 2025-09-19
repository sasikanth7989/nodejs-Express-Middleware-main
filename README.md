Implement Express Middleware for Logging and JSON Body Parsing
📌 Project Overview

This project demonstrates how to create a simple Express.js application that uses middleware for:

Logging requests (method, URL, timestamp)

Parsing JSON request bodies using the built-in express.json() middleware.

🚀 Getting Started
1. Setup Project

Create a new project folder and install dependencies:

mkdir express-middleware
cd express-middleware
npm init -y
npm install express

2. Create Application

Create a file app.js and:

Import Express and create an app instance.

Use express.json() middleware to parse JSON data.

Add a custom middleware to log request method, URL, and time.

Create sample routes (GET / and POST /data).

3. Run the Server

Start the application:

node app.js


Open http://localhost:3000
 in your browser or test using Postman.

📂 Project Structure
express-middleware/
 ├── app.js
 ├── package.json
 └── README.md

✅ Output
![WhatsApp Image 2025-09-19 at 09 55 59_3a1cbfb3](https://github.com/user-attachments/assets/1c020317-39da-4208-99c4-dca00d554013)
![WhatsApp Image 2025-09-19 at 09 55 59_08201cbe](https://github.com/user-attachments/assets/2d1637e3-754b-465f-bb3f-1a550ca5f9b0)
![WhatsApp Image 2025-09-19 at 09 55 59_21e19099](https://github.com/user-attachments/assets/1e135958-0756-495a-8e75-22dc3124deab)
