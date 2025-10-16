<div align="center">
  <br />
  <h1>🤖 Maverick</h1>
  <p>A sleek, responsive, and unrestricted AI chatbot powered by Dolphin Mistral, built with Node.js and Express.</p>
  <br />

  <p align="center">
    <a href="https://maverick-95om.onrender.com">
      <img src="https://img.shields.io/badge/Live-Demo-blueviolet?style=for-the-badge&logo=rocket" alt="Live Demo">
    </a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js Badge">
    <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js Badge">
    <img src="https://img.shields.io/badge/EJS-103F54?style=for-the-badge&logo=javascript&logoColor=white" alt="EJS Badge">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge" alt="License Badge">
  </p>
</div>

---

### ✨ Key Features

-   **🧠 Unrestricted AI:** Leverages the powerful `cognitivecomputations/dolphin-mistral-24b-venice-edition` model for open and powerful conversations.
-   **🎨 Modern Aurora UI:** A stunning dark theme with vibrant gradients and a clean, user-friendly interface.
-   **📱 Fully Responsive:** The UI seamlessly adapts to any screen size, from desktops to mobile phones.
-   **💬 Isolated Sessions:** Each browser tab maintains a separate, unique conversation history.
-   **💨 Instant Feedback:** User messages appear instantly, followed by an elegant bouncing loader while the AI thinks.
-   **📄 Markdown Support:** The AI's responses are beautifully rendered with support for code blocks, lists, bolding, and more.

---

### 🛠️ Tech Stack

| Technology     | Description                                                  |
| :------------- | :----------------------------------------------------------- |
| **Node.js** | Backend JavaScript runtime environment.                      |
| **Express.js** | Web framework for building the server and API routes.        |
| **EJS** | Templating engine to render the frontend with dynamic data.  |
| **Axios** | Promise-based HTTP client for making API calls to OpenRouter. |
| **Marked.js** | A fast Markdown parser to render AI responses as HTML.       |
| **Dotenv** | Module to load environment variables from a `.env` file.     |
| **CSS3** | Custom styling for the modern "Aurora" theme and responsiveness. |

---

### 🚀 Getting Started (Local Setup)

To get a local copy up and running, follow these simple steps.

#### Prerequisites

-   Node.js installed on your machine.
-   An API key from [OpenRouter.ai](https://openrouter.ai/).

#### Installation & Setup

1.  **Install NPM packages:**
    ```bash
    npm install
    ```
2.  **Create a `.env` file** in the root of the project and add your API key:
    ```env
    OPENROUTER_API_KEY=your_openrouter_api_key_here
    ```
3.  **Run the server:**
    ```bash
    node server.js
    ```
4.  Open your browser and navigate to `http://localhost:3000`.

---

### 👨‍💻 Created By

This project was created by **Chinmay V Chatradamath**.

---

### 📄 License

This project is distributed under the MIT License. See `LICENSE` for more information.
