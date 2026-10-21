# OddTrie

Personal website for OddTrie's ports, mods, apps and other projects.

## GitHub Pages

Publish this folder at the root of the `OddTrie/oddtrie.github.io` repository.
In repository Settings → Pages, select **Deploy from a branch**, **main**, and **/ (root)**.

Website: https://oddtrie.github.io

## Layout

- `index.html` is the whole site: the home page (load order) plus the OddTV and S2Recomp pages, switched with `#oddtv` / `#s2recomp` links. No build step.
- `assets/` holds the images: the OddTrie logo, the Discord server icon, OddBot, the OddTV icon and the S2Recomp screenshot.
- `old-concept/` is the earlier dark concept page, kept for reference. Delete it when you no longer need it.

## Editing

- Add a project: copy one `<li>` in the load order list in `index.html`, change its slot number, text and icon.
- Discord invite: https://discord.com/invite/YwAx7DrrFY (used in the top bar and the Community card).
- S2Recomp is in progress, and OddBot is private for now.
