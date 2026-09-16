# L2-web — AIOT-DA DIC-1

Do in Class 1 (DIC-1) for the **AIOT-DA** course.

## Live Demo

https://babyish23.github.io/L2-web/

![Live demo snapshot](docs/live-demo.png)

## Assignment

Build a personal webpage that shows:

- Name: **Liao Chia Hui（廖家暉）**
- Current local time (updates every second)

## Deliverables

| Item | Link |
| --- | --- |
| Public repository | https://github.com/babyish23/L2-web |
| Live site (GitHub Pages) | https://babyish23.github.io/L2-web/ |

## What was done

1. Created `index.html` with name and a live clock
2. Pushed the project to a public GitHub repository
3. Deployed with **GitHub Pages** (`main` branch, site root)
4. Added `.nojekyll` so the static page builds correctly
5. Added Cursor skills under `.cursor/skills/` (`grill-me`, `grilling`)

## How to open locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8765
```

Then visit `http://127.0.0.1:8765/`.

## Update / redeploy

Edit files → commit → push to `main`. GitHub Pages redeploys automatically.
