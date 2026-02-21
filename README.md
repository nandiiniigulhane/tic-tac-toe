# Tic-Tac-Toe

A simple **React + Vite + TypeScript** implementation of the classic Tic-Tac-Toe game.

---

## Features

- Two-player gameplay
- Interactive game board
- Winner detection
- Draw detection
- Docker support

---

## Project Setup

### 1. Clone the repository

```bash
git clone https://github.com/nandiiniigulhane/tic-tac-toe.git
cd tic-tac-toe
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the application locally

```bash
npm run dev
```

Open the app in your browser:

```
http://localhost:8080
```

---

# Docker

This project includes a Dockerfile to run the application inside a container.

### Build Docker image

```bash
docker build -t tic-tac-toe:v1.0 .
```

### Run the container

```bash
docker run -p 8080:80 tic-tac-toe:v1.0
```

Open:

```
http://localhost:8080
```

---

# Docker Compose

Docker Compose allows you to start the application with a single command.

### Run the application using Docker Compose

```bash
docker compose up --build
```

### Run in detached mode

```bash
docker compose up -d
```

### Stop the containers

```bash
docker compose down
```

Open the application:

```
http://localhost:8080
```

---

# Production Build

To build the optimized production version:

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

## Tech Stack

- React
- TypeScript
- Vite
- Docker
- Docker Compose
- Nginx (for production container)

---

## Author

Nandini Gulhane
