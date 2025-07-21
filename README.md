# Crypto Hustle Lite

Crypto Hustle Lite is a minimal React + Vite starter template, featuring fast development, HMR, and ESLint integration.

## Features

- ⚡️ Vite for fast builds and hot module replacement
- ⚛️ React 19
- 🧹 ESLint with recommended rules and React hooks support
- 🎨 Custom styles in [`src/App.css`](src/App.css)
- 🔑 Environment variable support via `.env`

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation

```sh
npm install
```

### Development

Start the development server:

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build

Create a production build:

```sh
npm run build
```

### Preview

Preview the production build:

```sh
npm run preview
```

### Lint

Run ESLint:

```sh
npm run lint
```

## Project Structure

```
crypto_hustle/
  ├── public/
  ├── src/
  │   ├── App.jsx
  │   ├── App.css
  │   ├── main.jsx
  │   ├── index.css
  │   └── assets/
  ├── .env
  ├── package.json
  ├── vite.config.js
  ├── eslint.config.js
  └── README.md
```

## Environment Variables

Set your API key in `.env`:

```
VITE_APPAPI_KEY="your_api_key_here"
```

## License

MIT
