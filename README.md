# LSN-MOTORS Three-phase induction motor behavior: interactives

Interactive simulations for LSN-MOTORS (CBT Technology Institute, lesson). Each lesson has self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The Canvas pages link to them through GitHub Pages.

Live site: https://luisleon-cbt.github.io/lsn-motors/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| lesson1 | Three-phase induction motor behavior | rotating-field.html | slip-challenge.html | motor-test-bench.html | vfd-start-lab.html |

## Publishing

1. Push this folder to the `main` branch of `luisleon-cbt/lsn-motors`.
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Each page is then live at `https://luisleon-cbt.github.io/lsn-motors/lessonN/<file>.html`.

The pages load the CBT logo from `luisleon-cbt/items`, and GSAP, Three.js, and fonts from public CDNs. They still work if a CDN fails (a 2D view replaces the 3D one) and need no build step.
