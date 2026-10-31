# Roomido redesign

A responsive redesign of Roomido AI using Tailwind CSS v4 locally (no Tailwind CDN, Bootstrap, AOS or icon CDN).

## Requirements
- Node.js 20+
- npm

## Run locally
```bash
npm install
npm run dev
```
Open `index.html` with a local server (for example VS Code Live Server).

## Production CSS
```bash
npm run build
```
The generated stylesheet is `dist/style.css`.

## Notes
- Tailwind is compiled locally using the official CLI.
- Google Fonts and the existing image-hosting URLs are still remote assets. No CSS framework or icon library is loaded from a CDN.
- Replace the sample testimonial text with verified customer feedback before publishing.
