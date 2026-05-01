# Meade Optical Tech

A growing collection of clinical calculators, references, and workflow tools for optometric practice — built and used at Meade Optical (Watertown & Lowville, NY).

Live at: [meadeopticaltech.org](https://meadeopticaltech.org)

## Tools

- **Vertex Distance Converter** (`/vertex/`) — Converts spectacle Rx to contact lens power and back, accounting for vertex distance.

## In Development

- **PD Calculator** — Monocular and binocular PD with near-vision compensation
- **Prism Resolver** — Horizontal/vertical prism component resolution

## Stack

- Static HTML/CSS/JS — no build step, no dependencies
- Hosted on Vercel via GitHub auto-deploy
- Single-file tools, fully self-contained

## Project Structure

```
/
├── index.html          Hub homepage
├── vertex/
│   └── index.html      Vertex distance converter
└── README.md
```

Each tool lives in its own folder. The folder name becomes the URL path.

## Adding a New Tool

1. Create a folder at the root: `/toolname/`
2. Add `index.html` inside it
3. Add a tool card to the homepage's tool grid
4. Push to GitHub — Vercel deploys automatically

## License & Disclaimer

Tools are provided as clinical references. Always verify results clinically; not a substitute for professional judgment.
