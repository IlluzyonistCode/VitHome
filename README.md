# VitHome

> *Your perfect stay, discovered and booked instantly.*

![JSON](https://img.shields.io/badge/JSON-000000.svg?style=flat-square&logo=JSON&logoColor=white)  ![npm](https://img.shields.io/badge/npm-CB3837.svg?style=flat-square&logo=npm&logoColor=white)  ![Autoprefixer](https://img.shields.io/badge/Autoprefixer-DD3735.svg?style=flat-square&logo=Autoprefixer&logoColor=white)  ![Mongoose](https://img.shields.io/badge/Mongoose-F04D35.svg?style=flat-square&logo=Mongoose&logoColor=white)  ![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A.svg?style=flat-square&logo=PostCSS&logoColor=white)  ![.ENV](https://img.shields.io/badge/.ENV-ECD53F.svg?style=flat-square&logo=dotenv&logoColor=black)  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=JavaScript&logoColor=black)  ![Nodemon](https://img.shields.io/badge/Nodemon-76D04B.svg?style=flat-square&logo=Nodemon&logoColor=white)  ![React](https://img.shields.io/badge/React-61DAFB.svg?style=flat-square&logo=React&logoColor=black)  ![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=flat-square&logo=Docker&logoColor=white)  ![Vite](https://img.shields.io/badge/Vite-646CFF.svg?style=flat-square&logo=Vite&logoColor=white)  ![ESLint](https://img.shields.io/badge/ESLint-4B32C3.svg?style=flat-square&logo=ESLint&logoColor=white)  ![Axios](https://img.shields.io/badge/Axios-5A29E4.svg?style=flat-square&logo=Axios&logoColor=white)  ![CSS](https://img.shields.io/badge/CSS-663399.svg?style=flat-square&logo=CSS&logoColor=white)  ![datefns](https://img.shields.io/badge/datefns-770C56.svg?style=flat-square&logo=date-fns&logoColor=white)

## Overview

VitHome is a full-stack MERN application for property rental discovery and booking. A React client handles search and listing display while an Express backend manages availability, reservations, and user authentication.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

---

## Features

|      | Component         | Details                                                                                                                                                                                                                                          |
| :--- | :---------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ⚙️  | **Architecture**  | <ul><li>Full-stack **MERN** app (MongoDB, Express, React, Node.js)</li><li>Split `client/` + `server/` monorepo structure</li><li>Client bootstrapped with **Vite** + React (JSX)</li><li>REST API backend served via Express</li><li>Environment config via `.env` (server-side)</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>ESLint enforced via `.eslintrc.json`</li><li>Consistent code style across `jsx`, `js`, and `cjs` files</li><li>**Nodemon** used for dev-time auto-reload on server</li><li>PostCSS + Tailwind config via `*.config.cjs` files</li></ul> |
| 📄 | **Documentation** | <ul><li>Minimal — `server/.env` referenced in Docker docs</li><li>No dedicated docs folder or wiki detected</li><li>`LICENSE` file present</li><li>Inline code comments assumed but not verified</li></ul> |
| 🔌 | **Integrations**  | <ul><li>**Axios** for HTTP client requests (client → server)</li><li>**Mongoose** for MongoDB ODM</li><li>**Multer** for file/image upload handling</li><li>**image-downloader** for fetching remote images</li><li>**date-fns** for date formatting/manipulation</li><li>**JWT** (`jsonwebtoken`) for auth token generation</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Clear client/server separation of concerns</li><li>`react-router-dom` enables client-side page routing</li><li>Tailwind utility classes promote reusable UI styling</li><li>`@vitejs/plugin-react` isolates React-specific build config</li></ul> |

---

## Project Structure

```
└── VitHome/
    ├── client
    │   ├── .eslintrc.json
    │   ├── .gitignore
    │   ├── index.html
    ├── LICENSE
    ├── logo.png
    ├── README.md
    └── server
        ├── .env
        ├── index.js
        ├── models
        ├── package-lock.json
        ├── package.json
        └── userfiles
```

---

## Getting Started

### Prerequisites

- Python 3.10+ / Node.js 18+ *(depending on the stack above)*

### Installation

```sh
git clone "https://github.com/IlluzyonistCode/VitHome
cd VitHome"
npm install
```

### Usage

```sh
npm start
```

---

## Contributing

- [Report Issues](https://github.com/IlluzyonistCode/VitHome/issues)
- [Submit Pull Requests](https://github.com/IlluzyonistCode/VitHome/pulls)
- [Discussions](https://github.com/IlluzyonistCode/VitHome/discussions)

---

## License

Distributed under the [AGPL-3.0](LICENSE) license.
