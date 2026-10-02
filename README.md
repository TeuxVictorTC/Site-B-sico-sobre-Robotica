# Robotica

A simple, responsive website introducing robotics to beginners. It covers the sense–think–act loop, real-world applications, common questions, and first steps in learning.

## Run locally

The GitHub copy contains `index.html` and `robot.webp` at the repository root. No packages or build step are required.

```sh
python -m http.server 8000
```

Open `http://localhost:8000` in your browser. You can also open `index.html` directly.

## Edit

Page content and CSS are in `index.html`. The FAQ uses native HTML disclosure elements, so no JavaScript is required. `robot.webp` is an AI-generated concept illustration; it does not depict a specific commercial robot.

The site supports narrow screens, keyboard navigation, visible focus states, and reduced-motion preferences.
