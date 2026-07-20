# Weather API Proxy Server ☁️🛡️

A focused Node.js and Express backend designed to act as a secure proxy for fetching data from third-party weather APIs. This server ensures that sensitive API keys remain completely hidden from the client side while effectively bypassing frontend Cross-Origin Resource Sharing (CORS) issues.

## ✨ Key Features

*   **🔒 API Key Protection:** Keeps your private weather API keys securely on the server using environment variables.
*   **🚧 CORS Resolution:** Acts as a middleman to prevent CORS errors when your frontend React application requests weather data.
*   **⚡ Lightweight:** Built with minimal dependencies to ensure fast response times and straightforward maintenance.

## 📂 Project Structure

```text
backend/
├── node_modules/       # Project dependencies (ignored in git)
├── .env                # Environment variables (API keys - ignored in git)
├── .gitignore          # Specifies intentionally untracked files
├── package-lock.json   # Exact dependency versions
├── package.json        # Project metadata and scripts
└── server.js           # Main Express server application logic