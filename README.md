# 🌐 omniConvert — Universal File Converter

**Convert files with ease using one simple web application.**

omniConvert is a full-stack web application built to provide a convenient interface for file conversion. It combines a React-based frontend with a Node.js and Express backend to create a modern, browser-accessible application.

## ✨ Features

- 🖥️ **Modern Web Interface** — Built with React and Vite.
- 🔄 **File Conversion Backend** — Node.js and Express-based server.
- 📁 **File Handling** — Uses Multer for handling uploaded files.
- ⚡ **Fast Development** — Vite-powered frontend development server.
- 🛡️ **Request Handling** — CORS and compression middleware.
- 🧩 **Modular Architecture** — Separate frontend and backend directories for easier development.

> Available conversion formats and additional features depend on the converters implemented in the project.

## 🛠️ Tech Stack

| Component | Technologies |
|---|---|
| Frontend | React, Vite, JavaScript |
| UI Icons | Lucide React |
| Styling | Tailwind CSS |
| Backend | Node.js, Express.js |
| File Uploads | Multer |
| Middleware | CORS, Compression |
| Development | Nodemon, npm |

## 📂 Project Structure

```text
omniConvert/
├── omniconvert-backend/
│   ├── src/
│   │   └── server.js
│   ├── package.json
│   └── package-lock.json
│
├── omniconvert-frontend/
│   ├── src/
│   ├── index.html
│   ├── vite.config.js
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Install the following before running the project:

- [Node.js](https://nodejs.org/) — includes npm
- [Git](https://git-scm.com/)
- A modern web browser

### 1. Clone the Repository

```bash
git clone https://github.com/sudhagirishgeet/omniConvert.git
cd omniConvert
```

### 2. Set Up the Backend

Open a terminal in the project root and run:

```bash
cd omniconvert-backend
npm install
npm start
```

For development with automatic restarts:

```bash
npm run dev
```

### 3. Set Up the Frontend

Open a **second terminal** in the project root and run:

```bash
cd omniconvert-frontend
npm install
npm run dev
```

Vite will display the local development URL in the terminal, usually:

```text
http://localhost:5173
```

Open that URL in your browser to access the application.

> Keep both terminal windows running while using the application locally.

## ⚙️ Available Scripts

### Backend

| Command | Purpose |
|---|---|
| `npm start` | Start the backend server |
| `npm run dev` | Start the server with Nodemon |

### Frontend

| Command | Purpose |
|---|---|
| `npm run dev` | Start the Vite development server |
| `npm run build` | Build the frontend for production |
| `npm run preview` | Preview the production build |

## 🔧 Configuration

If the application requires environment variables, configure them according to the backend implementation.

- Keep API keys, credentials, and private configuration out of Git.
- Configure the frontend API endpoint to match the backend server.
- Use appropriate CORS settings when deploying the frontend and backend separately.

## 🔒 Security Notes

- Do not commit passwords, API keys, tokens, or private environment files.
- Validate uploaded files and enforce appropriate file-size limits.
- Review dependency audit warnings and update vulnerable packages safely.
- Configure production CORS rules instead of allowing every origin.

## 🗺️ Future Improvements

- Add support for more file formats.
- Improve file validation and error messages.
- Add conversion progress and download feedback.
- Improve responsive design and accessibility.
- Deploy the frontend and backend for public access.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request.

## 📄 License

A license has not yet been specified. Add a `LICENSE` file before distributing the project under a particular open-source license.

---

**Developed by [sudhagirishgeet](https://github.com/sudhagirishgeet)**

⭐ If you find this project useful, consider giving the repository a star.
