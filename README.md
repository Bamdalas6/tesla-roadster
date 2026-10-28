# Redline Cockpit

A fighter-jet-style cockpit UI wrapped around a real-time 3D Roadster, built with Three.js. The car drives down a wet night-city street, takes off on lift jets and flies a thruster-powered barrel roll.

Unofficial concept, not affiliated with Tesla. The car is modelled in code after public photos.

## Run it

It is a single static page with no build step. Three.js loads from the jsDelivr CDN.

```bash
python -m http.server 3600
```

Then open http://127.0.0.1:3600. Any static host works (Cloudflare Pages, GitHub Pages, Netlify): serve `index.html` from the repo root.

## Controls

| Key | Action |
| --- | --- |
| Drag / scroll | Orbit and zoom the camera |
| C | Next camera |
| O | Slow orbit |
| W | Cycle rear wing |
| D | Doors (pit stop) |
| T (hold) | Fire thrusters |
| F | Take off / land |
| B | Barrel roll |
| 1 / 2 / 3 | Street / Sport / Track mode |

The dock also switches between the street and the studio, toggles the cinema camera, and loads your own `.glb` car model.
