# Casama gallery

Themes, color schemes, wallpapers and skills for Casama. A pull request is how someone contributes.
Casama reviews it, and a merge is what every app sees, without an app release.

Each item is a folder:

```text
themes/<id>/item.json
themes/<id>/theme.json
schemes/<id>/item.json
schemes/<id>/scheme.json
wallpapers/<id>/item.json
wallpapers/<id>/wallpaper.json
skills/<id>/item.json
skills/<id>/SKILL.md
```

`item.json` names the author and the license. Looks use CC0-1.0 or CC-BY-4.0. Skills use MIT or Apache-2.0.
Color schemes give a seed, a background and a text color for light and dark. Text on the background has to
pass WCAG AA. Fonts have to be ones the app already ships. Photos from Unsplash's API stay in photo search
and are not copied here.

Check the tree and refresh `index.json`:

```sh
node scripts/casama-gallery-check.mts
```
