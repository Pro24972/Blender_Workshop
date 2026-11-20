# Beyond Imagination — Blender Workshop Website

A responsive, parent-friendly presentation website for a collaborative Blender 3D workshop. The site explains Blender in accessible language, introduces the creative process, and showcases the two supplied workshop renders.

## Pages

- `index.html` — Welcome page and workshop overview
- `blender.html` — What Blender is, the basic creative process, and where 3D is used
- `projects.html` — The International Space Station and Donut & Coffee projects
- `team.html` — The five workshop presenters

## Team

Aarnav Singh · Viraaj Diwakar · Sparsh Sharma · Parth Varshney · Kavish Khurana

All projects are presented as collaborative team work. No individual project credits are assigned.

## Run locally

No build step or package installation is required. Open `index.html` in a modern browser.

For a local web server, run this command from the project folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Project images

The original supplied renders are included in the project root:

- `iss-space-station.png`
- `donut-coffee.jpg`

The ISS image uses `object-fit: contain` to preserve the complete wide render. The donut image is also displayed without distorting its proportions.

## Notes

- The website uses HTML, CSS and vanilla JavaScript.
- Navigation, mobile menu and scroll-reveal effects work without a build tool.
- Google Fonts are loaded online when a connection is available; system fonts remain as a fallback.
- The site is designed for a laptop/projector presentation as well as mobile screens.
