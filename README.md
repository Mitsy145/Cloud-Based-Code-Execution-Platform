# 🌐 Cloud-Based Code Execution Platform

A secure and scalable cloud platform that enables users to **write, compile, and execute code in multiple programming languages directly from the browser**. Built with server-side rendering (EJS), a responsive frontend, and a robust backend, the platform provides a real-time coding experience for developers, learners, and interviewers.



## 🚀 Key Features

- 💻 **Write, Compile, and Execute Code Online**
- 🧠 **Supports Multiple Languages** (C, C++, Python, JavaScript, etc.)
- 🔐 **Secure Execution in Isolated Environments**
- 📊 **Real-Time Output and Error Display**
- 📡 **Asynchronous Job Processing**
- 📱 **Responsive and Minimal Frontend UI**

---

## 🛠️ Tech Stack

| Layer        | Technologies Used                                |
|--------------|--------------------------------------------------|
| 💻 Frontend  | HTML, CSS, JavaScript, Bootstrap                 |
| 🎯 Templating| EJS (Embedded JavaScript Templates)              |
| 🔙 Backend   | Node.js, Express.js                              |
| 🐳 Execution | Docker (for secure code sandboxing)              |
| 🕸️ Messaging | RabbitMQ (for managing code execution jobs)      |
| 🗃️ Database  | MongoDB (for storing job logs and user data)     |

---

## 📊 Language Breakdown (Based on GitHub Stats)

- 🟦 **EJS** – 47.5%  
- 🌐 **HTML** – 26.9%  
- 📜 **JavaScript** – 23.6%  
- 🎨 **CSS** – 1.1%  
- 🧩 **Other** – 0.9%

---

## 📂 Folder Structure

├── views/ # EJS templates for rendering dynamic HTML
├── public/ # Static files (CSS, JS)
├── routes/ # Express route controllers
├── compiler/ # Code execution logic using Docker
├── queue/ # RabbitMQ configuration and workers
├── models/ # MongoDB models (job logs, user data)
├── app.js # Main Express server file
└── README.md # Project description


---

## 🧠 How It Works

1. The user enters code and selects a language from the frontend.
2. The code is sent to the backend and placed in a **RabbitMQ job queue**.
3. A **Docker container** picks up the job and runs it in a secure, isolated environment.
4. The output (or errors) is returned and displayed in the frontend in real time.
5. Execution data is logged into **MongoDB** for future reference or analytics.


💡 Use Cases
👨‍🏫 Educational Platforms – Let students write and test code in-browser

💼 Interview Portals – Assess candidates' coding skills securely

💬 Coding Communities – Provide an instant code playground

📱 Code Sharing Apps – Share and run code snippets in real time
