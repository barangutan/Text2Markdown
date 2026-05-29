# Text2Markdown

Text2Markdown is a lightweight web app that converts plain text into Markdown using simple formatting heuristics.

## Features

- Convert pasted plain text to Markdown in the browser
- Basic heading detection
- List normalization for bullets and numbered lists
- Basic emphasis handling (`*italic*`, `**bold**`)
- Copy generated Markdown to clipboard

## Tech Stack

- React
- Vite
- TypeScript (project config)
- Tailwind CSS (CDN in `index.html`)

## Getting Started

### Prerequisites

- Node.js 18+ (recommended)
- npm

### Install

```bash
npm install
```

### Run locally

```bash
npm run dev
```

Then open the local Vite URL shown in the terminal (typically `http://localhost:5173`).

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Project Structure

- `/index.html` – Main app markup and converter logic
- `/index.tsx` – Entry placeholder
- `/vite.config.ts` – Vite configuration
- `/metadata.json` – App metadata

## Notes

- Conversion uses heuristics and may require manual Markdown cleanup for complex text.
- Input is processed client-side in the browser.

## License

This project is licensed under the MIT License.
