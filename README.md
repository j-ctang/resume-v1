# Justin Tang — Resume

Source for my personal resume site, live at [j-ctang.github.io](https://j-ctang.github.io/).

Built with React, TypeScript, Tailwind CSS, and Framer Motion.

## Features

- Dark / light mode, auto-detected with manual toggle
- Expandable experience entries (inline on desktop, modal on mobile)
- PDF download
- SEO & ATS friendly — full CV content is injected into static HTML at build time (JSON-LD, semantic `<noscript>` fallback)
- 3D photo flip easter egg

## Development

```bash
npm install
npm run dev      # local dev server
npm run build    # production build to dist/
npm run lint
```

Resume content lives in [`src/data/resume-config.ts`](./src/data/resume-config.ts); field reference is in [`src/data/resume-config.example.ts`](./src/data/resume-config.example.ts).

## Deployment

Pushes to `main` deploy automatically to GitHub Pages via [`.github/workflows/deploy.yml`](./.github/workflows/deploy.yml).

## Credits

Based on [clementbouly/interactive-resume-template](https://github.com/clementbouly/interactive-resume-template) (MIT licensed).

## License

MIT
