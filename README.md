# 🛍️ E-Commerce Setup Guide
---

## ⚙️ Prerequisites

Before you begin, make sure the following are installed:

- **Node.js** (v18+ recommended) → [Download Node.js](https://nodejs.org/)
- **PostgreSQL** → [Download PostgreSQL](https://www.postgresql.org/)
- **Git** → [Download Git](https://git-scm.com/)
- **Code Editor** → [VS Code](https://code.visualstudio.com/) recommended

### 📦 Clone the Repository

To get started, clone this repository and navigate into the project folder:

```bash
git clone https://github.com/zie1203/E-Commerce
cd evershop-clone
```

### ⚙️ Install Dependencies

Make sure you have Node.js and PostgreSQL installed. Then install project dependencies:

```bash
npm install
```

### 🌐 Set Up Environment Variables

Create a `.env` file in the root directory and add your database details:

```env
DB_HOST=localhost
DB_PORT=5432
DB_NAME=evershop
DB_USER=your_postgres_user
DB_PASSWORD=your_postgres_password
```

### 🛠 Initialize the Project

After setting up `.env`, run the setup script:

```bash
npm run setup
```

### 🚀 Start the Development Server

Finally, start the app:

```bash
npm run dev
```

Then open your browser and visit:

[http://localhost:3000](http://localhost:3000)


