<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=FULL%20STACK%20E-COMMERCE&fontSize=52&fontColor=FFD700&fontAlignY=42&desc=🛍️%20React%20%2B%20Node.js%20Online%20Store%20%C2%B7%20Client%20%2B%20Server&descAlignY=62&descColor=DCDCDC&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=20&duration=2800&pause=900&color=FFD700&center=true&vCenter=true&width=760&lines=%F0%9F%9B%92+Full-Stack+React+%2B+Node.js+Storefront;%F0%9F%94%90+Auth+%2B+Admin+%2B+User+Panels;%F0%9F%A7%A9+Modular+Controllers%2C+Models%2C+Middlewares;%F0%9F%93%B1+Responsive+React+Client;%F0%9F%8F%86+%231+GitHub+Committer+in+Colombia)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://github.com/NietoDeveloper">
    <img src="https://img.shields.io/badge/Engineer-Manuel%20Nieto-blue?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://committers.top/colombia#NietoDeveloper">
    <img src="https://img.shields.io/badge/Committers.top-%231%20Colombia-gold?style=for-the-badge"/>
  </a>
  <a href="https://react.dev/">
    <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=000"/>
  </a>
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/NietoDeveloper/FullStack_E-Commerce">
    <img src="https://img.shields.io/badge/📂_Source-NietoDeveloper%2FFullStack__E--Commerce-000000?style=for-the-badge&logo=github&logoColor=FFD700"/>
  </a>
</p>

</div>

---

## 📋 Overview

A **web application** built with **React**, **Node.js**, and JavaScript. This project consists of a client-side React application and a Node.js server. The client is located in the `client` folder, while the server and general instructions are in the root directory.

---

## 🗂️ Project Structure

```text
FullStack_E-Commerce/
├── client/                # React frontend
│   ├── public/
│   │   └── images/
│   └── src/
│       ├── components/
│       │   ├── Form/
│       │   ├── Layout/
│       │   └── Routes/
│       ├── context/
│       ├── hooks/
│       ├── pages/
│       │   ├── Admin/
│       │   ├── Auth/
│       │   └── user/
│       └── styles/
├── config/                 # Server configuration
├── controllers/             # Business logic handlers
├── helpers/                  # Helper functions
├── middlewares/                # Express middlewares
├── models/                       # Database models
└── routes/                        # RESTful API endpoints
```

---

## 🔄 Application Flow

```mermaid
flowchart LR
    A([👤 User]) -->|Auth / Browse| B[React Client]
    B -->|API Request| C[Routes]
    C --> D[Middlewares]
    D --> E[Controllers]
    E -->|Helpers| F[Business Logic]
    E -->|CRUD| G[(Models\nDatabase)]
    G -->|Response| H([📦 Storefront / Admin View])

    style A fill:#FFD700,color:#000,stroke:#FFD700
    style E fill:#0a0a0a,color:#FFD700,stroke:#FFD700
    style G fill:#47A248,color:#fff,stroke:#47A248
    style H fill:#000,color:#FFD700,stroke:#FFD700
```

---

## 🛠️ Technology Stack

<div align="center">

| Layer | Technologies |
|:------|:-------------|
| 🎨 **Frontend** | React, JavaScript |
| ⚙️ **Backend** | Node.js |
| 🔧 **Version Control** | Git / GitHub |

</div>

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

### Installation

**Step 1 — Clone the repository**

```bash
git clone https://github.com/NietoDeveloper/FullStack_E-Commerce
```

**Step 2 — Navigate to the project root**

```bash
cd FullStack_E-Commerce
```

**Step 3 — Install server dependencies**

```bash
npm install
```

**Step 4 — Install client dependencies**

```bash
cd client
npm install
```

### Running the Application

**Start the server** from the root directory:

```bash
npm start
```

**Start the client** from the client folder:

```bash
cd client
npm start
```

Access the application at `http://localhost:3000` (or the specified port).

---

## 🗂️ Project Structure Notes

- **`/client`:** React frontend code.
- **`/`:** Node.js server code and configuration.
- **`/public`:** Static assets (if applicable).
- **`/src`:** Client-side source code.

---

## 📜 Available Scripts

**In the root directory:**

| Command | Description |
|:--------|:-------------|
| `npm start` | Runs the Node.js server |
| `npm test` | Runs server-side tests (if configured) |

**In the client directory:**

| Command | Description |
|:--------|:-------------|
| `npm start` | Runs the React development server |
| `npm build` | Builds the React app for production |
| `npm test` | Runs client-side tests |

---

## 👨‍💻 Author

**Manuel Nieto** — Software Developer

---

## 📄 License

This project is licensed under the **MIT License**.

<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>




















<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=FULL%20STACK%20E-COMMERCE&fontSize=52&fontColor=FFD700&fontAlignY=42&desc=🛍️%20React%20%2B%20Node.js%20Online%20Store%20%C2%B7%20Client%20%2B%20Server&descAlignY=62&descColor=DCDCDC&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=20&duration=2800&pause=900&color=FFD700&center=true&vCenter=true&width=760&lines=%F0%9F%9B%92+Full-Stack+React+%2B+Node.js+Storefront;%F0%9F%94%90+Auth+%2B+Admin+%2B+User+Panels;%F0%9F%A7%A9+Modular+Controllers%2C+Models%2C+Middlewares;%F0%9F%93%B1+Responsive+React+Client;%F0%9F%8F%86+%231+GitHub+Committer+in+Colombia)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://github.com/NietoDeveloper">
    <img src="https://img.shields.io/badge/Engineer-Manuel%20Nieto-blue?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://committers.top/colombia#NietoDeveloper">
    <img src="https://img.shields.io/badge/Committers.top-%231%20Colombia-gold?style=for-the-badge"/>
  </a>
  <a href="https://react.dev/">
    <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=000"/>
  </a>
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/NietoDeveloper/FullStack_E-Commerce">
    <img src="https://img.shields.io/badge/📂_Source-NietoDeveloper%2FFullStack__E--Commerce-000000?style=for-the-badge&logo=github&logoColor=FFD700"/>
  </a>
</p>

</div>

---

## 📋 Overview

A **web application** built with **React**, **Node.js**, and JavaScript. This project consists of a client-side React application and a Node.js server. The client is located in the `client` folder, while the server and general instructions are in the root directory.

---

## 🗂️ Project Structure

```text
FullStack_E-Commerce/
├── client/                # React frontend
│   ├── public/
│   │   └── images/
│   └── src/
│       ├── components/
│       │   ├── Form/
│       │   ├── Layout/
│       │   └── Routes/
│       ├── context/
│       ├── hooks/
│       ├── pages/
│       │   ├── Admin/
│       │   ├── Auth/
│       │   └── user/
│       └── styles/
├── config/                 # Server configuration
├── controllers/             # Business logic handlers
├── helpers/                  # Helper functions
├── middlewares/                # Express middlewares
├── models/                       # Database models
└── routes/                        # RESTful API endpoints
```

---

## 🔄 Application Flow

```mermaid
flowchart LR
    A([👤 User]) -->|Auth / Browse| B[React Client]
    B -->|API Request| C[Routes]
    C --> D[Middlewares]
    D --> E[Controllers]
    E -->|Helpers| F[Business Logic]
    E -->|CRUD| G[(Models\nDatabase)]
    G -->|Response| H([📦 Storefront / Admin View])

    style A fill:#FFD700,color:#000,stroke:#FFD700
    style E fill:#0a0a0a,color:#FFD700,stroke:#FFD700
    style G fill:#47A248,color:#fff,stroke:#47A248
    style H fill:#000,color:#FFD700,stroke:#FFD700
```

---

## 🛠️ Technology Stack

<div align="center">

| Layer | Technologies |
|:------|:-------------|
| 🎨 **Frontend** | React, JavaScript |
| ⚙️ **Backend** | Node.js |
| 🔧 **Version Control** | Git / GitHub |

</div>

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

### Installation

**Step 1 — Clone the repository**

```bash
git clone https://github.com/NietoDeveloper/FullStack_E-Commerce
```

**Step 2 — Navigate to the project root**

```bash
cd FullStack_E-Commerce
```

**Step 3 — Install server dependencies**

```bash
npm install
```

**Step 4 — Install client dependencies**

```bash
cd client
npm install
```

### Running the Application

**Start the server** from the root directory:

```bash
npm start
```

**Start the client** from the client folder:

```bash
cd client
npm start
```

Access the application at `http://localhost:3000` (or the specified port).

