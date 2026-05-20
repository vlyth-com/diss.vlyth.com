# Digital Business Card

An interactive 3D digital business card by **Vlyth (Adam Wherrett)** — built for the university showcase as a quick, memorable way to share my details.

![Front face](docs/front.png)
![Back face](docs/back.png)

---

## About

This is a single-page web experience: a dark-themed business card with 3D tilt physics, light reflections that follow your mouse, and a smooth flip animation revealing my bio on the reverse. No framework runtime ships to the browser — just vanilla JavaScript driving all the interactions.

**Front:** my name, role, and direct links (email, dissertation, GitHub, LinkedIn).
**Back:** a short bio with inline links, rendered from Markdown.

## Tech

Built with [Astro](https://astro.build) for static-site generation, [astro-icon](https://github.com/niconiahi/astro-icon) for vector icons via Iconify (Lucide + Simple Icons), and custom vanilla JS for tilt, mouse-light, and flip animations. Fully client-side — zero server required.

## Interactions

| Feature | What it does |
|---------|-------------|
| **3D tilt** | Drag the background to tilt the card up to 25° with spring physics on release |
| **Mouse light** | Subtle radial gradients follow your cursor across the card surface |
| **Flip** | Click the refresh button to rotate the card and reveal the bio on the back |
| **Hint** | If you haven't flipped after 10 seconds, a gentle nudge appears |
| **Entrance** | The card swipes up from below with a slight overshoot bounce |

## Project origin

This showcase card is a personal fork of [`vlyth-exe/digital-business-card`](https://github.com/vlyth-exe/digital-business-card), the template I originally built for this project.

---

<div align="center">
  <a href="https://github.com/vlyth-exe/digital-business-card">Original template repo</a>
</div>
