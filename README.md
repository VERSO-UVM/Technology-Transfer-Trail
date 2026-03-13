# Technology Transfer Trail

A static educational website that explains the university technology transfer journey using a "trail" metaphor, with examples and practical resources for researchers and students.

## Overview

This site presents the full process of moving research into real-world impact through three pathways:

- Licensing to industry
- Launching a startup
- Open source release

It is designed as a lightweight, no-build project using plain HTML and CSS.

## Project Structure

```text
.
|- index.html           # Landing page and high-level intro
|- trail.html           # Five-stage process walkthrough
|- pathways.html        # Licensing, startup, and open source pathways
|- case-studies.html    # Real-world and illustrative examples
|- resources.html       # Programs, funding, tools, and contacts
|- css/
|  \- style.css         # Shared styling across all pages
\- img/                 # Site images and SVG assets
```

## Run Locally

Because this is a static site, you can open `index.html` directly in a browser.

For a local server workflow (recommended), run one of the following from the project root:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Editing Guide

- Content updates are made directly in the relevant `.html` file.
- Global style changes should be made in `css/style.css`.
- Keep navigation labels and links consistent across all pages.
- Optimize new images before adding them to `img/` to keep page load fast.

## Notes

- External links (program pages, funding resources, and UVM references) should be periodically reviewed for accuracy.
- This project currently uses no JavaScript and no package/dependency manager.

## License

No license file is currently included in this repository. Add a `LICENSE` file if you want to define reuse terms.