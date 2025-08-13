Typing Falling Letters

 Overview
  --------
  Simple typing game implemented with Canvas and ES6.
  The player types falling letters to collect them. Golden letters are rarer and worth double points.

  Rules
  -----
  - Press Start to begin a 20-second session.
  - Letters spawn from the top edge and fall downwards.
  - Type a letter on your keyboard to collect the lowest matching falling letter.
  - Normal letter = 10 points, Golden letter = 20 points.
  - After the session ends, a result screen shows a formula and a detailed breakdown.

  Files
  -----
  - index.html : single-file implementation (HTML, CSS, JS).

  How to run
  ----------
  1. Open `index.html` in a modern browser (Chrome, Edge, Firefox, Safari).
  2. No build step required. Project uses only browser APIs.

  Production notes
  ----------------
  - Keep canvas resolution constant for deterministic physics. For hi-dpi support consider rendering to an offscreen buffer and scaling.
  - To integrate in a build pipeline: extract JS to a module file, use bundler (Webpack/Rollup) and minify for production. Keep source maps for debugging.
  - Accessibility: add focus management and keyboard hints. Consider on-screen touch controls for mobile.

