# Prison Escape

A browser-based stealth game built with HTML5 Canvas. You've been wrongfully imprisoned — sneak past the guards and escape to freedom!

## Play

Open `index.html` in any modern browser, or [play online](https://yourusername.github.io/prison-escape/).

## Controls

| Key | Action |
|-----|--------|
| WASD / Arrow Keys | Move |
| E | Sprint (1.5s burst, 10s cooldown) |
| R | Restart level |

## Gameplay

- **Stay in the shadows** — guards will detect you instantly if you step into their light
- **Use sprint wisely** — sprinting through light triggers a brief chase, but walking triggers a full pursuit
- **Watch patrol patterns** — guards pause and look around at waypoints
- **5 levels** of increasing difficulty with more guards and complex layouts

## Features

- Dynamic shadow casting with ray-traced light cones
- Smooth guard AI with realistic patrol behavior
- Particle effects for sprinting and capture
- Gritty prison aesthetic with scanline overlay
- Mobile-friendly (works on phones/tablets)

## Hosting

This is a single self-contained HTML file. To host:

**GitHub Pages:**
1. Push to a GitHub repository
2. Go to Settings → Pages
3. Set source to main branch
4. Your game will be live at `https://yourusername.github.io/prison-escape/`

**Any web server:**
Just upload `index.html` — no build step or dependencies required.

## License

MIT License — feel free to modify and share!
