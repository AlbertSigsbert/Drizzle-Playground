# 💧 Drizzle ORM Playground (PostgreSQL)

A minimal TypeScript project set up to explore and test Drizzle ORM features using a PostgreSQL backend.

## 🚀 Getting Started

### Prerequisites

* Node.js (LTS version)
* A running PostgreSQL database instance.

### Setup

1.  **Clone the repository:**
    ```bash
    git clone [your-repo-link]
    cd drizzle-playground
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Create Environment File:**
    Create a `.env` file in the project root with your database connection URL. This file is ignored by Git.

    **.env**
    ```
    DATABASE_URL="postgresql://user:password@host:port/database"
    ```

### Running the Playground

Use the predefined `dev` script to run the entry point file (`src/main.ts`) using `tsx`.

```bash
npm run dev