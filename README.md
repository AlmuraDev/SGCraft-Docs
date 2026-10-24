# SGCraft-Docs

The wiki for [SGCraft](https://github.com/AlmuraDev/SGCraft): Markdown pages in `wiki/`, built into a themed HTML site
by `tools/build.py` and published with GitHub Pages.

The site is built again whenever SGCraft's remake branch gets a commit, from that commit, and whenever the wiki here
changes. To build it yourself, clone this repository beside SGCraft, install Python 3 and Pillow, and run
`python tools/build.py` from here; `--mod <path>` points it at an SGCraft clone somewhere else. See
[wiki/README.md](wiki/README.md) for how the pages are written.
