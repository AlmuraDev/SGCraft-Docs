<p align="center">
  <a href="https://almuradev.github.io/SGCraft-Docs/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://almuradev.github.io/SGCraft-Docs/logo.svg">
      <img src="https://almuradev.github.io/SGCraft-Docs/logo-light.svg" alt="SGCraft Remake 3.0" width="480">
    </picture>
  </a>
</p>

<h3 align="center">
  <a href="https://almuradev.github.io/SGCraft-Docs/">Read the SGCraft wiki &rarr; almuradev.github.io/SGCraft-Docs</a>
</h3>

---

The wiki for [SGCraft](https://github.com/AlmuraDev/SGCraft): Markdown pages in `wiki/`, built into a themed HTML site
by `tools/build.py` and published with GitHub Pages.

The site is built again whenever SGCraft's remake branch gets a commit, from that commit, and whenever the wiki here
changes. To build it yourself, clone this repository beside SGCraft, install Python 3 and Pillow, and run
`python tools/build.py` from here; `--mod <path>` points it at an SGCraft clone somewhere else. See
[wiki/README.md](wiki/README.md) for how the pages are written.
