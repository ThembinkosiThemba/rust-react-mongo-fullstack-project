# Build a Rust Fullstack CRUD App with ReactJS, Axum, MongoDB, Docker

In this comprehensive project, you'll learn how to build a CRUD application with `React.js, Tailwind CSS, React Query, React-Hook-Form, and Axios`. In brief, we'll use CRUD (CREATE, READ, UPDATE, DELETE) methods to perform basic operations against a data layer via REST API.

We'll also explore how to create a robust API that supports Create, Read, Update, and Delete operations using the `Axum framework and MongoDB`. But before we dive in, let's first understand what RESTful APIs and CRUD operations are and why they matter.

## Getting Started

```bash
git clone <project-url>
cd <project name>
```

### Starting the backend

```bash
cd backend
```

Ensure you modify the `.env.example` file and add your own values then start the server by running `cargo run` which should build the server by downloading needed packages and running it.

### Starting the frontend

```bash
cd frontend
npm install --legacy-peer-deps
npm run dev
```

This should start your frontend and you can access it on the specified host.
