# DEV × AYAN — React Portfolio

A multi-section, responsive creative developer portfolio built with React + Vite. This is a complete portfolio concept, not a single Hairline demo.

## Included
- Expanded long-form portfolio: hero, 12-project index, about, principles, services, capability grid, featured AHONA case study, learning timeline, three interaction labs, Hairline playground, process, notes, FAQ, contact and footer
- Twelve project entries using six custom CSS visual systems, category filters and detail modals
- GSAP + ScrollTrigger reveal and parallax motion
- Multiple custom interaction studies plus Hairline pointer-reactive terrain with an inline SVG fallback
- Responsive mobile navigation, accessible buttons, reduced-motion support
- Contact email copy interaction and social links
- Lime / warm-white / ink visual system, custom typography and fine-detail states

## Run locally
Node.js 18+ recommended.

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

Vite outputs the production build to `dist/`. Deploy `dist/` to Netlify or Vercel. Build command: `npm run build`; output directory: `dist`.

## Before publishing
- Replace `hello@devxayan.com` in `src/App.jsx` with your real contact email.
- Review the concept projects and descriptions in `src/data.js`; they are portfolio concept visuals, not claims that each project is a live client delivery.
- Update social links if needed.

Google Fonts and Hairline are loaded externally. The terrain includes a local SVG fallback so the layout still renders if Hairline fails to load. Project mockups are made with CSS and do not depend on stock imagery.
