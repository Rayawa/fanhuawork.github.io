# fanhuawork.github.io

English | [简体中文](README_zh.md)

An archived static website for game-service descriptions and related resources.

Archived project retained for reference.

## Overview

The site contains a landing page, game-specific descriptions and static assets. The project landing page focuses on the service catalogue; personal profiles and recruitment details are excluded from it.

## Technology and Dependencies

HTML, CSS and image assets. A browser and static HTTP server are sufficient; Python 3 is an optional local server. No package manifest or frontend build is included.

## Repository Structure

- `index.html` — landing page
- `job/` — game-specific pages
- `static/` — styles and images
- `404.html` — error page

## Quick Start

Serve the repository root so absolute asset paths resolve correctly:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/`. Edit the HTML and assets directly; no frontend build is required.
