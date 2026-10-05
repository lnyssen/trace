# TRACE

Draw in the air. Trace watches your hand through the camera and turns your movement into a living line — no pen, no surface, just gesture becoming light. Pinch thumb and index to draw, open your hand to lift the pen. Six brushes, colour drift, PNG export.

**Try it:** https://trace-air.vercel.app · **Guide (PDF):** https://trace-air.vercel.app/guide.pdf

A single `index.html`, no build step. Hand tracking by [ml5.js](https://ml5js.org/) (MediaPipe Hands), drawing with [p5.js](https://p5js.org/), both loaded from a CDN. The camera only works over `https://` (or on `localhost`).

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

`guide.html` is the source of `guide.pdf` (print it with Chrome headless — see the comment at its top).

Part of [Laurent Nyssen's creative lab](https://laurentnyssen.be/lab). MIT licence.
