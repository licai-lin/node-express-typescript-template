# Node + Express + TypeScript Template

A minimal starter template for building REST APIs with **Express** and **TypeScript**.

## Features

- Express 5 setup
- TypeScript configuration
- Development workflow with `nodemon`
- Simple build and start scripts

## Requirements

- Node.js 18+
- npm

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Start development server:

```bash
npm run dev
```

3. Open:

```text
http://localhost:3000
```

You should see:

```text
Hello from TypeScript Express!
```

## Scripts

- `npm run dev` - Run in development mode with auto-reload
- `npm run build` - Compile TypeScript to `dist/`
- `npm start` - Run compiled app from `dist/index.js`

## Build for Production

```bash
npm run build
npm start
```

## Project Structure

```text
.
├── src/
│   └── index.ts
├── package.json
├── tsconfig.json
└── README.md
```

## Default Route

- `GET /` -> `Hello from TypeScript Express!`
